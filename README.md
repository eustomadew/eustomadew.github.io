# website-hugo
Homepage: Academic or Coder theme

[Hugo Themes](https://themes.gohugo.io/)  
[Hugo Theme - Guide](https://github.com/hugo-toha/guides/tree/main/content/posts)  
[Hugo Theme - Coder](https://themes.gohugo.io/themes/hugo-coder/)  
[Hugo Theme - toha](https://themes.gohugo.io/themes/toha/)  

[hugo-toha theme](https://github.com/hugo-toha/hugo-toha.github.io)  
[如何用 hugo 搭建博客](https://zhuanlan.zhihu.com/p/126298572)  
[git 无法push远程仓库 Note about fast-forwards 问题解决](https://blog.csdn.net/weixin_42596434/article/details/88759295)  

```shell
$ hugo new site blog
$ hugo # generate `public` folder
$ hugo server  # http://localhost:1313
```

```shell
$ hugo
$ cd public
$ git init
$ git add .
$ git commit -m "first personal homepage"
$ git remote add origin git@github.com:eustomadew/eustomadew.github.io
$ $ git push origin master

$ git push origin master --allow-unrelated-histories
$ git status
$ git add .
$ git commit -m "Update on 19 Aug 2021, Thu 23:57 PM"  # format
$ # git push
$ git push --set-upstream origin master
```
