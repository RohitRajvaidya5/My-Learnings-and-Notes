# <u>HTML</u> - Hyper Text Markup Language

***

- HTML is consider as a first step to **Frontend Development**.
- HTML is known as language of the web. i.e we can make web pages with the help of html and what is internet if nothing but full of web pages containing data.
- HTML contain so many concepts like element ,tags , content etc.
- **HTML Element** &rarr; HTML element is a combination of Opening Tag , Closing Tag and content present in it. 
   e.g. 
   ```html
    <html> Content or Data </html>
    ```
    In this both `<html>` and `</html>` are opening and closing tag respectively. 
***

## Tools for development :

### 1. VS Code
There are so many code editors in the market which are just great as vs code but the support of extensions in vs code is so much helpful and if you used to all the shortcuts and environment then it is hard to choose another editor.
    
<br>

- Some Extensions which are totally change frontend experience with vs-code.

<br>

**1. Live - Server**

With the help of live server you can view or run your html file in your default browser. Even you can set keyboard shortct for this extension `Ctrl + 2` is works for me because nothing assign to it in default.

<br>

**2. colorize**

<br>

![image](/Notes/HTML/Images/Colorize.png)


**3. Color Themes**

### 2. Mozillla Firefox

***
## Basic HTML programme

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>First HTML Website</title>
</head>
<body>
    
</body>
</html>

```

Above code is basic html **boiler plate** which easily appear if you type `!` in vs code (Visual Studio Code) and press enter.

Some of the concepts regarding above code :

1. `<!DOCTYPE html>` &rarr; It defines the document as HTML document (But this is useful in previous times (when netscape navigator exists) but it just syntax part nothing else.)

2. `<html>` &rarr; This is tag which contains all web page contents.

3. `<head>` &rarr; This tag contain mainly meta data which is useful in SEO (Search Engine Optimization), also it contains `<title>` tag which shows the title of website in tab bar.

4. `<body>` &rarr; This tag all the visual content which will show in web page.

There so much to learn about `meta` tags and SEO but for basics and to run html page I think this info is more than enough.

***

### Most useful HTML tags

1. Header Tag

This tag is as the name states i.e. header which is use to give headings. Also it is not good practice to use header for just to make text bold.

To Make SEO friendly website with header tag :

- `h1` tag is most important
- It states the content title
- Should not be same as `title` tag
- Every page should contain one `h1` tag.
- `h2` and `h3` should be below `h1` as

<br>

```html
<h1>
    <h2>
        <h3>
```
<br>

2. Paragraph Tag

Paragraph tag use for giving descriptions and paragraphs.

<br>

To make SEO friendly website , Paragraph should be meaningful and short but not too short. You can start with topic's main point and explain it in further lines. Also should add sub-topics if the explanation taking too long.

<br>

```html
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facere sit esse fugit, eligendi nisi quam adipisci ab dolor? Consequuntur consequatur harum dolorem itaque cumque! Unde!</p>
```

3. Image Tag

It is use to place images in web pages. `alt` is attribute which is use for alternative text which is appear if image fails to show.

```html
<img src="Path of the image" alt="Alternative Text">
```

4. HTML Lists

List is just group of contents related to something.

<br>

There are two types in HTML Lists :
I. Ordered List 
II. Unordered List

Syntax of both lists respectively :

```html

<!-- I. Ordered List -->

    <ol>
        <li>First</li>
        <li>Second</li>
        <li>Third</li>
    </ol>

    <hr>

    <!-- II Unordered List  -->

    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
```

5. Link Tag

You can link with the help of this tag.

```html
<a href="https://www.google.com">GoTo Google</a>
```