Dynamic inputs,

It is a library designed to generate dynamic fields for its prior assessment and data counting.

<strong> Usage </strong>

```js
    var options = {
        id: "div_",
        icon: "trash",
        btn: ".bt_plus",
        element: "materials",
        addClass: "btn-danger",
        removeClass: "btn-info",
    };
    $ (document) .addItem (options);
```
* <strong> id: </strong> Is the identifier that we want to put to each of the dynamic fields (NOTE: "_" is not necessary).
* <strong> icon: </strong> Icon by which it will be replaced to remove the old line. 
* <strong> btn: </strong> It would be the class or the id of our button to add fields. 
* <strong> element: </strong> principal identifier of the first element / input. 
* <strong> addClass: </strong> Class to add to the button (Currently used to change the color). 
* <strong> removeClass:</strong> Class to remove from the button (Currently used to change the color). 

Demo: https://quecodig.github.io/dynamic-inputs/

<strong> Changelog </strong>

= 1.3 =
* Bug correction
* The code is optimized

= 1.2 =

* Bug correction
* Classes are added to give styles

= 1.0 =

Initial release

Changelog: https://www.phpcentral.com/pregunta/642/facturacion-con-diseno-en-bootstrap-multiples-inputs-dinamicos#resp_549406198764950208345d143aa67c7d
