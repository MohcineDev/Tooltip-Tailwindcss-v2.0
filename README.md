# Tooltip Tailwindcss v2.0
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
 
 that's why css is not minified and still some unused style tags like (button, input,  sup ...)   
 just to keep the style readable.    
     
      
### Enable variants
enable the possibility to change the display and the visibility of a child element when hovering over a specific parent element 
<pre>
  variants: {
    extend: {},
    display: ['group-hover'],
    visibility : ['group-hover']
  },
</pre>