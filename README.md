# python项目开发目录模板


## 目录简介
- docs 文档目录，项目配置文件通常也放在这里，
- extras 有时候会使用到外部库，如 C/C++ 库，一般放在这个文件夹里
- scripts 存放脚本文件，比如代码仓库不适合存放很大的二进制文件，这时候可以写个脚本去拉取
- yolov3xmlgenerator 是项目源码文件夹，一般用小写项目名称，入口文件建议命名为main.py，再配上 __init__.py 文件，另外，单元测试的代码也放在这块
- README.md 项目介绍，一般包括使用的环境，安装的方法，软件的基本原理、测试数据及常见问题等，越详细越好 ，
- requirements.txt 记录依赖的软件包及对应的版本号，方便读者明确项目使用了哪些 Python包，可以使用命令安装所有的依赖包 pip install -r requirements.txt，另外，可以使用 pipreqs 这个工具来生成 requirements.txt，
- setup.py， 安装、部署、打包的脚本。

---
## 开源方面需要
- LICENSE 协议文件
- ChangeLog.txt 记录版本发布的 release note（可选）
- .gitignore 如果使用的是 git 代码管理工具，表明上传时忽略的文件，如果您使用的是 svn，请忽略
