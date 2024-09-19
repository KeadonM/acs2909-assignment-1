## INSERT reset.css functionality

## Background

You've been tasked with creating a simple webpage that includes text, links, photos and some links. Attached is a text file with all the content for the website, and a vidlastly a mockup provided to you as a reference.

Outlined below are the requirements for the website along with some instructions to help you get started.

You will be marked on your file setup, functionality, and implementation.

## Document Setup

1.  Create a project folder called A1
2.  Inside the project folder, create three files called page_about_html.html, page_about_css.html, and A1.css
3.  Inside the project folder, create a folder called images
4.  Download the jpg from the website and store it in your images folder
5.  Both your HTML files must have valid HTML structure including a <head> element with the following:
    1.  A <title> element for each page.
    2.  A character meta tag <meta charset="utf-8" />
    3.  A "reset" CSS file, which is loaded from [this CSS file](https://www.lusciousorange.com/basic_reset.css "this file"). You cannot download and include it, you must load it from where it exists on the Internet.
    4.  A link to your A1.css file.
6.  For all elements, use the default font family and font sizes, unless otherwise specified.
7.  All your styles must exist inside the A1.css stylesheet. You cannot use any inline styles.

## Header

Both pages should have the same header. Use a <div> element with the ID "header". Inside of that include the <h1> with the title and then next to that place the navigation links.

The navigation links (top right) must exist inside of a <ul> with the id "navigation". The links go inside the list items, and they should point to the corresponding pages for the two files you're creating and then the third link points to Google's homepage.

1.  The header must be positioned fixed to the window and never move, even when scrolling.
2.  Use flexbox to position the elements on the page.
3.  The header should have a padding of 20px.
4.  The body element should have a margin of 20px and a padding on top of 60px.
5.  When the mouse is placed over the navigation links the colors should invert to black text and a white background.
6.  Apply padding to the top of the <body> tag to ensure the content starts 20px after the header.

## General styling

1.  The non-header content must be contained in a <div> with the id "content_container". That content must not be allowed to be wider than 600px;
2.  All images must be 50% width with a 20px margin on top.
3.  The two paragraphs of content on each page must be in <p> elements.
4.  The larger text must be in an <h2>.
5.  Any text that is bolded in the preview must also be bolded in your file.
6.  All paragraphs, lists, and headings inside of the content_container must have a padding on the bottom of 20px.
7.  Lists should have a left padding of 40px.

## About HTML page

1.  Use the content from the file to create this page.
2.  The first two items must be a in <p> elements.
3.  You must bold the elements as shown in the preview.
4.  The list of items must be an ordered list and the list items must have a padding on the bottom of 10px.
5.  The link to the logo must point to the online file. Do not download that file.

## About CSS page

1.  Use the content from the file to create this page.
2.  The box model must be created from four divs, which all must share a CSS class called "box_model".
3.  That CSS must set the border to black and 1px thick, with a 5px border radius and padding of 30px except for 10px on the bottom, and 10px of margin on the bottom.
4.  The 4 boxes likely require their own IDs to style individually. The inner box requires 30px of padding on the bottom to override the default 10 from the "box_model".
5.  The backgrounds for the 4 boxes are #FFFFFF, #BBBBBB, #999999, #666666;
6.  Hovering over the inside box must invert the colors.

## Hand-in instructions

Zip all files into a single archive named **StudentNumber_Assignment1.zip**. Submit that zip file via Nexus.
