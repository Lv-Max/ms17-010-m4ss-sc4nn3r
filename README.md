# Ms17-010 永恒之蓝漏洞检测工具
用Python写的Ms17-010多线程检测工具

灵感来自 [smb_ms17_010](https://github.com/rapid7/metasploit-framework/blob/master/modules/auxiliary/scanner/smb/smb_ms17_010.rb ) metasploit-framework auxiliary module  
<pre>

##使用方式: ms17-010-m4ss-sc4nn3r.py ip地址 or ip/CIDR or ip/subnet

   示范: ms17-010-m4ss-sc4nn3r.py 192.168.0.1
            ms17-010-m4ss-sc4nn3r.py 192.168.0.0/24
            ms17-010-m4ss-sc4nn3r.py 192.168.0.0/255.255.255.0

</pre>

## 环境需求:
- Python 2.7
- ipaddress module

## 特点:
<pre>
1) 多线程
2) 子网扫描
3) 无类别域间路由网络扫描
</pre>

## 编译版本
<pre>
1) 不需要Python环境
2) 不需要任何模块
3) 在32位和64位系统上测试通过
</pre>
