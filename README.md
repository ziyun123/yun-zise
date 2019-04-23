# yun-zise
我的第一个NPM模块

# CommonJS标准
我们看到上面代码中使用CommonJS标准。一个单独的文件就是一个模块，模块内将需要对外暴露的变量放到exports对象里，可以是任意对象，函数，数组等，未放到exports对象里的都是私有的。用require方法加载模块，即读取模块文件获得exports对象。这里出现的module，exports，require是JS的新语法吗？不是新语法，只是CommonJS的语法糖。

# 目录结构
bin: 相应的运行文件并生成指令
tests: 测试用例
lib: 功能文件
index.js 主入口
README.md 说明文档

