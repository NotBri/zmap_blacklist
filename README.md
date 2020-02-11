# zmap_blacklist
Anti Abuse &amp; Anti Honey blacklist conf for zmap

# How to Use?

## Dowload:

[https://raw.githubusercontent.com/iBriBri/zmap_blacklist/master/iBlacklist.conf](https://raw.githubusercontent.com/iBriBri/zmap_blacklist/master/iBlacklist.conf)

like 
`wget --no-check-certificate -qO- https://raw.githubusercontent.com/iBriBri/zmap_blacklist/master/iBlacklist.conf`

## For masscan:
`masscan -p 80 0.0.0.0/0 --excludefile iBlacklist.conf -oL result.out`

## For Zmap:
`zmap -p 80 -b iBlacklist.conf -o result.out`

# Thanks For

[https://github.com/Z-0ne/AntiScanIPList](https://github.com/Z-0ne/AntiScanIPList)

[https://github.com/PeralChen/drop_ip](https://github.com/PeralChen/drop_ip)

