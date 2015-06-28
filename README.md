#JS Code Conventions ES5

#Types 
##Primitives 

```javascript
// String
var name        = 'Alejandro';
var lastname    = 'Lechuga';

// Number
var age         = 29;

// Boolean
var isAlive     = true;

// Null
var SSN         = null;

```
##Complex

```javascript
// Array
var fruit   = [];
var veggies = ['cucumber', 'potato', 'asparagus'];

// Object 
var rock  = {};
var water = {
  'state':        'liquid',
  'temperature':  80,
  'acid':         1  
};

// Nested Objects
var molecule = {
  'name': 'water'
  'atoms': [
    {'name': 'H'},
    {'name': 'H'},
    {'name': '0'}
  ]
};
```
## Naming Convention
```javascript

// Common
var enable_functionality      = true;       // {Boolean}
var enable_superpower         = false;      // {Boolean}
var computer_status           = 'running';  // {String}
var number_rows               = 15;         // {Number}
var object                    = {};         // {Object}
var array                     = [];         // {Array}

// DOM References
var container_HTMLDivElement    = $('#id');     // {Object:HTMLDivElement}
var list_HTMLUlElement          = $('<ul>');    // {Object:HTMLUlElement}

// Classes / Modules
var UserController;
function UserController () {};

// Methods Grammar Examples
function getList() {}
function setName(name) {}
function addItem(item) {}
function updateItem(item, data) {}
function removeItem(id) {}
function parseResponse(response) {}
function normalizeItem(item) {}
function fetchList() {}
```

## Strings
* Use single quotes for strings

```javascript
// Single quotes
var title = 'Les Miserables';

// concatenation 
var full_name = self.name + ' ' + self.lastname;
```
* If you have a string longer than 60 characters use the following patterns.

```javascript
// Parentheses pattern
var wikipedia = (
  'Wikipedia receives between 25,000 and 60,000 page '        + 
  'requests per second, depending on time of day.[245] Page ' + 
  'requests are first passed to a front-end layer of Squid'   +
  'requests per second, depending on time of day.[245] Page ' +
  'hey yeah'
);

// Array pattern
var wikipedia = [
  'Wikipedia receives between 25,000 and 60,000 page '        ,
  'requests per second, depending on time of day.[245] Page ' , 
  'requests are first passed to a front-end layer of Squid'   ,
  'requests per second, depending on time of day.[245] Page ' ,
  'hey yeah'
].join('');
```

