# .config

一些通用的配置文件。

## .npmrc

对于 .npmrc 中配置的部分二进制文件，可以前往 https://registry.npmmirror.com/binary.html 查找。

目前已知的一些可配置二进制文件下载地址的变量（在 .npmrc 中建议全大写，使用下划线分隔）：

```bash
# canvas
canvas_binary_host_mirror
sqlite3_binary_host_mirror
selenium_cdnurl
chromedriver_cdnurl
# Puppeteer 20.1 以上的版本
puppeteer_download_host
# Puppeteer 20.1 以下的版本
puppeteer_download_base_url
electron_mirror
phantomjs_cdnurl
```


