# Single Page Portfolio

## Step 06:

### Full Screen Pages

In the previous step, I added links that depend on scrolling content into
view. On pages with tons of content and internal anchors to sections, this
is easy to observe.

Our page has only very small areas of content and most likely displays on
your screen with plenty of room to spare, as indicated by the red
background color. 

With one line of CSS, we can trick the browser into displaying each of
these "pages" at the full height of the window, regardless of the content
size. 

To the `section` selector, add this:

`height: 100vh;`


Depending on which links you may have clicked prior to reloading the page,
you may not see what you expect. Scroll to the top of the page, and you
should see the navigation bar at the very top. If you click a link, your
entire screen will be filled with one of the HTML `<section>` elements,
each with a different background.



