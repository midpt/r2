---
title: Fourth page
layout: default
v1: dog
v2: cat
v3: Fan
v4:Toy
---

# This is Fourth page

[the clickable text](http://xlson.com/)

* Bullet lists are also easy to create
* One more

Using inline html

v1 value:
<p>{{page.v1}}</p>

v2 value
<p>{{page.v2}}</p>


<p>v3 value:{{page.v3}}</p>
 

<p>v4 value:{{page.v4}}</p>




## Trying out Mermaid flowchart using javascript

  <div id="content"></div>


<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
<script>
    var mtxt="";
	mtxt="## Heading 2\n "+
	"1) Mr Sunny Neo SP:Harry Teo\n\n"+
    "&diams;Food delivery(18/06/19)(Serving community)\n"
  
	
    document.getElementById('content').innerHTML =marked(mtxt);
	  
   
	     
</script>



 
Go to [First Page](index.html)


Go to [Second Page](secpg.html)

Go to [Third Page](third.html)

### yyy