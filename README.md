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

### HTML Element
Add an HTML element below the document type. The HTML element wraps all of the Hyper Text Markup Language code embedded within it. End the HTML element by inserting a forward slash as shown below.

```html
<!doctype html>
<html>
</html>
```

### Set the Language
Within the HTML element we can declare the document's language by adding a language attribute to the HTML element. This is primarily to assist search engines and internet web browsers with identifying the language that the document is in. We have declared that the embedded HTML in this file will be in English (en).

```html
<!doctype html>
<html lang="en">
</html>
```