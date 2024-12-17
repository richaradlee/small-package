
*  常用OpenWrt软件包源码合集，同步上游更新！

*  感谢以上github仓库所有者！

##### 插件下载:

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/kenzok8/compile-package?style=for-the-badge&label=插件更新下载)](https://github.com/kenzok8/compile-package/releases/latest)

#### 使用方式：

```bash
 sed -i '$a src-git smpackage https://github.com/kenzok8/small-package' feeds.conf.default
```
对于强迫症的同学（有报错信息、或Lean源码编译出错的情况），请尝试删除冲突的插件

```bash
rm -rf feeds/smpackage/{base-files,dnsmasq,firewall*,fullconenat,libnftnl,nftables,ppp,opkg,ucl,upx,vsftpd*,miniupnpd-iptables,wireless-regdb}
```











