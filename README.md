# vimfiles
1、安装vim 从官网下载http://www.vim.org/download.php
2、安装 pathogen 下载地址https://github.com/tpope/vim-pathogen
3、在vim安装更目录下的vimrc配置文件中加一句话：
call pathogen#infect()

4、根目录下创建插件安装目录
PS：windows下安装vim会自动创建vimfiles文件夹，在文件夹下创建bundle文件夹。所有的插件在此目录下管理
linux直接在跟目录下创建bundle目录就ok

5、windows 小伙伴需要安装git  具体怎么安装网上查哦 linux 小伙伴跳过
6、在bundle目录下安装和更新插件

git submodule 不做详细解答

git submodule init
git submodule update
git submodule foreach "git checkout master && git pull"
git submodule add git://github.com:username/plugin.git bundle/plugin
