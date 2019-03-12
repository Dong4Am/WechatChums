# WechatChums
微信密友，隐藏通讯录好友和群聊

====

### 简介
WechatChums 是一个隐藏通讯录好友的 Xposed 模块。
基于微信巫师(WechatMagician)的代码，适配了微信最新版。
个人需要这个功能，但鉴于巫师很久未更新，所以手动适配，暂时取掉了其它功能。
因为换包名(要发布太极等)，代码修改的有点乱，如果有需要，整理后开源。
最终生成的apk，没有进行混淆，放心使用。

### 版本支持
目前只测试了7.0.3

### 使用教程
有待整理文档到 wiki

### 存在的问题
1. 初次进入时，因为动态适配(个人能力问题，后续再改)，需要同步解析微信apk，大约耗时六七秒左右。

### 特别感谢
1. [WechatMagician](https://github.com/Gh0u1L5/WechatMagician)
2. [WechatSpellbook](https://github.com/Gh0u1L5/WechatSpellbook)
