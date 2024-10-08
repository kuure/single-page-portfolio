# Single Page Portfolio

## Step 04:

### Adding HTML 'Pages'

In order to mimic the idea of "pages" within a single page, I will use
HTML `<section>` elements, which most accurately describe semantically
what these parts of the document represent.

Each section has a unique `id` attribute; there can only be one of any
`id` in a document which allows us to differentiate the three sections,
and the use of the `id` allows us to focus each of these elements
specifically in the window. 



### `<section>` CSS

There is a selector for every `<section>` element, which allows us
to apply the same rules to each of them.

But because each has a unique `id` attribute, each section has been given
a different background color based on CMYK values and using the `hsl`
color format.
