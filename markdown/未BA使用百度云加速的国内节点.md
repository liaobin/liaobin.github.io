#未BA使用百度云加速的国内节点

我朝有很多免费CDN服务,但是都要求BA.那么有能不BA使用国内节点的方法吗,当然...还是有的

首先用正常的CNAME的方式接入百度云加速,生效后再到域名DNS解析处将CNAME改成A记录,指向文章最下方的百度云加速的国内ip即可(其他CDN商不知道能不能用此法,没试过),这种方法能实现类似反代的功能,如果要做到CDN的那种就近访问节点的话,可以试试某些DNS商的分省解析功能,缺点是暂时不支持https,或者说我还不知道😶

这是个小demo-->[233.lolvip.net](http://233.lolvip.net/)

`119.147.134.80`

`112.25.91.129`

`58.211.137.129`

`116.31.127.129`

`119.147.134.129`

啊哦,好像玩过头了- - 可以不用尝试了😂

![](https://o2mu9ei56.qnssl.com/jiansu.png)
