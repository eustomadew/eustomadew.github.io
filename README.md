# website-hugo
Homepage: Academic or Coder theme

[Hugo Themes](https://themes.gohugo.io/)  
[Hugo Theme - Coder](https://themes.gohugo.io/themes/hugo-coder/)  
[Hugo Theme - toha](https://themes.gohugo.io/themes/toha/)  
[font awesome icons](https://fontawesome.com/v6.0/icons?s=solid%2Cbrands)  

[Hugo-toha Theme](https://github.com/hugo-toha/hugo-toha.github.io)  
[Hugo-toha Guide](https://github.com/hugo-toha/guides/tree/main/content/posts)  
[如何用 hugo 搭建博客](https://zhuanlan.zhihu.com/p/126298572)  
[git 无法push远程仓库 Note about fast-forwards 问题解决](https://blog.csdn.net/weixin_42596434/article/details/88759295)  
[hugo-toha.github.io data en sections about.yaml](https://github.com/hugo-toha/hugo-toha.github.io/blob/source/data/en/sections/about.yaml)  

[Nick Galbreath, CTO and co-founder](https://www.client9.com/using-font-awesome-icons-in-hugo/)  
[Font Awesome in Hugo](https://matze.rocks/posts/fontawesome_in_hugo/)  
[每次调用加密需要先清理public目录并生成一次](https://github.com/Li4n0/hugo_encryptor/issues/15)  
[Hugo 博客自定义优化 awesome font](https://shishuochen.gitee.io/2020/uffick8u1/)  
[Hugo 新手道場](https://hugo-for-newbie.kejyun.com/docs/theme/documentation/docsy/install/)  
[将自定义图标添加到超赞的字体](https://qastack.cn/programming/11426172/add-custom-icons-to-font-awesome)  


```shell
$ hugo new site blog
$ hugo # generate `public` folder
$ hugo server  # http://localhost:1313 (bind address 127.0.0.1)
#              # Press Ctrl+C to stop
```

**publish**
```shell
$ hugo
$ cd public
$ git init
$ git add .
$ git commit -m "first personal homepage"
$ git remote add origin git@github.com:eustomadew/eustomadew.github.io
$ git push origin master
```

**backup** <!--save-->
```shell
$ git push origin master --allow-unrelated-histories
$ git status
$ git add .
$ git commit -m "Update on 19 Aug 2021, Thu 23:57 PM"  # format
$ # git push
$ git push --set-upstream origin website-hugo
```

**install**
```shell
$ snap install hugo
$ # themes
$ mkdir themes
$ git submodule add https://github.com/hugo-toha/toha.git themes/toha
$ git submodule add https://github.com/vimux/mainroad.git themes/mainroad
$ git submodule add https://github.com/vaga/hugo-theme-m10c.git themes/m10c
```
