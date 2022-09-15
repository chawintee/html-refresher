# html
- purpose 
    - To review all about HTML 
    - conclude in my understand
    - my english is poor.
---
## lesson 1 Start Here
```html
    <!DOCTYPE html>
    <html lang="en">

    <head>
        <meta charset="UTF-8" >  
        <style>
            html {
                font-size: 22px
            }
            body {
                background-color: #333;
                color: whitesmoke;
            }
        </style>
    </head>

    <body>
        <h1>Hello World!</h1>
        <p>This is my first web page.</p>
    </body>

    </html>
```
- `<!DOCTYPE html>`
    - declare Type of document 
- `<html> head and body </html>` 
    - tag of html contain open tag and close tag
    - have 2 tag inside
        - `<head> metadata </head>`
        - `<body> content in body </body>`
    - attribute mandatory is lang
- `<head> metadata </head>`
    - In have have data call meta data
    - `<meta charset="UTF-8" > `
        - is type of charactor
    - `<style> style you would link in your body </style>`
        - style of page about color, background-color
- `<body> content in body </body>`
    - content in your web page
    - `<h1> </h1>`
        - header
    - `<p> </p>`
        - paragraph
#### [Markup Validation Service](https://validator.w3.org)

---

## lesson 2 Head Element
```html
    <!DOCTYPE html>
    <html lang="en">

    <head>
        <meta charset="UTF-8" >  
        <meta name="author" content="Chawintee">
        <meta name="description" content="This page contains all the things I am learning how to create as I learn HTML.">
        <title>My First Web Page</title>
        <link rel="icon" href="html5.png" type="image/x-icon">
        <link rel="stylesheet" href="main.css" type="text/css">
    </head>

    <body>
        <h1>Hello World!</h1>
        <p>This is my first web page.</p>
    </body>

    </html>
```
- `<head> metadata </head>`
    - `<meta ${attribute} >`
        - data in head tag
    - `<title>My First Web Page</title>`
        - content that would like to show in top tab
    - `<link ${attribute} >`
        - link content out file to show in file (resource of webpage)
        - `rel`
            - rel is descript what you link
            - `icon` 
                - icon that would like to show in top tab
            - `stylesheet`
                - style that would like to show in body

#### [Markup Validation Service](https://validator.w3.org)
---

## lesson 3 Text Basics
```html
    <body>
    <h1>Hello World!</h1>

    <hr>

    <h2>I'm Ready to Learn HTML</h2>
    <p>This is my first web page.</p>

    <h3>My Daily Schedule</h3>
    <p>Let me tell you how 
      <br>&nbsp;&nbsp;&nbsp;...I learn more about web dex.
      <br>&nbsp;&nbsp;&nbsp;...I plan out my schedule.
      <br>&nbsp;&nbsp;&nbsp;...I use resources from <abbr title="Mozilla Developer Network">MDN</abbr> .
    </p>

    <hr>

    <h2>I Am Also Planning a Vacation</h2>
    <p>I've been working hard and <em> really need a getaway </em>.</p>
    <p>I live in <abbr title="Kansas">KS</abbr> so I want visit a beach.</p>

    <h3>Place I'd Like to Visit</h3>
    <p>I've heard good things about the Caribbean</p>
    <p>I've heard good thibngs about going here:</p>
    <address>
      Margaritaville Island Reserve Riviera Cancun <br>
      Bahia Perempich Puerto Morelos, Mexigo <br>
      Colonia Morelos, Mexico 77580
    </address>

    <!-- TODO: Add more places -->
    <h3>Place I Want to Avoid</h3>
    <p>Anywhere hot. <strong> No way! </strong> </p>
    
    <hr>
    &lt;&lt;&lt;&copy; Chawintee &gt;&gt;&gt;


  </body>
```

- `<body> content in body </body>`
    - `<hr>`
        - horizontal rule no closing tag
    - `<br>`
        - line break
    - `<em> content would emphasyst </em>`
        - emphasys
    - `<strong> content would strong </strong>`
        - strong meaning bigger and bolder
    - `&nbsp;`
        - " "
        - html whitespace 
    - `&lt;`
        - "<"
        - html lessthan 
    - `&copy;`
        - "©"
        - html copyright icon 
    - `&gt;`
        - ">"
        - html greater than 
    - `<abbr title="full meaning"> </abbr>`
        - abbriviation
        - have title then mouse over is show full meaning
    - `<address> Input your address </address>`
        - address
    - `<!-- your comment -->`
        - comment
#### [Markup Validation Service](https://validator.w3.org)
---
## lesson 4 Text List Types
```html
```
- list
    - have indence   
    - order list
        ```html
        <ol>
            <li> content </li>
            <li> content </li>
            <li> content </li>
        </ol>
        ```
        ```result
        Before content
            1. content
            2. content
            3. content
        After content
        ```
    - unorder list
        ```html
        <ul>
            <li> content </li>
            <li> content </li>
            <li> content </li>
        </ul>
        ```
        ```result
        Before content
            · content
            · content
            · content
        After content
        ```
    - discription list
        - dt - description term
        - dd - description detail   
        ```html
          <dl>
            <dt>North Pole</dt>
            <dd>I hear this is <strong>cold</strong>!</dd>

            <dt>South Pole</dt>
            <dd>This is also cold.</dd>

            <dt>Moutain Tops</dt>
            <dd>These are also cold.</dd>
          </dl>
        ```
        ```result
        North Pole
            I hear this is cold!
        South Pole
            This is also cold.
        Moutain Tops
            These are also cold.

        ```
#### [Markup Validation Service](https://validator.w3.org)
---
## lesson 5: Add Link
```html
```
- `<a href="Link"> ... </a>` 
    - anchor tag
    - `<a href="https://developer.mozilla.org/">MDN</a>`
        - this href `https://developer.mozilla.org/` call `absolute reference`
            - In case of link href `html5.png` or `main.css` `call relative reference`
- `<section id="..."> ... </section>`
    - section is seperate section.
- `<nav>  </nav>`
    - nav is navigation area
- `<a href="#">Back to Top</a>`
    - go to top of page
- `<a href="#Vacation">Back to Top</a>`
    - go to id "Vacation"
- Link Text Rule
    - #1 Avoid printing the full web address to the page.
    - #2 Avoid "links to" phrase We all know it is a link.
    - #3 Keep your link text short. Exact topic. Not sentences.
    - #4 No links that say "click here". It provides no meaning.
            
- Download
    - anchor tag for download `<a href="html5.png" download> HTML5 favicon</a> `
        - href 
        - download
- Mailto
    - anchor tag for mailto `<a href="mailto:chawintee.kmutt@mail.kmutt.ac.th">`
        - href
        - mailto:
- Dailto
    - anchor tag for mailto `<a href="tel:+66992761234">`
        - href
        - tel:+
- Open Google in `new tab`
    - anchor tag for newtab `<a href="https://www.google.com/" target="_blank">Google</a>`
        - target
        - target="_blank"
#### [Markup Validation Service](https://validator.w3.org)
---
# Reference
[HTML Full Course for Beginners By Dave Gray](https://www.youtube.com/watch?v=mJgBOIoGihA&t=61s)
