# Single Page Portfolio

A simple one-page, JavaScript-free portfolio style website example.

### Notes:

By custom, the default file displayed by a web browser for any directory is
named `index.html`, so we stick with that convention.

This file is named `README.md`, and uses a format called Markdown to render text
that can easily be converted to HTML. It is standard for folders of software
("repositories" or "repos") in GitHub to have these files to explain various
things about the project. 

In this case, this file will be different for each **branch** in this repo with
updated information on the steps performed.


## Step 02: 

### Add the standard HTML structure:

First is the `<!doctype>` to state what type of document the browser should
expect; this signals an HTML5 document, and the browser modifies how strictly it
parses the HTML based on this.

Next come the opening and closing `<html>` tags surround ***everything else in
the document***. The opening tag includes an _attribute_ named `lang` which
indicates that this is in the United States version of English.

The opening and closing `<head>` tags come first inside of the `<html>` tags. 

The `<head>` hold the metadata, or the information *about* the page. Elements
here are not visible in the browser window, but *can* be seen in the places like
the title or tab bar.

- the `<title>` is required for a page to be valid
- the two `<meta>` tags are types of catch-alls for any other meta-information
  you'd like to include in a page for behind-the-scenes uses 
  - the `charset` attribute states that this document uses the `utf-8` set of
    characters, which includes basically every known glyph on earth - the
    `viewport` attribute is important for responsive and mobile design - it
    tells the browser to scale everything to default values based on the size of
    the user's device
- finally, the `<link>` element ties another document to this one; it uses two
  attributes:
  - "rel" to establish the *relation* between the documents; in this case it
    indicates that the linked file acts as a stylesheet
  - "href" to define the HTML style link to actual CSS file


After the close of the `<head>` tags comes the opening and closing `<body>`
tags. The body is where the rest of your HTML is going to go; things inside the
`<body>` and `</body>` tags are what is visible inside of the browser window.


### Validation:

HTML is an official specification, meaning it is either correct ('valid') or
not. It is always a good idea to write valid HTML, as it can be hard enough get
things looking correct using CSS even with perfectly valid HTML; without it can
be impossible.

You can check the validation of any HTML document by uploading, linking, or
copying and pasting into the [W3C HTML Validator](https://validator.w3.org/).
