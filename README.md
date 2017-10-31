# SSEncrypt.module
SSEncrypt.module for Surge

# 使用方法
单个
```
Proxy = custom, 1.2.3.4, 443, chacha20-ietf-poly1305, password, https://raw.githubusercontent.com/ConnersHua/SSEncrypt/master/SSEncrypt.module, obfs=tls,obfs-host=yunjiasu-cdn.net
```
群组
```
[Proxy]
🇯🇵 JP = custom, 1.2.3.4, 443, chacha20-ietf-poly1305, password, https://raw.githubusercontent.com/ConnersHua/SSEncrypt/master/SSEncrypt.module, obfs=tls,obfs-host=yunjiasu-cdn.net
🇸🇬 SG = custom, 1.2.3.4, 443, chacha20-ietf-poly1305, password, https://raw.githubusercontent.com/ConnersHua/SSEncrypt/master/SSEncrypt.module, obfs=tls,obfs-host=cloudflare.com
🇰🇷 KR = custom, 1.2.3.4, 443, chacha20-ietf-poly1305, password, https://raw.githubusercontent.com/ConnersHua/SSEncrypt/master/SSEncrypt.module
🇺🇸 US= custom, 1.2.3.4, 443, chacha20-ietf-poly1305, password, https://raw.githubusercontent.com/ConnersHua/SSEncrypt/master/SSEncrypt.module

[Proxy Group]
Proxy = select,🕹 Auto,🇯🇵 JP,🇸🇬 SG,🇰🇷 KR,🇺🇸 US
🕹 Auto = url-test,🇯🇵 JP,🇸🇬 SG,🇰🇷 KR,🇺🇸 US,url = http://www.gstatic.com/generate_204
```
