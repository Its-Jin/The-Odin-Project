# Basic Syntax 
<img src="https://cdn.statically.io/gh/TheOdinProject/curriculum/05ce472eabf8e04eeb2cc9139e66db884074fd7d/foundations/html_css/css-foundations/imgs/00.jpg" width=150>

# Selectors 
| Types of Selectors | Universal | Type aka element | Class | ID | 
|:------------------:|:---------:|:----------------:|:-----:|:--:|
| syntax             | *         | name of element | .class-name | #ID-name |


### Grouping and Chaining Selectors
```css
/* Grouping selectors decreases repetition by organizing similar declarations together */

.read, .unread{
    color:white;
    background:black;
}

/* Chaining selectors is used to specify and select specific elements. This can either be a combination of 2 class names or 1 class name followed by id */

<div class="subsection header"></div>
<div class="subsection id="preview"></div>

.subsection.header{ /* no spaces */
    color:red;
}

.subsection#preview{
    color:red;
}
```

### Combinator Selector
Combinator Selector also allows for the combination of selectors but shows a relationship between the selectors unlike grouping or chaining.
**Descendant Selector** 