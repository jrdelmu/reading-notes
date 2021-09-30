# Authentication

[Main Page](https://jrdelmu.github.io/reading-notes/)

## What is OAuth

1. What is OAuth?
  - open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential.
2. Give an example of what using OAuth would look like.
  - When you log onto a website and it offers one or more opportunities to log on using another website's logon.
3. How does OAuth work? What are the steps that it takes to authenticate the user?
4. What is OpenID?
- The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
- The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
- The first site gives this token and secret to the initiating user’s client software.
- The client’s software presents the request token and secret to their authorization provider.
- If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
- The user approves a particular transaction type at the first website.
- The user is given an approved access token.
- The user gives the approved access token to the first website.
- The first website gives the access token to the second website as proof of authentication on behalf of the user.
- The second website lets the first website access their site on behalf of the user.
- The user sees a successfully completed transaction occurring.
- OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed.

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?
  - rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphjone and authorize the device
2. What is Authorization Code Flow?
  - The user clicks Login within the regular web application.

  - Auth0's SDK redirects the user to the Auth0 Authorization Server `(/authorize endpoint)`.

  - Your Auth0 Authorization Server redirects the user to the login and authorization prompt.

  - The user authenticates using one of the configured login options and may see a consent page listing the permissions Auth0 will give to the regular web application.

  - Your Auth0 Authorization Server redirects the user back to the application with an authorization code, which is good for one use.

  - Auth0's SDK sends this code to the Auth0 Authorization Server `(/oauth/token endpoint)` along with the application's Client ID and Client Secret.

  - Your Auth0 Authorization Server verifies the code, Client ID, and Client Secret.

  - Your Auth0 Authorization Server responds with an ID Token and Access Token `(and optionally, a Refresh Token)`.

  - Your application can use the Access Token to call an API to access information about the user.

The API responds with requested data.
3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
  - The user clicks Login within the application.

  - Auth0's SDK creates a cryptographically-random code_verifier and from this generates a code_challenge.

  - Auth0's SDK redirects the user to the Auth0 Authorization Server `(/authorize endpoint)` along with the code_challenge.

  - Your Auth0 Authorization Server redirects the user to the login and authorization prompt.

  - The user authenticates using one of the configured login options and may see a consent page listing the permissions Auth0 will give to the application.

  - Your Auth0 Authorization Server stores the code_challenge and redirects the user back to the application with an authorization code, which is good for one use.

  - Auth0's SDK sends this code and the code_verifier `(created in step 2)` to the Auth0 Authorization Server `(/oauth/token endpoint)`.

  - Your Auth0 Authorization Server verifies the code_challenge and code_verifier.

  - Your Auth0 Authorization Server responds with an ID Token and Access Token `(and optionally, a Refresh Token)`.

  - Your application can use the Access Token to call an API to access information about the user.

  - The API responds with requested data.
4. What is Implicit Flow with Form Post?
  - The user clicks Login in the app.

  - Auth0's SDK redirects the user to the Auth0 Authorization Server `(/authorize endpoint)` passing along a response_type parameter of id_token that indicates the type of requested credential. It also passes along a response_mode parameter of form_post to ensure security.

  - Your Auth0 Authorization Server redirects the user to the login and authorization prompt.

  - The user authenticates using one of the configured login options and may see a consent page listing the permissions Auth0 will give to the app.

  - Your Auth0 Authorization Server redirects the user back to the app with an ID Token.
5. What is Client Credentials Flow?
  - Your app authenticates with the Auth0 Authorization Server using its Client ID and Client Secret (/oauth/token endpoint).

  - Your Auth0 Authorization Server validates the Client ID and Client Secret.

  - Your Auth0 Authorization Server responds with an Access Token.

  - Your application can use the Access Token to call an API on behalf of itself.

  - The API responds with requested data.
6. What is Device Authorization Flow?
  - The user visits the verification_uri on their computer, enters the user_code and confirms that the device that is being activated is displaying the user_code. If the user visits the verification_uri_complete by any other mechanism (such as by scanning a QR code), only the device confirmation will be needed.

  - Your Auth0 Authorization Server redirects the user to the login and consent prompt, if needed.

  - The user authenticates using one of the configured login options and may see a consent page asking to authorize the device app.

  - Your device app is authorized to access the API.
7. What is Resource Owner Password Flow?
  - The user clicks Login within the application and enters their credentials.

  - Your application forwards the user's credentials to your Auth0 Authorization Server `(/oauth/token endpoint)`.

  - Your Auth0 Authorization Server validates the credentials.

  - Your Auth0 Authorization Server responds with an Access Token `(and optionally, a Refresh Token)`.

  - Your application can use the Access Token to call an API to access information about the user.

  - The API responds with requested data.