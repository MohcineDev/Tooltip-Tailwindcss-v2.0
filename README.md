# Tooltip Tailwindcss v2.0
<div align="center">
<img src="./Tailwindcss.svg"  alt="Tailwindcss" width="50%">  
</div>
<br/>
      
Social media buttons Tooltip using Tailwindcss v 2.0 

* this repo created on the very special day when GitHub launched the dark mode

 
### !Note : about the css style

> in the config file i used :
 
<pre>
   purge: {
    enabled: true,
    content: ['./src/**/*.html'],
   },
</pre>   
by default preserveHtmlElements : true    
 
that's why css is not minified and still some unused style tags like (button, input,  sup ...)    
Read more [HERE](https://tailwindcss.com/docs/optimizing-for-production#preserving-html-elements)     
     
      
### Enable variants
enable the possibility to change the display and the visibility of a child element when hovering over a specific parent element 
<pre>
  variants: {
    extend: {},
    display: ['group-hover'],
    visibility : ['group-hover']
  },
</pre>