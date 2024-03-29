# <center>WechatMoments</center>

# 微信朋友圈导出工具

# 一、项目介绍

## 1. 项目简介

* [WechatMoments](https://github.com/tech-shrimp/WechatMoments)是一款运行在Windows上的，备份导出朋友圈为html的工具
* 作者：[技术爬爬虾](https://space.bilibili.com/316183842)（B站 抖音 Youtube同名）更多有趣实用项目请关注
* 开源许可: Apache License
* 分发，宣传，二次开发等请注明原作者

## 2. 使用说明

* (1) 安装[Windows版微信](https://pc.weixin.qq.com/)，并且登陆
* (2) 在[Releases](https://github.com/tech-shrimp/WechatMoments/releases)下载压缩包wechat_moments.zip 
* (3) 解压文件夹（路径不要包含中文）
* (4) 管理员身份运行wechat_moments.exe，并按提示操作
* (5) 如发生异常，重启微信，重启软件

# 二. 详细介绍

## 1. 核心功能

* 导出微信朋友圈数据为HTML
* 可以下载图片/视频离线查看，永久保存
* 可以根据联系人，朋友圈时间进行过滤导出
* 强依赖微信Windows客户端，只提供windows版本
* 只测试过python3.11+Win10/Win11，其他环境随缘
<br>
![主界面.png](/doc/pic/主界面.png)

## 2. 已知问题

* 视频下载不稳定（如有解决方案欢迎PR）
* HTML页面比较原始
* 音乐等朋友圈格式不支持
* 自动浏览朋友圈的功能不稳定（如有解决方案欢迎PR）


## 3. 常见问题与解决方法
问：为什么导出的数据不全？
- 答：软件只能导出在电脑微信**浏览过**的朋友圈记录，未浏览过的无法导出。

问：怎么在电脑微信浏览朋友圈？
- 答：软件提供了两种自动浏览朋友圈的方法，第一种浏览全部，缺点是最多只能刷到前100天。第二种浏览单个朋友，没有时间限制。

问：自动浏览单个朋友圈功能失效！
 - 答：可以手动操作，也可以替换图片提高成功率，详见文档[电脑微信浏览朋友圈](/doc/manual_guide.md)<br/>
  
问：为什么视频没法播放？
- 答：请使用Chrome浏览器打开html文件。或者勾选视频转码，获得更多浏览器的兼容性。

问：能不能导出聊天记录？
- 答：导出聊天记录请使用这个软件[https://github.com/LC044/WeChatMsg](https://github.com/LC044/WeChatMsg)


## 4. 更新计划

*  导出点赞，评论等
*  HTML网页功能增强，过滤排序等功能
*  支持更多的朋友圈格式（音乐分享等）
*  其他导出格式（Word, PDF等）
*  佛系开发 随缘更新

## 5. 问题反馈

*  请直接提issue，或发送邮箱techshrimp@163.com
*  请附上日志与软件截图，日志地址log\xxxx-xx-xx-output.log

## 6. 二次开发

*  Python环境: Python3.11
*  安装依赖: pip install requirements.txt
*  启动: python main.py
*  编译为可执行文件: 使用Github Action(.github/workflows/main.yml)
*  微信数据库解密见项目:[https://github.com/xaoyaoo/PyWxDump](https://github.com/xaoyaoo/PyWxDump)


# 三、免责声明

### 1. 使用目的

* 本项目仅供学习交流使用，本项目无收费项目，不用于盈利，**请勿用于非法用途**，否则后果自负。
* 本项目只能导出**自己有权查看**的朋友圈数据，无其他越权功能。
* 用户理解并同意，任何违反法律法规、侵犯他人合法权益的行为，均与本项目及其开发者无关，后果由用户自行承担。
* 禁止利用本项目的相关技术从事非法测试或渗透，禁止利用本项目的相关代码或相关技术从事任何非法工作

### 2. 使用期限

* 您应该在下载保存，编译使用本项目的24小时内，删除本项目的源代码和（编译出的）程序；超出此期限的任何使用行为，一概与本项目及其开发者无关。

### 3. 操作规范

* 本项目仅允许在授权情况下对朋友圈进行备份与查看，严禁用于非法目的，否则自行承担所有相关责任；用户如因违反此规定而引发的任何法律责任，将由用户自行承担，与本项目及其开发者无关。
* 严禁用于窃取他人隐私，否则自行承担所有相关责任。

### 4. 免责声明接受

* 下载、保存、进一步浏览源代码或者下载安装、编译使用本程序，表示你同意本警告，并承诺遵守它;

# 四、致谢

* PC微信工具:[https://github.com/xaoyaoo/PyWxDump](https://github.com/xaoyaoo/PyWxDump)
* 留痕（聊天导出工具）:[https://github.com/LC044/WeChatMsg](https://github.com/LC044/WeChatMsg)

# 五、捐赠

如有帮助，请帮忙给B站视频点赞充电
[技术爬爬虾](https://space.bilibili.com/316183842)