git init
git add *
git commit -m ''
// 配置本机与 GitHub 连接 用ssh密钥
// 1.生成密钥 ssh-keygen -t rsa -C '921084803@qq.com'
// 创建密钥文件：将生成的密钥写入到文件中

// 2.查看密钥 cat ~/.ssh/id_rsa.pub   xxx.pub 表示密钥文件

// 3.来到GitHub new 一个 ssh 将ssh密钥复制进去 建立电脑与 GitHub 连接

如何将本地仓库 添加到 远程仓库
### 方式一
- 第一步 创建一个远程仓库 创建一个本地仓库
- 第二部 建立本地仓库与远程仓库连接 
    git remote add origin https://github.com/pink18/liyuxin.git
    语法总结  git remote add origin git@server-name:path/repo-name.git
- 第三步 将本地仓库添加到远程仓库 git push -u origin master
    git push 添加
    -u 表示谁添加的
    origin 表示组织
    master 主支

如果说更改需要添加到远程
git add ----> git commit ----> git push

注意：只有第一次 才需要建立 电脑与GitHub 连接
      只有是一个新的仓库 才需要建立 本地仓库与远程仓库的连接

### 方式二
直接使用GitHub 工具直接上传


### GitHub
1.如何使用 GitHub 进行项目的版本管理
2.如何使用 GitHub 自学 找到优秀的开源项目 
3.如何使用 GitHub进行多人合作开发