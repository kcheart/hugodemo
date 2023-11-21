+++
title = 'My First Post'
date = 2023-11-21T16:09:23+08:00
draft = false

summary = 'Hugo 系統建置筆記'

+++

# MY IT Note for Hugo

# 7. 安裝 Hugo

Hugo 是使用Go語言編寫的靜態網頁生成器，最大優點是編譯速度極快。
https://gohugo.io/

使用剛安裝好的 Windows Terminal, 指定使用系統管理員權限來安裝
安裝指令：
```shell
choco install hugo-extended -confirm
```

安裝後，查詢 Hugo 版本：
```shell
hugo version
```
如果看到版本號碼，表示安裝成功。
