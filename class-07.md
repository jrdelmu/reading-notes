# Object-Oriented Programming, HTML Tables

[Main Page](https://jrdelmu.github.io/reading-notes/)

## Tables

**Tables** are a structured set of data displayed in rows and columns. Makes for a good way to display various forms of data. Tables are created with `<table>`.

### Table Structure Elements

- `<tr>` The table row starts the new row of the table
- `<td>` Table data is displayed inbetween these tags
- `<th>` Table headings headings function as just that, headings for the data in the table
- `<thead>` contains the headings
- `<tbody>` contains the body of the table
- `<tfoot>` stores the footer

## Functions, Methods, and Objects

### Creating an Object

`let car = new Object();`

**Properties:**
```
car.make = 'Honda';
car.model = 'Integra';
car.year = 1997;
```

**Method:**
```
car.checkYear = function{
  return this.year;
};
```

### Updating an Object

`car.model = 'NSX';` OR `car['model'] = 'NSX';`