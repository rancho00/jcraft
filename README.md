# jcraft-guide
jcraft是SSH2的一个纯Java实现。它允许你连接到一个sshd 服务器，使用端口转发，X11转发，文件传输等等。
这里只介绍端口转发，因为在我们开发环境中，很多服务器是不对外暴露的，都要通过跳转机跳转，这样使我们开发人员开发很不方便，为了在本地开发，这里我们通过jcraft的转口转发功能来实现我们在本地机器上连接内网服务器进行开发


# 使用
# 导入maven包 
![Image text](https://raw.githubusercontent.com/rancho00/jcraft-guide/master/images/TIM%E5%9B%BE%E7%89%8720181227144235.png)
