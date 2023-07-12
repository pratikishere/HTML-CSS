This repo is created to learn HTML and CSS from [YouTube](https://www.youtube.com/watch?v=G3e-cpL7ofc)

### DOCTYPE

```
<!DOCTYPE html>
```

The HTML document type declaration, also known as DOCTYPE , is the first line of code required in every HTML or XHTML document.

### Language

```
<html lang="en">
```

Always define language of the pade it helps browser to display content in spcified language.

```
<title>Document</title>
```

### Title

Define title of the page so that it will be displayed in tab.

```
<a href="https://youtube.com" target="_blank">Link to YouTube</a>
```

In above syntax href and target are called HTML Attribute. It modifies how an element behaves.

### Hovers, Transitions, Shadows

```
  .tweet-button {
        background-color: rgb(2, 137, 255);
        color: white;
        border: none;
        height: 36px;
        width: 74px;
        border-radius: 18px;
        font-weight: bold;
        font-size: 0.85rem;
        cursor: pointer;
        transition: box-shadow 0.15s;
    }

    .tweet-button:hover {
      opacity: 0.7;
      box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.15); // right top blur color
    }

    .tweet-button:active {
      opacity: 0.4;
    }
```

The above code is style defined for tweet-button. :hover and :active are called pseudo style. trasition can be applied to more than 1 properties.

### Note: <p> by default, come with margin at top and bottom

### What is CSS Specificity?

[CSS Specificity](https://www.w3schools.com/css/css_specificity.asp)

If there are two or more CSS rules that point to the same element, the selector with the highest specificity value will "win", and its style declaration will be applied to that HTML element.

Think of specificity as a score/rank that determines which style declaration is ultimately applied to an element.

### What is void element?

A void element is an element whose content model never allows it to have contents under any circumstances. Void elements can have attributes. The following is a complete list of the void elements in HTML :

| area | base | br | col |
| command | embed | hr | img |
| input | keygen | link | meta |
| param | source | track | wbr. |

## CSS display Property

[W3 schools CSS display Property](https://www.w3schools.com/cssref/pr_class_display.php)

The display property specifies the display behavior (the type of rendering box) of an element.

### The display: block value

A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element. A block-level element always takes up the full width available (stretches out to the left and right as far as it can). Two commonly used block elements are: <p> and <div>

### The display: inline-block value

Displays an element as an inline-level block container. The element itself is formatted as an inline element, but you can apply height and width values

### The display: inline value

An inline element does not start on a new line and it only takes up as much width as necessary. The <span> element is an inline container used to mark up a part of a text, or a part of a document.

```
Note:
It is tricky o make image center in div horizontally or vertically. [how-to-center-an-image-in-a-div-css](https://www.freecodecamp.org/news/how-to-center-an-image-in-a-div-css/) This link explains differnt tricks and methods to make image in center.

[CSS position method](https://www.freecodecamp.org/news/css-position-property-explained/)

[flexbox method](https://www.freecodecamp.org/news/css-flexbox-tutorial-with-cheatsheet/)
```
