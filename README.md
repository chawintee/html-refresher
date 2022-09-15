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
- !DOCTYPE html
    - declare Type of document 
- html 
    - tag of html contain open tag and close tag
    - have 2 tag inside
        - head
        - body
    - attribute mandatory is lang
- head
    - In have have data call meta data
    - charset 
        - is type of charactor
    - style 
        - style of page about color, background-color
- body 
    - content in your pages
    - h1
        - header
    - p 
        - paragraph
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
- head
    - meta
        - data in head tag
    - title
        - content that would like to show in top tab
    - link
        - link content out file to show in file
        - rel
            - rel is descript what you link
            - icon 
                - icon that would like to show in top tab
            - stylesheet 
                - style that would like to show in body
---



# Reference
[HTML Full Course for Beginners By Dave Gray](https://www.youtube.com/watch?v=mJgBOIoGihA&t=61s)
