# JavaScript Notes

[Home](README.md)

- conditionals
  - if
  - else
- operators ( + - = *)
- data types
  - string
  - boolean
  - number
- variable` var` `x = 42`, `UserName = Brandon`

## Objects and methods

- the document object represents the entire page
- write() method allows new conent wherever the `<Script>` element sits
- parameters go inside methods

<img src ="js example.jpg">

- java script will run where it is found in the html
- comment are done like C++ with a `//`
- store variable into strings bye using  ' string here'

``` 
var today = new Date();
var hourNow = today.getHours();
var greeting;


if (hourNow > 18) {
    greeting = 'Good Evening G!';
} else if ( hourNow > 12){
    greeting = 'Good Afternoon Playa!';
} else if (hourNow > 0){
    greeting = ' Good Morning Sunshine!';
} else {
    gretting = ' Welcome Sir ...';
}

document.write('<h3>'+ greeting + '</h3>')
```