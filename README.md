# Tor-s-meek-google
Running meek-google without TBB
使用方法：首先本提取版meek-google需要用到谷歌的Host也就是谷歌的可用IP才能运行，这一点与去阿根廷原理一样，所以本人推荐Gogo tester：https://github.com/azzvx/gogotester/releases 作为获取可用谷歌IP的软件。获取到谷歌IP后按照网上方法填入Host,此处仅作示范：
用记事本打开C:\Windows\System32\drivers\etc\hosts 在下面填入“208.117.245.152（或者其他你用Gogo tester测试能用的IP） plus.google.com” 
填完后保存，运行本软件中的tor-run.bat启动meek-google提取版，将浏览器代理设置为socks5 127.0.0.1:9050 进行使用即可，当想退出本软件时，运行tor-stop.bat即可
