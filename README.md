#!name=大灰狼書源（可切換）
#!desc=大灰狼聚合書源專用策略組，可手動切換節點
#!author=Custom
#!icon=https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Book.png

[Proxy Group]
大灰狼 = select,HK,TW,SG,JP,KR,US,DIRECT,img-url = https://raw.githubusercontent.com/Koolson/Qure/master/IconSet/Color/Book.png

[Rule]
# 大灰狼主要域名
DOMAIN-SUFFIX,langge.cf,大灰狼
DOMAIN-SUFFIX,langge.tk,大灰狼
DOMAIN-SUFFIX,doubi.tk,大灰狼
DOMAIN-SUFFIX,czyl.cf,大灰狼
DOMAIN-SUFFIX,dashabi.tk,大灰狼
DOMAIN-SUFFIX,dahuilang.cf,大灰狼
DOMAIN-KEYWORD,langge,大灰狼
DOMAIN-KEYWORD,czyl,大灰狼
DOMAIN-KEYWORD,dahuilang,大灰狼

# 常見後備 IP
IP-CIDR,219.154.201.122/32,大灰狼,no-resolve
