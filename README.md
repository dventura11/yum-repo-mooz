# yum-repo-mooz

A yum repo maintained by [@moozhub](https://github.com/moozhub)

### Repository highlights

* kodi (stable)
* kmod-megaraid_sas - LSI MegaRAID kernel module (latest)
* rtorrent (git)

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
