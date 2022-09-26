# yuque_vercel_webhook_api
基于vercel的语雀severless云函数api部署
你需要传递的参数有 token，user，source。

```
https://yuque-vercel-webhook-api.vercel.app/api?
token='{填写你的github私钥}'&
user='{填写你的github用户名}'&
source='{填写你的github仓库地址}'

示例：
https://yuque-vercel-webhook-api.vercel.app/api?token='8888888888'&user='Zfour'&source='my-blog-source-file'
将这个URL路径作为触发链接，在语雀中进行配置。
```

修改触发链接里的参数项，访问这个链接，如果出现‘This’s OK!’说明配置成功。
复制 URL 路径作为触发链接，在语雀中进行配置。