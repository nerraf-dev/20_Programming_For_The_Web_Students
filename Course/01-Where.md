# Where?
You can include any number of scripts in a HTML document.

Scripts can be placed in the `<head>` or the `<body>` of a page, or in both.

## In the `<head>`
Often the scripts in the `<head` section is often functional. This code is loaded before the document. Here a JavaScript function is placed in the `<head>` section of an HTML page.

The function is invoked (called) when a button is clicked:

```html
    <!DOCTYPE html>
    <html>
    <head>
    <script>
        function demoFunction() {
            document.getElementById("demo").innerHTML = "oooh new text!";
        }
    </script>
    </head>

    <body>
        <h2>Where: JS in Head</h2>

        <p id="demo">A Paragraph of text...</p>
        <button type="button" onclick="demoFunction()">Click Me!</button>
    </body>
    </html>
```

