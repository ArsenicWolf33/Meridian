

Tag used: <a>

```<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>```

The `target` attribute specifies where to open the linked document.

The `target` attribute can have one of the following values:

-   `_self` - Default. Opens the document in the same window/tab as it was clicked
-   `_blank` - Opens the document in a new window or tab
-   `_parent` - Opens the document in the parent frame
-   `_top` - Opens the document in the full body of the window


#### To use an image as a link, just put the `<img>` tag inside the `<a>` tag:

```
<a href="default.asp">  
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">  
</a>
```

### For changing link colors and stuff
``` css
<style>  
a:link {  color: green;  
  background-color: transparent;  
  text-decoration: none;}  
  
a:visited {  color: pink;  
  background-color: transparent;  
  text-decoration: none;}  
  
a:hover {  color: red;  
  background-color: transparent;  
  text-decoration: underline;}  
  
a:active {  color: yellow;  
  background-color: transparent;  
  text-decoration: underline;}  
</style>

```

# Links within the same page
Bookmarks can be useful if a web page is very long.

To create a bookmark - first create the bookmark, then add a link to it.

When the link is clicked, the page will scroll down or up to the location with the bookmark.

``` html
<h2 id="C4">Chapter 4</h2
<a href="#C4">Jump to Chapter 4</a>
<a href="html_demo.html#C4">Jump to Chapter 4</a>
```
