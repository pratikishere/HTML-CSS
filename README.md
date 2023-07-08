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
