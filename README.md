# myFetch
This node module package is to GET, POST, PUT & DELETE data from a API /others websites

## How to instal
```bash
npm i fetch-npm
```
## Example
```bash
let myFetch = require("fetch-npm");
myFetch.init({
    address: "https://reqres.in/api/users/",
    key: "1234"
})

myFetch.put("5", {
    name: 'Kasper'
}).then(data => console.log(data));
```