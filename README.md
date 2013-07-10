# **Blackbird - Open Source JavaScript Logging Utility**  

A fork of the cool Blackbird logging utility  

#Original README:  
Blackbird - Open Source JavaScript Logging Utility  
Author: G Scott Olson  
Web: http://blackbirdjs.googlecode.com/  
       http://www.gscottolson.com/blackbirdjs/

The MIT License - Copyright (c) 2008 Blackbird Project

Adding Blackbird to your page:

   1. Include blackbird.js in your page.
   2. Inlcude blackbird.css in your page.

Your HTML source should look similar to the following code:

```<html>
<head>
<script type="text/javascript" src="/PATH/TO/blackbird.js"></script>
<link type="text/css" rel="Stylesheet" href="/PATH/TO/blackbird.css" />
...
</head>
...
```

Demos, API, and more at: http://www.gscottolson.com/blackbirdjs/

# review
作者做的这工具做得挺好的，在没有console输出的浏览器上可以进行一些输出语句的调试，还对log信息进行了分类处理，可以只管的查看log结果。
问题还是有的，当在mousemove或者setInterval这样的连续执行的函数中多次执行log输出后，log节点太多使页面压力很大，会导致浏览器变得很慢，这也是无法避免的。