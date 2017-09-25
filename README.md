# yum-repo-mooz

A yum repo maintained by [@moozhub](https://github.com/moozhub)

### Repository highlights

* [kodi:krypton](https://github.com/xbmc/xbmc/tree/Krypton)
* [rtorrent:master](https://github.com/rakshasa/rtorrent)
* [kmod-megaraid_sas-07.702.06.00](https://github.com/torvalds/linux/tree/master/drivers/scsi/megaraid) - MegaRAID kernel module as provided by latest LSI RPMs

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
