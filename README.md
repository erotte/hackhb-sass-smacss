# MM_REVEAL

HTML is great, but after lots of projects with haml or slim I really don't want to write HTML manually.

This is just a simple middleman project with the reveal.js skeleton.

If you just want to watch the slides, check the files located in the `build/` folder.
There is also a PDF version in the `pdf` folder.
 

You will find the middleman template files in the source/ folder.
The outer layout is just a copy from the initial reveal.js index.html template 
with a <%= yield %> to render the slides sections.


## Attention

Take care of the asset files and folders in source/!  