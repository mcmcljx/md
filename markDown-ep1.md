---
# ⚠️ 注意事项：
* **~数据全清~**：解锁会格式化手机，请提前备份重要数据（微信聊天记录、照片等）。  
* **保修影响**：解锁后可能失去官方保修（部分国家/地区政策不同）。  
* **适用机型**：一加全系（国行/国际版通用，但ColorOS机型需确认OEM解锁选项存在）。  
---
# **🔧** 准备工作 
1. 开启开发者选项
* 进入 **设置 → 关于手机 → 版本信息 **，连续点击**“版本号”**，直到提示**“您已处于开发者模式”**。  
![](https://com.miui.notes/note_image/1a6b686c420527229981c8bfa8a694843952ce3c)
![](https://com.miui.notes/note_image/63dc372bbe84d2c84b28def0d00a94137a2cd778)
* 返回，**设置 → 系统 → 开发者选项**，开启以下两项：  
     OEM解锁（**必须**开启，否则无法解锁BL）。  
     USB调试（用于电脑连接调试）。  
![](https://com.miui.notes/note_image/79884c16ac49df1aa0725a7a4e5c2a76f64c7e43)
![](https://com.miui.notes/note_image/edd3c671b0f4b50d5a1ffd5063dfaac0cee47380)
2. **电脑端工具**
*    下载 ADB和Fastboot工具，~MTK处理器虚同时安装 MTK_USB驱动~
*     安装 **一加USB驱动*（****工具位于图文末链接）*
---
# 🔓 解锁Bootloader
1. 连接电脑，进入Fastboot模式
* 使用~数据~线将手机连接到电脑，此时手机出现弹窗*（如下图）*，勾选 ~传输文件。~
![](https://com.miui.notes/note_image/ee8c630f9e69a0b7313cc2c0bb1cc817b8d1b0e8)
* 并允许使用 USB调试*（下图）*
![](https://com.miui.notes/note_image/d0879871b7793232f4f0344fd1f77beef0377c54)

1. 使用ADB，解锁Bootloader
* 进入Fastboot模式后

