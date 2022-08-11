echo "# docker" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/maxl960/docker.git
git push -u origin main

git remote add origin https://github.com/maxl960/docker.git
git branch -M main
git push -u origin main
--------------------------------
### 项目简介
    本项目是用于存储docker相关配置文件。
    dockerfile: 通用项目容器（Nginx, PHP, MySQL）
    dockercompose: 具体项目开发环境搭建