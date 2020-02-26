Opencore出现的问题以及处理方案
====
www.cmlnt.com QQ：404535691 mail:admin@cmlnt.com<br>
OC版本|系统版本|简略配置|问题描述<br>
----

* OC5.6|15.3|X299 R6A| 第三方USB3.1芯片占用系统XHCI路径导致PCH南桥XHCI丢失
----
    * 首先尝试禁用ASMUSB进入系统生效PCH USB全部返回正常使用
    * 尝试修改SSDT-XHCX待测试
