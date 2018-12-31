#L-QUANT

##简介

###L-QUANT才刚刚开始，以后每日都会更新，在此立一个FLAG

###今天就是L-qunt的生日，2018.12.28

```
{
    "name": "wblearn-blog",
    "title": "Wblearn Blog",
    "author": "Wblearn <1275660493@qq.com>",
    "version": "1.7.0",
    "homepage": "https://wblearn.github.io",
    "repository": {
        "type": "git",
        "url": "https://github.com/wblearn/wblearn.github.io"
    },
    "bugs": "https://github.com/wblearn/wblearn.github.io/issues",
    "devDependencies": {
        "grunt": "~0.4.5",
        "grunt-contrib-less": "~0.11.4",
        "grunt-contrib-watch": "~0.6.1",
        "grunt-banner": "~0.2.3",
        "grunt-contrib-uglify": "~0.5.1"
    },
    "scripts": {
        "preview": "cd _site; python -m SimpleHTTPServer 8020",
        "py3view": "cd _site; python3 -m http.server 8020",
        "watch"  : "grunt watch & npm run preview & jekyll serve -w",
        "py3wa"  : "grunt watch & npm run py3view & jekyll serve -w",
        "boil"   : "git push boilerplate boilerplate:master",
        "push"   : "git push origin master --tag",
        "cafe"   : "git co gitcafe-pages; git merge master; git push gitcafe gitcafe-pages:gitcafe-pages --tag; git co master;"
    }
}
```
