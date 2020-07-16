# vscode-remote-python

针对国内网络预先完成apt下载、pip源的修改

本项目中的[Dockerfile](https://github.com/microsoft/vscode-remote-try-python/blob/master/.devcontainer/Dockerfile)由[微软范例python开发容器](https://github.com/Microsoft/vscode-remote-try-python)中提取后修改

相较于原本的Dockerfile，做了如下修改

- 通过apt多安装了zsh less locales git-flow vim这5个组件
- 安装了oh-my-zsh
- 生成了中文locale支持，在终端中中文的输入与输出都不会乱码了
- 时区设置为+0800
- ENV Shell设置为zsh
