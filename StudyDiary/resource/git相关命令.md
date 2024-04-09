# git相关命令

参考网址：<https://zhuanlan.zhihu.com/p/118562819>  
参考网址：<https://zhuanlan.zhihu.com/p/38776323>

1. 下载git : sudo apt install git
2. 配置git :  
git config --global user.name "###"  
git config --global user.email "###"  
3. github新建仓库
4. 将github仓库和主机相连
   1. 本机创建ssh，命令行执行

        ```sh
        ssh-keygen -t ed25519 -C "###"
        ```

   2. 将本机创建的ssh添加到github上
   3. 按照主页提示执行。
