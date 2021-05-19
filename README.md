This is a demo HTML exposition
==============================

This is a demo exposition for the HTML import feature of the RC. The
HTML import feature allows you to directly import a simple static HTML website. 
Any embedded media files will be automatically transcoded to a smaller size. 

Requirements:
-------------

* The root folder needs to contain a file named __index.html__
  this will be the first page displayed when the reader opens the exposition.
* Do not nest folders into folders.
* A common issue is that apastrof's are displayed as the infamous `"â€™"`.
  To avoid, always include `<meta charset="utf-8">` in all your .html files.
  Also make sure, you specify this charset in `<head>` _before anything else_, thus:

    <!DOCTYPE html>
    <head>
        <meta charset="utf-8">
	    <title>Title of exposition</title>
		<link rel="stylesheet" href="styles.css"> 
		etc...
    </head>
    <body>
	
 	
* You can use .html, .css, image, pdf, audio and video files. 
* JavaScript is currently not supported for security reasons, if present, import will fail.
* The character encoding of the .html files should be UTF-8
