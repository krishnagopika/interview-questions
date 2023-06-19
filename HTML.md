1. What is HTML?

<details><summary>Show Answer</summary>

HTML stands for Hyper Text Markup Language. It was created in 1989 by Tim Berners-Lee and Robert Calliau. HTML is used to define the structure and content of a webpage.(Building blocks of web pages)

**HyperText:** The document containes links that allow the reader to jump from one page to other page quickly and easily.
**Markup Language:** Markup Language is a way computers speack to each other to control how text is processed and presented. A markup language allows you to annotate text, and these annotations provide additional meaning to the contents of a document(Tags are markup). 
  
</details>

2. What are Tags?

<details><summary>Show Answer</summary>

  **1. Tags:** Tags are used to **mark up the start of an HTML element**. The syntax for tags is `<element-name>`. Most tags should be closed `</element-name>`. In simple terms Tags act like contaiers. They tell us someting about the information about that lies between opening and closing tags.

<i><b>Note:</b> The terms "tag" and "element"
are often used interchangeably. g, however, an
element comprises the opening tag and the closing tag and any content that lies between them.</i>

</details>

3. What are attributes?

<details><summary>Show Answer</summary>

  **2. Attributes:** Attributes are used to provide the **additional pieces of information** about the contents of an element. Attributes are placed inside an opening tag and every atrribute has two parts the name and value. syntax for attributes is

```html
<element-name attribute-name="attribute-value">
```

<i><b>Note: HTML5 allows uppercase atribute names and quotemarks can be ommited, but its a convention to use lowecase for attributes with quotes for attribute value.</b> </i>

</details>
  
  4. What is body tag?
  
  <details><summary>Show Answer</summary>

    `<body>`: Everything inside this element is
shown inside the main browser
window.
  
  </details>
    
 5. What is Head tag?
    
 <details><summary>Show Answer</summary>
   
   `<head>`: Before the `<body>` element you will often see a `<head>` element. This contains information about the page

  </details>
   
   6. What is title tag?
    
    
  <details><summary>Show Answer</summary>
    
    `<title>`: You will usually find a `<title>` element inside the `<head>` element. The contents of the `<title>`

  </details>

  7. What are heading tags?
    
  <details><summary>Show Answer</summary>

  </details>
    
    HTML has six "levels" of headings:

1. `<h1>`
2. `<h2>`
3. `<h3>`
4. `<h4>`
5. `<h5>`
6. `<h6>`

The number of headings is inversely proportional to the precedence of the heading. `<h1>` is the main heading and all the headings after that would be subheadings.
    
    
8. What is paragraph tag?
    
    <details><summary>Show Answer</summary>
      
      A paragraph consists of one or more sentences that form a self-contained unit of discourse. The start of a paragraph is indicated by a new line. 

```html

<p>By default, a browser will show
each paragraph on a new line
with some space between it and
any subsequent paragraphs</p>
```
      
9. What are list in HTML? List out various types of lists in HTML.


  </details>
    
    
1. **Ordered lists**: Ordered lists  are lists where each item in the list is numbered. For Ex: recipe and legal contract.

```html
<ol>
  <li> Each item in the list  </li>
</ol>
```

2. **Unordered lists**: Unordered lists are lists that begin with a bullet point (rather than characters that indicate order).

```html
<ul>
  <li> Each item in the list  </li>
</ul>
```

3. **Definition lists:** Definition lists are made up of a set of terms along with the definitions for each of those terms.

```html
<dl>
    <dt>the definitionterm</dt>
    <dd>The definition</dd>

</dl>
```

<i><b>Note:</b>Lists can be nested inside one another and the browser provided the indentation for the nested lists.</i>
    
    
    10. How to add links in HTML?
    
    <details><summary>Show Answer</summary>
      
      `<a>``</a>` is used to link one webage in the other webiste(absolute url) or the existing website(relative url).

```html
<a href="link"></a>

```

- to open the link in new tab use `target= "_blank"`.
- to create a link to an email use `<a href="mailto:email">`email</a>
- To link to specific part of same page ids can be used.
- To link to specific part of different page user absolute-url/#id ad href. 

  </details>
    
    

    
    



