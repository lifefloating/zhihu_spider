# zhihu_scrapy
新版知乎抓取 scrapy requests selenium


## 说明

新版的知乎登录改了，现在需要提交pay reload 参数 而且payreload参数中有个signature 是js生成的，
和之前的一样去数据是rest api接口方式的，具体可以f12 点全部回答的时候看下api url地址，
大概看下里面参数，有几个还是能够通过对比发现含义的。具体见代码。
