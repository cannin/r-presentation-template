
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-317478-17', 'auto');
  ga('send', 'pageview');

</script>

<script src='https://ajax.googleapis.com/ajax/libs/jquery/2.2.0/jquery.min.js'></script>
<script>
$(window).bind('load', function() {
  Reveal.addEventListener('slidechanged', function(event) {
    console.log('Slide Index: ' + event.indexh);
    ga('send', 'event', 'Slide Index', 'click', event.indexh);
  });
});
</script>


<div class="guide horz" style="height: 0%; width: 100%; top: 10%; left: 0%"></div>
<div class="guide horz" style="height: 0%; width: 100%; top: 20%; left: 0%"></div>
<div class="guide horz" style="height: 0%; width: 100%; top: 30%; left: 0%"></div>
<div class="guide horz" style="height: 0%; width: 100%; top: 40%; left: 0%"></div>
<div class="middle-guide horz" style="height: 0%; width: 100%; top: 50%; left: 0%"></div>
<div class="guide horz" style="height: 0%; width: 100%; top: 60%; left: 0%"></div>
<div class="guide horz" style="height: 0%; width: 100%; top: 70%; left: 0%"></div>
<div class="guide horz" style="height: 0%; width: 100%; top: 80%; left: 0%"></div>
<div class="guide horz" style="height: 0%; width: 100%; top: 90%; left: 0%"></div>

<div class="guide vert" style="height: 100%; width: 0%; top: 0%; left: 10%"></div>
<div class="guide vert" style="height: 100%; width: 0%; top: 0%; left: 20%"></div>
<div class="guide vert" style="height: 100%; width: 0%; top: 0%; left: 30%"></div>
<div class="guide vert" style="height: 100%; width: 0%; top: 0%; left: 40%"></div>
<div class="middle-guide vert" style="height: 100%; width: 0%; top: 0%; left: 50%"></div>
<div class="guide vert" style="height: 100%; width: 0%; top: 0%; left: 60%"></div>
<div class="guide vert" style="height: 100%; width: 0%; top: 0%; left: 70%"></div>
<div class="guide vert" style="height: 100%; width: 0%; top: 0%; left: 80%"></div>
<div class="guide vert" style="height: 100%; width: 0%; top: 0%; left: 90%"></div>


R Basics
===
author: Augustin Luna
date: 17 July, 2016
width: 960
height: 700
transition: linear
css: rpres.css

<!-- NOTE: Styling and external images may be missing --> 
<p>Research Fellow
  <br/>
  Department of Biostatistics and Computational Biology
  <br/>
  Dana-Farber Cancer Institute
</p>
<div class="footer" style="top: 85%; left:1%"><img src="img/dfci_logo.gif" height="60px" width="330px" /></div>

What is R?
===
* Free, open source
* Started in 1993
* Geared towards scientific computing
 * Created by Ross Ihaka and Robert Gentleman (statisticians)
* Interpreted; similar to Python and MATLAB

First Script: Hello World!
===

* `cat()` prints a simple message in the console


```r
cat("Hello World!")
```

```
Hello World!
```

Running Hello World Script
===
class: center-img

* "Run" button runs current line or selected lines
* "Source" button runs all lines in file

<img src="img/rstudio_helloWorld.png" height="500px" />

<div class="box" style="height: 3%; width: 10%; top: 39.2%; left: 49.5%"></div>

RStudio Overview
===
class: center-img

<img src="img/rstudio.png" height="600px" />

<div class="box" style="height: 10%; width: 20%; top: 40%; left: 25%">
  <span class="filled" style="font-size: 2rem !important">Editor<span>
</div>

<div class="ellipse" style="height: 20%; width: 5%; top: 60%; left: 70%">
</div>

Top 20 Packages (kdnuggets.com)
===
class: smaller

|Package|Downloads|
|---|---|
|Rcpp|693288|
|ggplot2|598484|
|stringr|543434|
|plyr|523220|
|digest|521344|
|reshape2|483065|
|colorspace|476304|
|RColorBrewer|453858|
|manipulate|395232|
|scales|394389|

***

|Package|Downloads|
|---|---|
|labeling|373374|
|proto|369096|
|munsell|368949|
|gtable|364015|
|dichromat|362562|
|mime|352780|
|RCurl|340530|
|bitops|322743|
|zoo|302052|
|knitr|295528|
