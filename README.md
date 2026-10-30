# 再刷西游 · 更新通道

本仓库只存放游戏内自动更新使用的静态文件，不存放游戏本体。

- `windows/channel.json`、`windows/channel.sig`：电脑版更新器读取的已签名更新通道。
- `windows/zaishuayiba-windows-v0.59.01.zip`：电脑版累计内容更新包（最新；上一版本包保留作回退）。
- `android/channel.json`：手机版游戏内更新读取的通道。
- `android/zaishuayiba-android-v0.59.01.zip`：手机版累计内容更新包（最新；上一版本包保留作回退）。

游戏通过 jsDelivr 读取这些文件（无需登录，公开可下载）：
`https://cdn.jsdelivr.net/gh/luiluu/zaishuayiba-updates@main/...`

更新包只包含游戏内容文件，不含存档；安装前请先在游戏内正常保存。

国内镜像（内容相同）：`https://gitee.com/kyoluu/play-again_-xiyou_-kyo`。
