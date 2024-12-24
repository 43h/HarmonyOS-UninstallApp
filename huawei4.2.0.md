# HarmonyOS4.2.0
---
更新于 2024-12-23

## 测试设备
* 荣耀30 pro

## ADB命令
```shell
adb.exe shell
## 查看用户
pm list users
## 查看系统包
HWEBG:/ $ pm list package -s
## 查看用户包
pm list packages -3 
## 查看包信息
pm dump <包名>
pm uninstall --user 0 package
```

## 默认系统APP列表
### 可卸载应用
* 壁纸与主题
> ~~com.huawei.magazine~~ - 华为杂志  
> ~~com.huawei.android.thememanager - 华为主题管理~~  
> ~~com.huawei.aod~~ - AOD（Always On Display）熄屏显示  
> ~~com.android.wallpaperbackup~~ - 壁纸备份  
> ~~com.huawei.livewallpaper.paradise~~ - 华为动态壁纸（天堂）  
> ~~com.android.wallpaper.livepicker~~ - 壁纸选择器  
* AI
> ~~com.huawei.search~~ - 智慧搜索  
> ~~com.huawei.suggestion~~ - 小艺建议 
> ~~com.huawei.arengine.service~~ - AR引擎服务  
* 游戏
> ~~com.huawei.gameassistant~~ - 游戏助手  
* 云
> ~~com.huawei.hicloud~~ - 华为云服务  
* 钱包
> ~~com.huawei.wallet~~ - 华为钱包  
> ~~com.huawei.wallet.sdk.walletsdk~~ - 华为钱包SDK  
> ~~com.huawei.hwpanpayservice~~ - 华为HuaweiPay支付服务  
> ~~com.huawei.wallet.facard~~ - 华为钱包卡片服务  
> ~~com.huawei.trustcircle~~ - 信任圈  
* 音乐
> ~~com.huawei.music~~ - 华为音乐 
* 浏览器
> ~~com.huawei.browser~~ - 华为浏览器  
> ~~com.huawei.browser.fa~~ - 华为浏览器功能增强  
* 视频
> ~~com.huawei.himovie~~ - 华为视频  
> ~~com.sohu.sohuvideo.emplayer~~ - 搜狐视频播放器  
> ~~com.huawei.himovie.partner1~~ - 华为电影合作伙伴1  
> ~~com.huawei.himovie.partner2~~ - 华为电影合作伙伴2  
> ~~com.tencent.qqlivehuawei~~ - 腾讯QQ视频华为版 
* 输入法 
> ~~com.baidu.input_huawei~~ - 百度输入法华为版  
* 其他应用与系统服务
> ~~com.huawei.hmos.compass~~ - 华为鸿蒙指南针  
> ~~com.huawei.fastapp~~ - 快应用  
> ~~com.huawei.hwvoipservice~~ - 华为畅联  
> ~~com.huawei.android.karaoke~~ - 华为K歌应用  
> ~~com.bjbyhd.screenreader_huawei~~ - 华为屏幕阅读器（由北京百家云开发）  
> ~~com.huawei.easygo~~ - 华为EasyGo  
> ~~com.huawei.ohos.smarthome~~ - 华为鸿蒙智能家居  
> ~~com.huawei.android.UEInfoCheck~~ - 用户体验信息检查  
> ~~com.huawei.android.chr - 华为CHR（客户体验报告）~~  
> ~~com.huawei.intelligent~~ - 华为负一屏  
> ~~com.android.htmlviewer~~ - HTML查看器  
> ~~com.iflytek.speechsuite~~ - iFlytek语音套件  
> ~~com.huawei.rcsserviceapplication~~ - 华为RCS服务  
> ~~com.huawei.skytone~~ - 天际通  
> ~~com.huawei.contentsensor~~ - 屏幕取词  
> ~~com.huawei.android.pushagent~~ - 华为推送代理  
> ~~com.android.ons~~ - ONS服务  
> ~~com.huawei.securitymgr~~ - 华为安全管理
> ~~com.huawei.ohos.health~~ - 鸿蒙健康服务  
> ~~com.huawei.photos~~ - 华为照片 
> ~~com.huawei.android.FloatTasks~~ - 华为浮动任务  
### 不可卸载应用
com.huawei.systemmanager 手机管家 
com.huawei.searchservice - 华为搜索服务  
com.huawei.hiai - 华为AI服务  
com.huawei.android.airsharing 空中共享  
com.huawei.ohos.famanager - 鸿蒙文件管理器  
com.huawei.hiaction - 华为行动  
com.huawei.vassistant - 华为语音助手  
com.huawei.ohos.search - 鸿蒙搜索  
com.huawei.iaware - 华为智能感知  
com.huawei.scanner - 智慧视觉  
com.huawei.hicard - 华为IC卡服务
com.huawei.hidisk - 华为HiDisk（磁盘管理）  
com.huawei.hiview - 华为HiView（云视图服务）  
com.huawei.parentcontrol - 家长控制  



### 不建议卸载应用(并未测试是否可以卸载)
* com.huawei.android.launcher - 华为桌面启动器  
* com.android.permissioncontroller - 权限管理器  
* com.huawei.filemanager - 文件管理器  
* com.huawei.filemanager.fa - 文件管理器（FA） 
* com.huawei.camera - 华为相机  
* com.huawei.onekeylock.hmservice - 华为一键锁屏服务  
* com.android.phone - 电话服务  
* com.huawei.bluetooth - 华为蓝牙  
* com.android.mms.service - 短信服务  
* com.android.bluetooth - 蓝牙服务  
* com.android.mms - 短信管理  
* com.huawei.secime - 华为安全键盘  
* com.huawei.hwdockbar - 华为Dock栏  
### 其他未知
com.huawei.security.hsdr - 华为安全数据恢复  
com.android.cts.priv.ctsshim - CTS Shim（兼容性测试套件）  
com.huawei.camerakit.impl - 华为相机开发包实现  
com.huawei.synergy - 华为协同功能  
com.huawei.hms.dupdateengine - 华为HMS更新引擎  
com.android.providers.telephony - 电信服务提供商  
com.huawei.harmonyos.foundation - 华为鸿蒙OS基础功能  
com.huawei.hwpreview - 华为硬件预览  
com.android.providers.calendar - 日历提供商  
com.huawei.featurelayer.featureframework - 华为功能层框架  
com.huawei.hwddmp - 华为DDMP（设备调试和管理平台）  
com.huawei.ohos.collaborationcenter - 华为鸿蒙协作中心  
com.android.providers.media - 媒体提供商  
com.huawei.android.hsf - 华为HSF（硬件支持框架）  
com.huawei.ohos.soundrecorder - 华为鸿蒙音频录音机  
com.android.wallpapercropper - 壁纸裁剪工具  
com.huawei.nearby - 华为附近服务  
com.huawei.desktop.systemui - 华为桌面系统UI  
com.huawei.motionservice - 华为动作服务  
com.huawei.appmarket - 华为应用市场  
com.huawei.recsys - 华为推荐系统  

com.android.wifi.resources.overlay - Wi-Fi资源覆盖  
com.android.documentsui - 文件管理界面  
com.huawei.numberidentity - 华为号码识别  
com.android.externalstorage - 外部存储服务  
com.huawei.multimedia.audioengine - 音频引擎  
com.android.companiondevicemanager - 配件设备管理器  
com.huawei.regservice - 华为注册服务  
com.huawei.waudio - 华为音频  
com.android.providers.downloads - 下载提供商  
com.android.networkstack.inprocess - 网络堆栈  
com.huawei.hwdiagnosis - 华为硬件诊断  
com.huawei.onehopsvchost - 华为OneHop服务  
com.huawei.phoneservice - 华为电话服务  
com.huawei.desktop.explorer - 华为桌面资源管理器  
com.huawei.screenrecorder - 屏幕录制  

com.huawei.airlink - 华为AirLink（无线连接）  
com.huawei.ohos.inputmethod - 鸿蒙输入法  
com.huawei.iconnect - 华为iConnect  
com.huawei.android.AutoRegSms - 自动短信注册  
com.huawei.dsdscardmanager - 华为DSD卡管理  
com.huawei.hiviewtunnel - HiView隧道  
com.huawei.distributedpasteboard - 分布式剪贴板  
com.android.providers.downloads.ui - 下载UI  
com.android.pacprocessor - PAC处理器  
com.android.systemui.overlay - 系统UI覆盖层  
com.huawei.smartshot - 华为智能截图  
com.android.connectivity.resources - 连接资源  
com.huawei.phoneservice.overlay - 电话服务覆盖层  
androidhwext - 硬件扩展  
com.huawei.pengine - 华为引擎  
com.huawei.contacts - 华为联系人  
com.android.modulemetadata - 模块元数据  
com.android.certinstaller - 证书安装器  
com.huawei.phone.recorder - 电话录音  
com.android.carrierconfig - 运营商配置  
android - 系统基本包  
com.huawei.imedia.sws - 华为媒体处理  
com.huawei.hwid - 华为账户  
com.huawei.msdp - 华为多媒体数据平台  
com.huawei.nemo - 华为NEMO  

com.huawei.systemserver - 系统服务器  

com.android.mtp - MTP协议服务  
com.android.nfc - NFC服务  

com.android.stk - SIM工具包  

com.android.backupconfirm - 备份确认  
com.huawei.android.instantshare - 华为即时分享  

com.huawei.trustagent - 信任代理  
com.huawei.profile - 用户档案  
com.huawei.trustspace - 信任空间  
com.huawei.calendar - 华为日历  
com.huawei.deskclock.overlay - 闹钟覆盖层  
com.huawei.mediacontroller - 媒体控制器  
com.android.statementservice - 账单服务  
com.huawei.printservice - 打印服务  
com.huawei.ohos.hiwindow - 鸿蒙窗口服务  
ohos.media.medialibrary - 媒体库  
com.huawei.devicegroupmanage - 设备分组管理  
com.huawei.android.internal.app - 华为内部应用  
com.huawei.dmsdp - 华为设备多媒体平台  
com.huawei.gateway - 网关服务  
com.huawei.hicar - 华为HiCar（车联网）  
com.huawei.hwasm - 华为HWASM（硬件加速）  
com.huawei.wifiprobqeservice - 华为Wi-Fi问题诊断服务  
com.huawei.soundrecorder - 华为录音机  
com.huawei.onehopsvcclient - 华为OneHop客户端服务  
com.huawei.remotepassword - 华为远程密码管理  
com.android.providers.settings - 设置提供商  
com.android.sharedstoragebackup - 共享存储备份  
com.android.printspooler - 打印任务调度器  
com.huawei.hmos.himovie.fa - 华为鸿蒙HiMovie功能增强  
com.android.frameworkres.overlay - 系统框架资源覆盖  
com.huawei.featurelayer.sharedfeature.map - 华为共享地图功能  
com.android.incallui - 来电界面  
com.huawei.systemmanager - 华为系统管理器  
com.huawei.nb.service - 华为网络服务  
com.android.se - SE（安全元素）  
com.android.inputdevices - 输入设备管理  
com.huawei.securityserver - 华为安全服务器  
com.huawei.controlcenter - 华为控制中心  
com.huawei.ohos.videoeditor - 华为鸿蒙视频编辑器  
com.huawei.privatespace - 华为私人空间  
com.huawei.hilink.framework - 华为HiLink框架  
com.android.cellbroadcastreceiver - 小区广播接收器  
android.ext.shared - Android扩展共享  
com.huawei.HwMultiScreenShot - 华为多屏截图  
com.android.server.telecom - 电信服务  

com.android.cellbroadcastservice - 小区广播服务  
com.huawei.multimedia.hivideoplayengine - 华为视频播放引擎  
com.android.keychain - 密钥链  
com.android.printservice.recommendation - 打印推荐服务  
com.huawei.languagedownloader - 语言下载器  
android.ext.services - Android扩展服务  
com.android.wifi.resources - Wi-Fi资源  
com.huawei.hwstartupguide - 华为启动指南  
com.android.calllogbackup - 通话记录备份  
com.huawei.ohos.security.privacycenter - 华为鸿蒙安全隐私中心  
com.huawei.fido.uafclient - 华为FIDO认证客户端  
com.android.packageinstaller - 包安装器  
com.huawei.bonevoiceui - 华为骨声纹UI  
com.android.proxyhandler - 代理处理器  
com.android.managedprovisioning - 企业配置管理  
com.huawei.hitouch - 华为触控功能  
com.huawei.ohos.suggestion.hm.overlay - 华为鸿蒙建议功能覆盖层  
com.huawei.coauthservice - 华为联合认证服务  
com.huawei.securitypluginbase - 安全插件基础  
com.huawei.android.hwaps - 华为APS（应用性能管理）  
com.huawei.android.hwouc - 华为OUC（开放云平台）  
com.huawei.android.wfdft - 华为WFDFT（无线显示）  
com.huawei.himovie.local - 华为HiMovie本地服务  
com.huawei.ohos.mms - 华为鸿蒙信息服务  
com.huawei.mmitest - 华为MMI测试  
com.android.apps.tag - NFC标签应用  
com.huawei.powergenie - 华为电池管理（Power Genie）  
com.huawei.behaviorauth - 华为行为认证  
com.huawei.webview - 华为WebView  
com.huawei.devicemanager - 设备管理器  
com.huawei.ohos.suggestion - 鸿蒙系统建议服务  
com.huawei.iconnect.ui - iConnect用户界面  
com.huawei.android.instantonline - 即时在线服务  
com.android.settings - 系统设置  
com.android.networkstack.tethering.inprocess - 网络堆栈中的共享服务  
com.android.networkstack.permissionconfig - 网络堆栈权限配置  
com.huawei.ohos.camera - 华为鸿蒙相机  
com.huawei.deviceauth - 设备认证  
com.huawei.pcassistant - 华为PC助手  
com.huawei.android.projectmenu - 华为项目菜单  
com.android.cts.ctsshim - CTS Shim（兼容性测试）  
com.huawei.android.remotecontroller - 华为远程控制  
com.huawei.hidisk.fa - HiDisk（FA）  
com.android.vpndialogs - VPN对话框  
com.huawei.security.privacycenter - 华为隐私中心  
com.huawei.android.hwupgradeguide - 华为升级指南  
com.huawei.ohos.mirror - 鸿蒙镜像服务  
com.android.shell - 系统Shell  
com.android.providers.blockednumber - 屏蔽号码提供商  
com.android.providers.userdictionary - 用户词典提供商  
com.android.providers.media.module - 媒体模块提供商  
com.android.emergency - 紧急服务  
com.huawei.ohos.photos - 华为鸿蒙照片  
com.huawei.distributed.kms - 分布式密钥管理系统  
com.android.hotspot2.osulogin - 热点登录  
com.android.internal.systemui.navbar.gestural - 系统UI导航手势  
com.huawei.music.local - 本地音乐  
com.android.location.fused - 位置服务（融合）  
com.android.systemui - 系统UI  
com.android.bluetoothmidiservice - 蓝牙MIDI服务  
com.huawei.assetsync - 华为资源同步  
com.huawei.hwdetectrepair - 华为硬件检测与修复  
com.huawei.ca - 华为认证  
com.huawei.assetsyncservice - 华为资源同步服务  
com.huawei.ohos.suggestion.overlay - 鸿蒙建议覆盖层  
com.huawei.def - 系统默认功能  
com.huawei.hbm - 华为HBM（硬件行为管理）  
com.huawei.hff - 华为HFF（硬件功能框架）  
com.huawei.ims - IMS（IP多媒体子系统）  
com.huawei.lbs - LBS（位置服务）  
com.android.providers.contacts - 联系人提供商  
com.android.captiveportallogin - 捕获门户登录  
com.huawei.audioaccessorymanager - 音频配件管理器  
com.huawei.trustedthingsauth - 信任物联网认证  
com.huawei.deskclock - 华为桌面时钟  