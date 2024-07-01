# Introduction to HTML and CSS
On this lesson we have learned the basics of HTML and CSS. We have learned how to create a simple webpage using HTML and how to style it using CSS. We have also learned how to use the Chrome Developer Tools to inspect the HTML and CSS of a webpage.

Remember that Chrome developer tools are a great way to test and experiment with HTML and CSS. But all the changes you make are temporary and will be lost when you refresh the page. If you want to make permanent changes to a webpage you will need to edit the HTML and CSS files directly.

# HTML basic tips
- HTML is a markup language that is used to create the structure of a webpage.
- To structure this page we use tags like `<h1>`, `<p>`, `<ul>`, `<li>`, `<a>`, `<img>`, etc. 
- Tags are used to create elements. Elements can have attributes like `id`, `class`, `href`, `src`, etc.

Example of an HTML element:
```html
<h1 id="main-title">Hello World</h1>
```
In this case, the element is a `<h1>` tag with the content "Hello World" and an `id` attribute with the value "main-title".

# CSS basic tips
- CSS is a styling language that is used to style the structure of a webpage.
- To style a webpage we use properties like `color`, `font-size`, `background-color`, `margin`, `padding`, etc.
- Properties are used to style elements. Elements can be styled using the tag name, the class name, or the id name.

Example of a CSS rule:
```css
#main-title {
  color: red;
  font-size: 24px;
}
```
Now we are styling the element with the `id` "main-title" with a red color and a font size of 24 pixels.

## Important!
- Don't forget to link your CSS file to your HTML using the `<link>` tag inside the `<head>`. 🤔

For more information check the portal on Week1 day 1.