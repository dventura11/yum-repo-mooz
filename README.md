# yum-repo-mooz

A yum repo maintained by [@moozhub](https://github.com/moozhub)

### Repository highlights

* [kodi:krypton](https://github.com/xbmc/xbmc/tree/Krypton)
* [rtorrent:master](https://github.com/rakshasa/rtorrent)
* [kmod-megaraid_sas-07.702.06.00](https://hwraid.le-vert.net/wiki/LSIMegaRAIDSAS) - Latest LSI megaraid_sas kernel module
* [megacli-8.07.14](https://hwraid.le-vert.net/wiki/LSIMegaRAIDSAS#a3.3.megacli) - Latest LSI megacli utility
* [storcli-1.23.02](https://www.thomas-krenn.com/en/wiki/StorCLI) - Latest LSI storcli utility

### Installing

EL7

```
curl -L https://raw.githubusercontent.com/moozhub/yum-repo-mooz/master/elmooz.repo > /etc/yum.repos.d/elmooz.repo
```

### Install packages

```
yum clean all
yum install kodi
```
