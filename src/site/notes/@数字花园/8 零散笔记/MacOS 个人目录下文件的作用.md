---
{"dg-publish":true,"dg-path":"8 零散笔记/MacOS 个人目录下文件的作用.md","permalink":"/8 零散笔记/MacOS 个人目录下文件的作用/","created":"2025-07-28","updated":"2025-07-28"}
---


> 经常会产生疑问，索性记录下来备查。

| 文件/目录                 | 作用                             | 删除影响           | 是否自动重建 | 建议操作   |
| --------------------- | ------------------------------ | -------------- | ------ | ------ |
| `.CFUserTextEncoding` | macOS 为当前用户保存「默认文本编码」的隐藏文件     | 无              | 是      | 别管，留着  |
| `.python_history`     | Python REPL（交互式解释器）的「命令历史」     | 丢失 Python 交互历史 | 是      | 想清历史就删 |
| `.vscode`             | VS Code 的「用户级配置目录」             | VS Code 配置全丢   | 是      | 先备份再删  |
| `.zsh_history`        | Z shell（macOS 默认 shell）的「命令历史」 | 丢失 shell 命令历史  | 是      | 想清历史就删 |
| `.zsh_sessions`       | macOS 自带的「恢复终端会话」功能            | 失去终端会话恢复       | 是      | 想清就删   |
