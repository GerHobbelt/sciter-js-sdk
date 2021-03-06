# class Element.Style

Instances of Element.Style class represent list of CSS properties set on element.

To get reference to style collection use ```element.style``` property.

#### Properties:  

Properties of Element.Style are CSS properties defined in CSS. To get set them use either camelCase notation as: 

```JavaScript
var bgColor = element.style.backgroundColor;
```

or the "hyphen case" form:

```JavaScript
var bgColor = element.style["background-color"];
```

#### Methods:

* `element.style.getPropertyValue(name)`
* `element.style.setProperty(name, value [,important])`
* `element.style.removeProperty(name)`
* `element.style.colorOf(name)` reports color property _name_ as instance of [`Graphics.Color`](Graphics.Color.md) class.

