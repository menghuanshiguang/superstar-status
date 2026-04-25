# SuperStar Status

该仓库用于 SuperStar Android 应用的远程状态控制。

## 文件说明

- `status.txt` - 状态文件，内容为 `1` 或 `0`
  - `1` = 允许使用
  - `0` = 禁止使用

## 使用方式

应用启动时通过以下 URL 读取该文件：
```
https://raw.githubusercontent.com/menghuanshiguang/superstar-status/main/status.txt
```
