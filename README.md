# wechat payment for nodejs

Fork from [this Repo](https://github.com/befinal/node-tenpay)

## changelog

改写koa2 middleware对微信支付/退款回调xml数据的解析

ctx.request.body => ctx.request.xmlBody.xml
