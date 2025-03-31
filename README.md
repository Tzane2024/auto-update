1、创建kv空间，命名随意英文数字。<br>
2、复制origin.js的内容。<br>
3、部署一个workers→编辑代码，全选代码，ctrl+v替换代码→部署。<br>
4、设置变量：UUID（随便找一个）、TR_PASS（复杂密码）、PROXY_IP（值设置为cdn-b100.xn--b6gac.eu.org）<br>
5、绑定kv空间，名称（kv），绑定到刚创建的kv空间的名字。<br>
6、绑定域名。<br>
7、访问'域名/panel'，设置登录密码，用密码登录，勾选所有端口→应用→复制订阅地址→粘贴到V2rayN。<br>
<p></p>
若遇全体失效，返回本项目重新操作步骤2、3、，再尝试登录。<br>
本项目的工作流为每天自动获取https://raw.githubusercontent.com/bia-pain-bache/BPB-Worker-Panel/refs/heads/main/build/unobfuscated-worker.js 文件（混淆加密过的），保存到本地的origin.js文件中。<br>
查看：https://github.com/bia-pain-bache/BPB-Worker-Panel/blob/main/build/worker.js<br>
2025.3.31
