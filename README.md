# 2020-618-TB-miaobi-autojs
2020TB喵币挂机自动获取脚本 ~ 奇怪的项目又增加了

具体说明和不知道怎么下载见https://blog.csdn.net/weixin_44090559/article/details/106461853

最新的的js和app放在主页上了
其他的文件夹里的都是自己测试用的历史版本，每个版本的问题和解决方法尽量有时间再填上
---
2020/6/2

更换主页的3.4.js和1.0.3apk成最新的4.1和1.0.4
区别在于前者在启动时过7秒检测当前应用(if(currentActivity() == "com.taobao.browser.BrowserActivity"){...})
后者每5秒循环检测直到是淘宝为止（while(text("做任务，领喵币").find().empty()){sleep(5000);...}）

---
2020/6/1
增加了历史版本文件夹（留念），每个版本的问题和解决方法尽量有时间再填上

主页的js和app都是最新自测可用的


---
2020/5/31 有点迟了明天把完善的版本提交上

使用前提：
1. 安装淘宝
2. 安装上方地址下的apk：(Chou)

使用教程：
 1. 打开app即可
 
提示：
 1. 目前遇到在主页面的浏览任务不会返回活动页面，需要注意，其他的浏览任务都还OK
 2. 若发现运行不正常按音量上键停止脚本
 3. 这是V1.0版本，目前在我的手机红米K20pro上运行🆗，其他机型。。。应该没差，除了IOS
