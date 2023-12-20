# confluence-html-export-viewer
Very basic navbar/iframe solution for viewing confluence html exports.
Provides a confluence-like view with a collapsible/expandable tree of nav links on the left and a draggable page splitter.

## Usage
- put 00_index.html from this repo into the root directory of confluence export (page.html, main-page.html are just for demo)
- from the original index.html of confluence export grab the nav markup i.e. the `<ul>` `<li>` `<a>` element hierarchy
- put the confluence nav markup into the `<aside id="navbar">` element of 00_index.html
- open 00_index.html in browser
