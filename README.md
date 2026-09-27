#!name=大灰狼書源走PROXY
#!desc=大灰狼聚合書源相關域名走 PROXY 策略
#!author=Custom
#!icon=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Book.png

[Rule]
# 大灰狼主要域名
DOMAIN-SUFFIX,langge.cf,PROXY
DOMAIN-SUFFIX,langge.tk,PROXY
DOMAIN-SUFFIX,doubi.tk,PROXY
DOMAIN-SUFFIX,czyl.cf,PROXY
DOMAIN-SUFFIX,dashabi.tk,PROXY
DOMAIN-SUFFIX,dahuilang.cf,PROXY
DOMAIN-KEYWORD,langge,PROXY
DOMAIN-KEYWORD,czyl,PROXY
DOMAIN-KEYWORD,dahuilang,PROXY

# 塔讀相關
DOMAIN,media3.tadu.com,PROXY
DOMAIN-SUFFIX,tadu.com,PROXY

# 常見後備 IP
IP-CIDR,219.154.201.122/32,PROXY,no-resolve
