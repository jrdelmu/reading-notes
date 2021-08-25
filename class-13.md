# The Past, Present, and Future of Local Storage for Web Applications

[Main Page](https://jrdelmu.github.io/reading-notes/)

- Browsers that support HTML5 Storage:
  - IE 8.0+
  - Firefoxe 3.5+
  - Safari 4.0+
  - Chrome 4.0+
  - Opera 10.5+
  - Iphone 2.0+
  - Android 2.0+
- HTML5 Storage utilizes named key/value pairs
- `setItem()` will overwrite a previous value if it is called with named key that already exists
- `getItem()` will return null if called with a non-existent key
- `removeItem()` with a non-existant key will do nthing
- `key()` with an index that is not between 0 -1  will return null if called in a function
