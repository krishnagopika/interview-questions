

1. What different types of selectors in CSS?

<details><summary>Show Answer</summary>

   CSS provides several types of selectors to target specific elements:
   - Element selectors: Select elements based on their HTML tag name (e.g., `div`, `p`, `h1`).
   - Class selectors: Select elements based on the value of their `class` attribute (e.g., `.my-class`).
   - ID selectors: Select a single element based on the value of its `id` attribute (e.g., `#my-id`).
   - Attribute selectors: Select elements based on the presence or value of a specific attribute (e.g., `[type="text"]`).
   - Pseudo-classes and pseudo-elements: Select elements based on specific states or positions in the document (e.g., `:hover`, `::before`).

</details>

2. What are the different ways to add CSS styling to an HTML page?

<details><summary>Show Answer</summary>

   There are three main ways to add CSS styling to an HTML page:
   - Inline CSS: Apply CSS directly to an HTML element using the `style` attribute.
   - Internal CSS: Place CSS code within the `<style>` tags in the `<head>` section of an HTML document.
   - External CSS: Link an external CSS file to the HTML document using the `<link>` element in the `<head>` section.

</details>

  
3. What is an ID selector?

<details><summary>Show Answer</summary>

   An ID selector in CSS is used to select a single HTML element based on its unique `id` attribute. It is denoted by a hash (#) followed by the ID name. ID selectors should be unique within an HTML document because they can only be assigned to one element.

 </details>

4. What is a class selector?

<details><summary>Show Answer</summary>

   A class selector in CSS is used to select multiple HTML elements that share the same `class` attribute. It is denoted by a dot (.) followed by the class name. Multiple elements can have the same class, allowing you to apply the same styling to multiple elements.


  </details>

  5. What is an element selector?

<details><summary>Show Answer</summary>

   An element selector in CSS is used to select HTML elements based on their tag names. It targets all elements of a specific type. For example, the element selector `p` selects all `<p>` elements in the document.
  
  </details>


6. What is the difference between flex and grid?

<details><summary>Show Answer</summary>

   Flexbox (`display: flex`) and CSS Grid (`display: grid`) are two CSS layout models with different approaches:
   - Flexbox is designed for one-dimensional layouts, either in a row or column. It provides flexible and dynamic alignment of elements within a container.
   - CSS Grid is a two-dimensional layout system that allows you to create complex grid-based layouts. It provides more control over rows and columns and allows items to be placed in any cell of the grid.
  
  </details>


7. What is the difference between class and ID selectors in CSS?

<details><summary>Show Answer</summary>

   Class selectors are denoted by a dot (.), while ID selectors are denoted by a hash (#). 
  The main difference is that a class selector can be applied to multiple HTML elements,
  while an ID selector can only be applied to a single HTML element. In other words,
  multiple elements can share the same class, but each element can have a unique ID.
  
 </details>


8. How do you apply multiple CSS styles to an element?

<details><summary>Show Answer</summary>

   You can apply multiple CSS styles to an element by separating them with semicolons (;). Each style declaration consists of a property followed by a colon (:) and its corresponding value.

   Example:
   ```css
   .my-class {
     color: red;
     font-size: 16px;
     text-align: center;
   }
   ```
 </details>

   
 9. What is the box model in CSS?

<details><summary>Show Answer</summary>

The box model is a fundamental concept in CSS that describes how elements are rendered on the web page. 
It consists of four main components: content, padding, border, and margin. The content area contains the 
actual content of the element, surrounded by padding, which creates space between the content and 
the border. The border surrounds the padding and content, and the margin is the space outside the border, 
creating separation between elements.

</details>


10. How do you change the color of text in CSS?

<details><summary>Show Answer</summary>
To change the color of text in CSS, you can use the color property. The color property accepts various color values, such as color names (e.g., "red", "blue"), hexadecimal values (e.g., "#ff0000" for red), RGB values (e.g., "rgb(255, 0, 0)" for red), or HSL values (e.g., "hsl(0, 100%, 50%)" for red).

Example:

css
Copy code
.my-text {
  color: blue;
}
In the above example, the text inside elements with the class "my-text" will be displayed in blue color.

</details>







 
