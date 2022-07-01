- 把我们的项目 交给GitHub 托管， 可以直接访问
    1. 这项服务的名字叫 github pages
    2. 免费的二级域名
        纯静态资源

- 相对地址有问题
    工程化vite 配置  将index.html 与 assets 的关系配置成 **"./"**
    github 中可能有好多个项目 / 根路径

- github 中上传了源码
  
- npm i gh-pages 
    专门负责dist 目录的在线访问

- 本地配置远程过程
    git init 
    git add .
    git commit -m ''
    git branch -M main 新建分支
    git remote add origin https://github.com/KECHUXUEZHE/try-react-gh.git 与远程连接
    git push-u origin main 提交到远程 第一次执行报错执行下一步
    git config --global http.seslVerify false 执行后执行上一步