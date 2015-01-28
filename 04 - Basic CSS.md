Basic CSS
=========

There are three ways in which you can add CSS (Cascading Style Sheets) to an HTML document so that you can control the apperance of your web pages:

* Add it directly to a tag:
```
<body style='background-color: rebeccapurple;'>
```
* Add a style sheet in the head section your document:
```
<style>
  body {
    background-color: rebeccapurple;
    color: white;
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
  }
  h1 { color: white; font-weight: bold; }
</style>
```
* Link to an external style sheet:
```
<link rel="stylesheet" type="text/css" href="theme.css">
```
