UglifyJs JavaScript Compiler for Sublime Text 2 简介
========================
------------------------
UglifyJs JavaScript Compiler for Sublime Text 2 是代码编辑器Sublime Text 2的一个 JavaScript 编译插件，能够对  JavaScript 进行压缩，生成用于生产环境的 .min.js 文件。

安装
------------------------
* 方式1
    * 下载并安装NodeJS(nodejs.org), windows 下需要重启
    * 打开 Sublime Text 2 的Packages目录， "Preferences" -> "Browse Packages"
    * 在Packages目录本代码仓库，Git Clone https://github.com/rehorn/sublime-uglifyjs
    * 打开一个.js文件，按F7或Ctrl+b，在同级目录下生成 .min.js 文件
* 方式2
    * 下载并安装NodeJS(nodejs.org), windows 下需要重启
    * 安装 Packages Control 后，将本代码仓库添加到源
        * ctrl+alt+p之后，输入add repository，输入https://github.com/rehorn/sublime-uglifyjs
    * 执行 Packages Control 后，就能搜索到 sublime-uglifyjs ，安装即可
    * 打开一个.js文件，按F7或Ctrl+b，在同级目录下生成 .min.js 文件

使用
------------------------
* 打开一个.js文件，按F7或Ctrl+b，在同级目录下生成 .min.js 文件

自定义
------------------------
* 打开 Sublime Text 2 的Packages目录， "Preferences" -> "Browse Packages"
* 进入 sublime-uglifyjs
* 修改 uglifyjs.sublime-build 文件，可以自定义编译目录，文件名等
* uglify-js.js/lib/bin 等文件升级 uglifyJs 版本

其他
------------------------

