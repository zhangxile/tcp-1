总结：
IP地址以点分十进制输入；端口号以逗号分隔，端口范围不要太大，输入端口范围（如21,54,85-100）
结果如下：
Python 3.7.0 (v3.7.0: 1bf9cc5093, Jun 27 2018, 04:59:51) [IMSC v.1914 64 bit (AMD64)] on vin32
Type" copyright","credits" or "license()"for more informat ion.
RESTART: C:/Users/Administrator/ppDat a/Local/Programs/Python/Pytho*37/56.py
Input IP :119.75.217.26
Input PORT:78-85
The scan is completel
》》>A total of0open port
RESTART: C:/Users/Administrat or/ AppDat a/Local/Progr ams/PythorVPython37/56. PY
Input IP :192. 168.0.1
Input PORT:78-85
[+] 80 open
>>>1
[*] The scan is complete!
[*] A total of1 open port
总结：客户端通过connect发起连接后，如果服务器处于监听状态就可以发起连接成功，否则说明端口是关闭的。优点是比较简单可靠，缺点是如果连接不成功会频繁的发包，扫描时间比较长 。我对于百度和自己主机进行了78-85端口扫描，通过运行结果可以观察出所监测范围相应端口的开闭状态。
