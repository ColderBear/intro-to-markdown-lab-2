# How to write an HTML Boilerplate ?

![coding image](https://images.unsplash.com/photo-1515879218367-8466d910aaa4?q=80&w=1469&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

### Creating an HTML boilerplate involves setting up the basic structure of an HTML document. This includes the <!DOCTYPE html> declaration, the html, head, and body elements, and some standard meta tags. Here's a basic HTML boilerplate:

# Explanation on each part

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="styles.css" />
    <!-- Link to your CSS file -->
    <script defer src="script.js"></script>
    <!-- Link to your JavaScript file -->
  </head>
  <body>
    <!-- Your content goes here -->
  </body>
</html>
```

1. **!DOCTYPE html**: This declaration defines the document type and version of HTML. It ensures that the document will be rendered in standards mode.

2. **html lang="en"**: The _html tag_ is the root element of an HTML page. The lang attribute specifies the language of the document.

3. **Parameters**: The _head element_ contains meta-information about the document. This includes the document's title, links to stylesheets, character set declarations, and other meta tags.

4. **meta charset="UTF-8"**: This meta tag specifies the character encoding for the HTML document. UTF-8 is a standard encoding that supports most characters from all languages.

5. **meta name="viewport" content="width=device-width, initial-scale=1.0"**: This meta tag ensures that the webpage is responsive and sets the viewport to match the device's width.

6. **`html <title>Document</title>` **: This meta tag ensures that the webpage is responsive and sets the viewport to match the device's width.

7. **` <link rel="stylesheet" href="styles.css">` **: This link tag is used to include an external CSS file for styling the document.

8. **` <script defer src="script.js"></script>` **: This script tag is used to include an external JavaScript file. The defer attribute ensures that the script is executed after the HTML document has been completely parsed.

9. **` <body>` **: The body element contains the content of the HTML document, which is displayed in the browser.
