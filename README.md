# 8R节点
### 售后邮箱:jc.haggler664@passinbox
### 1、节点不死可永久使用，质保1年售后。
### 2、不限制设备数量/不限制流量/不限制速度/解锁流媒体/解锁奈飞/解锁chatGPT等平台。
--------------------------------
## 傻瓜式使用流程：
#### 1、使用什么设备下载对应的代理软件，下列已电脑v2rayN安卓v2rayNG举例：
#### 2、电脑下载好v2rayN。安卓手机下载好v2rayNG。
#### 3、[购买链接](https://www.idatariver.com/zh-cn/project/8r%E8%8A%82%E7%82%B9-d26a)
#### 4、购买成功会获得一个链接，复制链接。
#### 5、电脑版直接在v2rayN里面 Ctrl+v粘贴---v2rayN里“服务器”下面会多出一个“import-sub”分组点击选中---点击v2rayN上面“订阅分组”选择“更新当前订阅(不通过代理)”----import-sub分组里会多出几条节点----选择任意一条右键----设为活动服务器----自动配置系统代理。可以全选右键选择(测试服务器真链接延迟(多选))
#### 6、安卓手机--复制购买获得的链接----打开v2rayNG---点击+号---从剪切板导入---所有分组后面会多出一个import sub分组----里面会有多条节点---可以点击竖3个点选择“测试当前组配置Tcping”---点击下面灰色类似播放键启动服务即可成功。
#### 7、其他客户端类似操作，不会邮箱联系。
-------------------------------------------------------------
## 使用过程中问题：
#### 1、速度慢怎么解决？速度慢是根据国家与地区与运营商限制，可以切换网络，可以更换IP。 
#### 2、速度慢可以更换IP。使用优选IP。下面也推荐了8R官方不死IP。也可以根据您的具体网络自己优选IP。
-------------------------------------------------------------
## 如何更改IP：
#### 1、电脑端---随便选择一条不好的节点---右键“编辑服务器”----地址(address)里粘贴新IP即可----确定----设为活动服务器----自动配置系统代理。 
#### 2、安卓机---随便选择一条不好的节点---🖊----服务器地址----更改新IP---右上角√----即可。
-------------------------------------------------------------

## 1：优选IP应用

如果你没有天天最高速度或者选择国家的需求，使用默认的8R官方IP或者域名即可，不必更换

推荐好记的懒人专属8R官方IP如下（IP落地地区都为美国，支持13个标准端口切换），称之为"冲在最前的不死IP"

104.16.0.0 

104.17.0.0 

104.18.0.0 

104.19.0.0 

104.20.0.0 

104.21.0.0 

104.22.0.0 

104.24.0.0 

104.25.0.0 

104.26.0.0 

104.27.0.0 

172.66.0.0

172.67.0.0

162.159.0.0

2606:4700:: 需IPV6环境

通过配置变量修改，可使用他人分享的IP或者域名，也可以自行本地优选.

本地电脑端优选项目推荐（可在上面代码区直接下载）：

1、CDN优选域名V23.8.18 (电脑win64)

2、8R优选反代IP (电脑版，带测速)

3、8R优选官方IP (美、亚、欧三地区无交互电脑版！强烈推荐！)

4、8R优选官方IP (电脑版，带测速)

5、在线优选IP：https://stock.hostmonit.com/CloudFlareYes

注意：多个8R节点在客户端使用负载均衡或者自动选择时，建议所有应用的节点都为同一个国家地区，以避免不同国家之间的IP乱跳现象

---------------------------------

## 2：客户端推荐

#### 启用分片(Fragment)功能的好处：无视域名被墙TLS阻断，从而让workers等被墙的域名支持TLS节点
#### 提示：未被墙TLS阻断的自定义域名或pages域名无需开启分片就可使用TLS节点
 
目前支持该功能的平台客户端如下（点击名称即跳转到官方下载地址）

1、安卓Android：[v2rayNG](https://github.com/2dust/v2rayNG/tags)、[Nekobox](https://github.com/starifly/NekoBoxForAndroid/releases)、[Karing](https://github.com/KaringX/karing/tags)、v2box

2、电脑Windows：[v2rayN](https://github.com/2dust/v2rayN/tags)、[Hiddify](https://github.com/hiddify/hiddify-next/tags)、[Karing](https://github.com/KaringX/karing/tags)

3、苹果Ios：Karing、Hiddify Proxy & VPN、Shadowrocket(小火箭)、Streisand、v2box

4、软路由Openwrt：[homeproxy](https://github.com/yonggekkk/homeproxy/releases)，建议使用系统自带的软件库查找更新

注意：其他平台客户端未开启分片功能情况下，workers域的6个443系TLS节点是不可用的

注意：Shadowrocket(小火箭)、v2box、v2rayn、v2rayng客户端对trojan+ws有强制开启TLS问题，造成trojan+ws不通。且clash订阅没有trojan+ws节点。特此说明

---------------------------------

## 优选官方IP+反代IP（在本地网络环境下利用termux或者ish运行）：

1、安卓请使用termux官方项目下载客户端（谷歌商店下载的不可用！）：https://github.com/termux/termux-app/releases/tag/v0.118.1

首次安装后，请先安装依赖：```pkg upgrade```，然后运行以下你要使用的脚本

2、苹果手机用户，由于ISH最新版有BUG导致脚本运行卡住，请使用ISH_1.2.2版本，可以用巨魔先安装再降级，网上也有其它指定旧版IPA安装的教程

首次安装后，请先安装依赖：```apk add curl bash```，然后运行以下你要使用的脚本

-------------------------------------------------------------
### 脚本1：8R-优选官方IP (默认美、亚、欧三地区 强烈推荐！！！)，安卓苹果手机平板专用：
```
curl -sSL https://raw.githubusercontent.com/yonggekkk/Cloudflare_vless_trojan/main/cf/cf.sh -o cf.sh && chmod +x cf.sh && bash cf.sh
```
-------------------------------------------------------------

### 脚本2：8R-CDN优选公共大厂域名脚本，苹果安卓手机平板专用：
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/CFcdnym.sh -o CFcdnym.sh && chmod +x CFcdnym.sh && bash CFcdnym.sh
```
------------------------------------------------------------------------
### 脚本3：8R-优选官方IP+反代IP二合一脚本（带测速），苹果安卓手机平板专用：
```
curl -sSL https://gitlab.com/rwkgyg/CFwarp/raw/main/point/cfip.sh -o cfip.sh && chmod +x cfip.sh && bash cfip.sh
```
-------------------------------------------------------------
