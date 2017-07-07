# CustomGGBook
Personalized layout for GeoGebraBooks


INSTALLATION INSTRUCTIONS

1. Download and unpack your GeoGebraBook from tube.geogebra.org
2. Add mystyle.css and mystyle.js to the folder
3. Add the following two lines to the main HTML file (just before </body>):

    `<link rel="stylesheet" type="text/css" href="mystyle.css" />`
    
    `<script src="mystyle.js"></script>`

4. Customize the general layout in mystyle.css
5. Customize the look of text blocks in mystyle.js
6. Optionally, switch the math typesetting engine to MathJax by adding the following to the main HTML file:


	`<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-MML-AM_CHTML">`
	
	`</script>`
	
	` `
	
	`<script type="text/x-mathjax-config">`
	
	` `
	
	`	MathJax.Hub.Config({`
	
	`		tex2jax: {`
	
	`			inlineMath: [['$','$'], ['\\(','\\)']],`
	
	`			processEscapes: true`
	
	`		},`
	
	` `
	
	`		CommonHTML: {`
	
  	`			scale: 100`
	
  	`		}`
	
	`	});`
	
  	` `
	
	`	MathJax.Hub.Queue(["Typeset",MathJax.Hub]);`
	
	` `
	
	`</script>`
  
     You can now use $ tags in the GeoGebraBook editor instead of the browser math editor.
  
