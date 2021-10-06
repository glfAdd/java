##### sdkman

- 安装

```bash
$ curl -s https://get.sdkman.io | bash
$ source "/Users/glfadd/.sdkman/bin/sdkman-init.sh"
```

- 命令

```bash
$ sdk selfupdate      升级sdkman
$ sdk list            查看sdkman支持安装的sdk组件
$ sdk list java       可以查看java的可用版本
$ sdk install java 8u272-albba       安装
$ sdk uninstalll candidate    卸载
$ sdk use candidate
$ sdk default candidate


设置默认 java 版本
$ sdk default java 11.0.11-open
```

##### windows

```
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - SDKMAN 多版本管理
windows安装
1. 安装git bash

2. 安装需要的依赖
C:\> choco install unzip
C:\> choco install zip

3. 安装sdkman
curl -s "https://get.sdkman.io" | bash

4. git bash 没有sdkman命令, 在 .bash_profile 文件中添加
export SDKMAN_DIR="/c/Users/glfadd/.sdkman"
[[ -s "/c/Users/glfadd/.sdkman/bin/sdkman-init.sh" ]] && source "/c/Users/glfadd/.sdkman/bin/sdkman-init.sh"

5. 命令
sdk selfupdate      升级sdkman
sdk list            查看sdkman支持安装的sdk组件
sdk list java       可以查看java的可用版本。
sdk install java 7u80       安装
sdk uninstalll candidate    卸载
sdk use candidate
sdk default candidate

sdk install java 8u272-albba


- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - java 安装以后没有jre文件
1. 管理员运行cmd
2. 进入java的目录 D:\Java\jdk-15.0.1
3. 执行命令生成 jre 文件 bin\jlink.exe --module-path jmods --add-modules java.desktop --output jre


AutoCreateDoc.java:8: 错误: 编码GBK的不可映射字符

```

