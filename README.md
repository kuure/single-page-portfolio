# Single Page Portfolio

## Step 05:

### Navigation HTML

In order to link between pages, you will need to have some sort of
navigation element.

Here I'm using the standard pattern of an html `<nav>` element, with an
unordered list inside of it that contains links to the three URLs defined
by the anchor tags.


### Navigation CSS

I know I'm going to want a horizontal navigation bar, at least at the wide
view, so I've styled it this way using Flexbox for flexibility in the
future. Styling `<nav>` elements can be tricky due to having to apply
rules at different levels - the outer container, the list items, the
actual link tags, and so on. 

Generally speaking it's best spend the most time styling the `<a>` tags,
which are the innermost layer and dictate the clickable area, hover
values, and so on.


### Clicking the Links

The links can be clicked, and they cause the URL to change in the browser,
but they don't really do anything yet because most likely everything is
visible on the screen at the same time. Tags like this internal anchor to
an `id` cause the browser to scroll that element into view; right now the
"pages" are only as tall as their (meager) content so there's nothing to
scroll.
