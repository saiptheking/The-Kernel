## The Foundation of the Internet

HTML, standing for Hyper-Text Markup Language, is a coding language that can generate static content in a webpage. Utilizing a structure hierarchy of tags, it allows you to display static text and images on your webpage. HTML is essentially the foundation of the internet, creating the structure that other languages build on.

## Investigation: The Tag Structure

For example, take the HTML code below:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
    <!-- Link to your CSS file -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Your content goes here -->
    <h1>Hello, World!</h1>
    
    <!-- Link to your JavaScript file -->
    <script src="scripts.js"></script>
</body>
</html>
```

Right away, you can see that there are many different tags, such as the `html`, `head`, `body`, and `script` tags. You may have also noticed that tags could be nested in each other, like the `h1` tag being nested into the `body` tag.

## Conclusion

Take a look at the HTML code below. Look at the `p` tag in the code. What tag is it nested under? How do you know? What do you think this tag does? 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Adventures</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Your content goes here -->
    <h1>Hello, World!</h1>
    <p>Welcome to our HTML Adventures!</p>
    <script src="scripts.js"></script>
</body>
</html>
```


> [!Answer]- Answer
> The `p` tag is nested under the `body` tag, nested under the `html` tag. We know this because it is indented from the body tag column. This tag displays standard text as a paragraph.

