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