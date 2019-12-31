.. README.rst --- 
.. 
.. Description: 
.. Author: Hongyi Wu(吴鸿毅)
.. Email: wuhongyi@qq.com 
.. Created: 五 7月 26 20:21:45 2019 (+0800)
.. Last-Updated: 日 7月 28 22:11:26 2019 (+0800)
..           By: Hongyi Wu(吴鸿毅)
..     Update #: 2
.. URL: http://wuhongyi.cn 

##################################################
README
##################################################

这是仓库模板。

**git - 提交空目录**

需要在目录下创建 .gitkeep 文件，然后在项目的 .gitignore 中设置不忽略 .gitkeep。

.gitkeep 是一个约定俗成的文件名并不会带有特殊规则。




**本地对应仓库的创建**

.. code:: bash

  #初始化 该目录下将生成. git 文件夹
  git init
  #设置远程仓库地址 第一个为 HTTPS 第二个为 SSH，两个选一个即可。
  #设置完之后该信息将被写入到 .git/config 文件中，可修改该文件切换上传方式
  git remote add origin https://github.com/wuhongyi/xxxx.git
  git remote add origin git@github.com:wuhongyi/xxxx.git




   
.. 
.. README.rst ends here
