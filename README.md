### 安装 Sublime Text 3 自定制文件

1. 在新系统上 sublime 3 安装好之后

```console
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/
git clone git@github.com:logchi/sublime_customization.git
mv sublime_customization/* .
rm -rf sublime_customization
```

2. 到 https://packagecontrol.io/installation 安装 packagecontrol 。这样所有的包会自动安装上。
