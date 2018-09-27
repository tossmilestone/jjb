# 京价保 - 自动申请京东价格保护

京价保是一个帮你监控商品价格变化自动申请京东价格保护，顺便帮你签到领京豆、钢镚的 Chrome 拓展。

强烈推荐使用 Chrome 商店安装（这样才能获得自动更新）：

<a target='_blank' rel='nofollow' href='https://chrome.google.com/webstore/detail/gfgkebiommjpiaomalcbfefimhhanlfd'>
  <img alt='Chrome
  web store' width='496' height='150' src='https://oi4m2ufmx.qnssl.com/jjb/cws_badge_496x150.png' />
</a>

同时提供 Firefox 版本：

<a href="https://addons.mozilla.org/zh-CN/firefox/addon/jjb/" target="_black">
  <img alt="安装 Firefox 版" class="firefox" src="https://d33wubrfki0l68.cloudfront.net/4ce5ce101cdaa4030248fab2934960ad1cc6960e/3f95c/firefox-quantum.png" width="32px">
</a>

> 

## 主要功能

* 自动监控最近订单商品的价格变化，在商品降价时自动申请价格保护
* 自动签到领取京豆
* 自动签到领取钢镚
* 自动领白条券
* 自动领Plus券
* 自动领全品类
* 自动京东金融会员签到
* 商品价格走势图

## 界面截图

#### 主界面

![主界面](http://jjbcdn.zaoshu.so/screenshots/jjb.2.0.0.png)

#### 价格走势图

![价格走势图](http://jjbcdn.zaoshu.so/screenshots/pricechart.png)


## 重要提示

1. 京价保并非开源软件，不许可您以任何形式进行再发行，请仔细阅读协议模块。

2. 当前仓库是插件源代码，无法直接安装，如需安装请自行参考 #如何开发 编译。


## 如何开发

* 安装依赖
> yarn 

* 开始开发
> yarn dev --version=1.16.3 --browser=chrome

`主要作用就是合并压缩代码，质疑代码和市场版本不一致，请先自行打包一下再对比`

## 价格

京价保不是一个免费应用，你需要支付任意的金额获取合法的授权。尽管目前代码中没有任何强制的校验。

在理想的情况下，京价保通常至少能够提供每个月大于5元的等同现金的收入（每天3~15个京豆+0.08个钢镚），即使你买的东西中没有任何一件降价。

![](https://oi4m2ufmx.qnssl.com/jjb/weixin_pay.png?imageView2/0/h/300)

你的打赏能帮助京价保保持更新，适配京东的页面修改，添加更多自动功能。

## 安全提示

京价保不会在任何情况下强行劫持访问、插入恶意代码、上传隐私信息或利用你的电脑挖矿。

若你发现任何类似问题，请首先确保你使用的是商店版本，不建议在任何情况下使用第三方提供的安装包。

京价保目前有约两万人正在使用（包括 Chrome 和 Firefox 以及其他浏览器非市场版本），其中至少有数千名开发者，京价保的代码有近千人关注，若怀疑京价保代码有问题，不妨直接审查代码。


## 关于黑号

网络上有很多人表示多次领券和申请价格保护会导致账号“黑号”，不知道其对京东的风控政策是如何了解的，为何正常使用其官方提供的功能会导致账号被“黑”？

目前没有任何一例可靠的报告表明使用京价保会导致“黑号”，作者本人和同事家人使用京价保近一年，即使在开发阶段疯狂测试申请价格保护账号亦无任何异常。

但，若你担心此项风险，决定自我审查，关闭领券功能或直接卸载京价保即可。


## 系统支持

目前京价保对 Windows 和 Mac 平台的 Chrome 有较好的支持。

据用户反应，部分 Chromium 内核的国产浏览器可能有兼容问题（例如搜狗浏览器）。

Ubuntu 有明确的兼容问题，由于作者不拥有任何 Ubuntu 设备，因此暂时无法解决。

## 获取信息

你可以 Telegram 上关注京价保 https://t.me/jingjiabao

您还可以关注京价保的公众号，主要发布更新通知：

![京价保公众号](http://jjbcdn.zaoshu.so/wechat/qrcode_for_gh_21550d50400c_430.jpg)

## 协议和授权

京价保并非一个开源软件，作者保留全部的权利。
公开源代码的目的是为了让使用者能够审计代码，但是你仍然可以就以下方式合法的使用本项目的全部代码和资源：

1. 个人使用
2. 以学习目的使用全部或部分代码

但你不可以：

1. 将本项目的部分或全部代码和资源进行任何形式的再发行（尤其是上传到 Chrome 商店）
2. 利用本项目的部分或全部代码和资源进行任何商业行为

## 贡献代码

京价保并非一个开源项目，也不是社区共同创造，其全部功能由作者独立完成。

如果你愿意放弃所有权利，并将权利无条件转让给京价保作者，欢迎您贡献代码。

## 提交反馈

欢迎提交 issue，请写清楚遇到问题的原因，浏览器和操作系统环境，重现的流程。
如果有开发能力，建议在本地调试出出错的代码。

不接受功能请求的 issue，功能请求可能会被直接关闭，请谅解（正确的方式是打赏并附言）。

若有功能建议或其他非技术反馈，请使用应用内反馈。由于京价保不设客服人员反馈将默认不回复。

## 联系作者

请发邮件至：`ming@tiny.group`

请勿发送功能咨询邮件，将不会收到回复。相关功能细节请自行了解。

## 赞助商

<h3>
  <a href="https://www.duohui.cn/?utm_source=jjb&utm_medium=github&utm_campaign=jjb-readme" target="_blank">多会 - 专业的活动管理系统</a>
</h3>

<h3>
  <a href="https://www.duotai.net/?utm_source=jjb&utm_medium=github&utm_campaign=jjb-readme" target="_blank">多态</a>
</h3>
