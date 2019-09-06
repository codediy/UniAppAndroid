## 覆盖升级
1. 下载最新版SDK
[SDK下载](https://ask.dcloud.net.cn/docs/#//ask.dcloud.net.cn/article/103)
2. 替换最新版lib
```
lib.5plus.base-release.aar
uniapp-release.aar
```
3. 替换最新版data
```
;app/src/man/assets/data
dcloud_control.xml
dcloud_error.html
dcloud_properties.xml
dcloud1.dat
dcloud2.dat
```
4. 修改appid
```
;app/src/man/assets/data/dcloud_control.xml

<hbuilder version="1.9.9.66861">
<apps>
    <app appid="{appid}" appver=""/>
</apps>
</hbuilder>
```
## UniAppAndrodi打包版本升级
- [SDKv2.1.3](https://github.com/codediy/UniAppAndroid/tree/v2.1)
- [SDKv2.2.1](https://github.com/codediy/UniAppAndroid/tree/master)
