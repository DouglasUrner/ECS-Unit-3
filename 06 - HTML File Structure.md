HTML File Structure
===================

Or, steal this file

Stealing, or perhaps more politely, reusing, code is a time honored and valuable tradition is CS. When you reuse code you save yourself both the time to type in the code, but more importantly you save the time to design and debug the code. Reuse of code also encourages you to think about consistancy and creating reusuable code – all good habits for a software developer.

Below is the skeleton of a well-written HTML document. You don't have to use it exactly, but you should use something close to it and you should be familiar with the parts. In the assessment interview at the end of the unit we'll be looking at your code and you will be expected to be able to explain what is going on in the HTML that you've written.

Semantic Tags
-------------

HTML tags give your docments their structure. They also provide valuable information to search engines – and readers of the code – about the purpose and importance of different sections of the document. HTML 5 introduces what are called "semantic tags" that identify specific common parts of a document. The <a href='http://www.w3schools.com/tags/tag_header.asp'>```<header>```</a> (not to be confused with ```<head>```) and ```<nav>``` tags are examples. The links take you to the W3 Schools descriptions of these tags.

Skeletons in the Closet
-----------------------

```
<!doctype html>
<html>
  <title>Skeleton</title>
  
  <link href='' rel='stylesheet' type='text/css'></link>
  <meta charset='utf-8'>
<head>
</head>

<body>
  <header>
    <img id='logo' src='' alt=''>
    <h1></h1>
    <nav>
      <ul>
        <li>Home</li>
        <li>Thing 1</li>
        <li>Thing 2</li>
      </ul>
    </nav>
  </header>
  
  <article>
    <h1>This is the main content of this page</h1>
  </article>
  
  <footer>
    <span id='copyright'>Copyright 2015, Your Name Here</span>
    <nav>
      <ul>
        <li>Contact</li>
        <li>About</li>
      </ul>
    </nav>
  </footer>
</body>
</html>
```
