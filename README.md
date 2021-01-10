# Remove due to regulation

## 软件作者已停止更新，如需使用请点击右侧“Releases”或“发布”进行下载。

## Software removal method
First put the .app from the application file to the trash (any way)
Then open the Terminal.app and enter:

```bash
rm -rf /Library/Application\ Support/ShadowsocksX-NG-R8
rm -rf ~/Library/Application\ Support/ShadowsocksX-NG-R8
rm -rf ~/Library/LaunchAgents/com.qiuyuzhou.shadowsocksX-NG.http.plist
rm -rf ~/Library/LaunchAgents/com.qiuyuzhou.shadowsocksX-NG.local.plist
rm -rf ~/.ShadowsocksX-NG
rm -rf ~/Library/Preferences/com.qiuyuzhou.ShadowsocksX-NG.plist
rm -rf ~/Library/Caches/com.qiuyuzhou.ShadowsocksX-NG
```

If the prompt is insufficient, please execute after using sudo


# 使用须知
## 维护本工具是为了帮助更多人的学习与工作，毕竟Google比Baidu更靠谱，因此希望大家注意以下几点

- GFW=智商墙，请注意提高自己的智力，勿被境外利益集团洗脑 

- 墙外≠法外，请注意自己言行，本工具是为了帮助学习而不是让你叛国（[自2020年5月1日起，互联网聊天记录可作为呈堂证供](http://www.npc.gov.cn/npc/c30834/201912/9bce4fdad6734765b316f06279aba6b8.shtml)）

- 爱国富强的前提是自己要有独立思考问题的能力，而不是秀智力

- 请勿在本项目的Issues里进行任何购买梯子或者搭建梯子的讨论

- 本项目所提供编译好的App程序不保证一定可用（特别是macOS 10.15），请各位技术大牛自行下载编译运行，提高使用门槛（在Xcode11.6上可以直接编译运行）
