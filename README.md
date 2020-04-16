# 01 HTML CSS Git: Code Refactor

Using extisting "index.html" and "style.css" elements I was able to streamline the code for the client, Horiseon. 

Many of the "CSS" elements were redunant, therefore they were condensed. In html, tags were put in the same order. See below for further details. Additionally, a style sheet called "reset" was added. This document will allow the webpage to have standard formatting across all browsers.

HTML CHANGES
<head>
  Added: <meta name="viewport" content="width=device-width, initial-scale=1.0">
  Added: a title to the webpage: <title>Horiseon</title>
  Added: id=“search-engine-optimization” after <div

<body>

  <header>
    Changed <div class=“header> to <header class=“header> </header>
    Changed the <div> below <h1> into <nav></nav> to encapsulate the navigation links
    Changed class=“.seo” to an id

Added<figure></figure> tags around the background image, below the nav bar. added a ‘src’

Added <section> and <article> tags to main content

Added <aside> tag to the <p> under <h3> tags

Added “alt= Image description” to all <img/> tags

Added closing tag to Brand-Awarness <img>

Changed <div class-“footer”> to  <footer class=“footer></footer>


CSS CHANGES
class=“nav” 
  Moved content under header into “.nav” added specific styling for “.nav” “.nav ul” and “.nav li”

class=“content”
  Created “.content h2” rule

class=“benefits”
  Removed individual class tags for each <h3>, <img> and <p>, created 1 class for each tag
  Moved styling notes to above the footer (so mirrored order in the html document) 

