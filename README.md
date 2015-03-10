# HTML 101

## Before You Begin
Install an Interactive Development Environment (IDE) editor, such as [Atom](https://atom.io) or [Sublime Text](http://www.sublimetext.com). These are some of the most popular choices, but there are many different options available.

## Getting Started
Once you have installed an IDE editor, create an **index.html** file as the starting point for the directory.

### Document Type
A document type must be declared at the start of your index.html file. By declaring the document type you are telling the internet web browser to recognize the file as Hyper Text Markup Language, otherwise known as HTML.

```html
<!doctype html>
```

### HTML Tag
Add an HTML tag below the document type. The HTML element wraps all of the Hyper Text Markup Language code embedded within it. End the HTML element by inserting a forward slash as shown below.

```html
<!doctype html>
<html>
</html>
```

### Set the Language
Within the HTML tag we can declare the document's language by adding a language attribute to the HTML tag. This is primarily to assist search engines and internet web browsers with identifying the language that the document is in. We have declared that the embedded HTML in this file will be in English (en).

```html
<!doctype html>
<html lang="en">
</html>
```
### Head tag
The Head element provides information about the document. This element can contain the title of the document, meta information, scripts and style.

```html
<!doctype html>
<html lang="en">
<head>
</head>
</html>
```
The following tags can go within the head tag:
+ `<base>`
+ `<link>`
+ `<meta>`
+ `<noscript>`
+ `<script>`
+ `<style>`
+ `<title>`


### Meta Tag
Metadata is data that describes other data. The Meta tag provides the metadata of the document. The Meta tag can tell the browser how to display content, provide key words for search engines.

### Set the character encoding
We set the character encoding within the meta tag. In this example we will set the character encoding to [Unicode](http://unicode.org).

```html
<!doctype html>
<html lang ="en">
<head>
<meta charset="utf-8">
</head>
</html>
```
