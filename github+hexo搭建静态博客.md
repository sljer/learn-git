1. npm install -g hexo 
2. npm install
3. hexo generate
4. hexo server
5. 新建仓库：wuyuejianjue.github.io
6. 复制https地址并修改配置文件_config.yml的repository
7. ssh-keygen -t rsa -C "2294373258@qq.com"
8. ssh-agent -s
9. ssh-add ~/.ssh/id_rsa
10. (eval ssh-agent -s
11. ssh-add)
12. clip < ~/.ssh/id_rsa.pub(copy ssh key)
13. 在setting中add key
14. ssh -T git@github.com
15. hexo generate
16. hexo deploy

