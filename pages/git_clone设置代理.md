---
title: git clone设置代理
---

## 设置代理
## ```
## git config --global http.proxy "socks5://127.0.0.1:10808"
git config --global https.proxy "socks5://127.0.0.1:10808"
## ```
##
## 取消代理
## ```
## git config --global --unset http.proxy
git config --global --unset https.proxy
## ```
##
