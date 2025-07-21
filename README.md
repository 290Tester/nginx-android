# 🚀 Nginx for Android  
> 轻量级、一键启动的 Nginx 服务器，专为 Android 打造。

<<<<<<< HEAD
如何使用？
克隆就是了
记得+x
=======
![GitHub release (latest by date)](https://img.shields.io/github/v/release/290Tester/nginx-android)
![GitHub Repo stars](https://img.shields.io/github/stars/290Tester/nginx-android?style=social)
![GitHub](https://img.shields.io/github/license/290Tester/nginx-android)

## 📦 目录结构
nginx-android/ ├── conf/ # 配置文件 ├── html/ # 默认网页 ├── libs/ # 依赖库 ├── sbin/ # 可执行文件 └── README.md
## 设置环境变量
  ```bash
 export LD_LIBRARY_PATH=nginx/libs:$LD_LIBRARY_PATH
## 启动 Nginx
  ```bash
 ./sbin/nginx
## 完
