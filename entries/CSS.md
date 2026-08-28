**Cascading Style Sheets** (**CSS**) is a style sheet language used for describing the presentation of a document written in a markup language such as HTML or XML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.

CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple web pages to share formatting by specifying the relevant CSS in a separate .css file, and reduce complexity and repetition in the structural content.

## History
CSS was proposed by Hakon Wium Lie on October 10, 1994. At the time, Lie was working with Tim Berners-Lee at CERN. Several other style sheet languages for the web were proposed around the same time, and discussions on public mailing lists and inside the World Wide Web Consortium (W3C) led to the first W3C CSS Recommendation (CSS1) being released in December 1996.

## Syntax
CSS has a simple syntax and uses a number of English keywords to specify the names of various style properties. A style sheet consists of a list of rules. Each rule or rule-set consists of one or more selectors, and a declaration block.

Example:
```css
body {
    background-color: #f8fafc;
    color: #1e293b;
}
```

In this example:
* `body` is the selector, pointing to the HTML element to style.
* `background-color` and `color` are properties.
* `#f8fafc` and `#1e293b` are values.