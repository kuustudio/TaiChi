### 什么是无极模式？

简单来说，就是**可以提前使用未适配的任意模块**。具体就是，如果某些模块在太极的模块管理中显示为「暂不支持」，如果处于无极模式，可以忽略这个提示继续使用。

::: tip
注意：无极仅仅是允许你暂时使用没有适配的模块而已，没有别的神奇魔法。如果模块本身会造成闪退，开了无极依然会闪退；如果模块本身不支持你的系统（如某些过时并且不会更新的模块），那开了无极依然不支持。无极码不会让太极阴变成太极阳，也不会让原本无法使用的模块变得可用。
:::

### 为什么会有无极模式？

无极模式的初衷是为了**方便开发和测试模块**。

### 无极模式会全面开放吗？

**不会**。

不论你是否接受，以下是我的几点理由：

1. 开放无极对我存在潜在的风险，百害而无一利。太极天生就是一颗“魔丸”，一旦开放无极被不法分子用于非法场景，会将我至于及其危险的境地。我自认为年轻有为、前途光明，为了一个免费软件去冒这个险，我实在想不出任何理由。令人悲观的是，我可能会在任何时候停止对太极的开发。
2. 开放无极 100% 被滥用。不论是过去的 Xposed，还是我之前开发的 VirtualXposed，亦或是别人开发的 Autojs，无一例外都成为了黑灰产的利器。原子弹是个好东西，可以保护国家的安全；但如果恐怖分子掌握了原子弹，这个世界将陷入混乱。
3. 正常状态下的太极依然能满足 99% 用户的需求：
   1. 常用的模块都可以正常使用。
   2. 如果模块有更新，可以自行到 http://admin.taichi.cool 提交；如果签名没有发生改变，五分钟之后就会生效。
   3. 如果要使用新模块，也可以在 http://admin.taichi.cool 提交；我会在周末或者下班的时候处理。

### 你这几点理由都是瞎扯，为什么别的框架可以随便用模块？

只能说每个人对这个世界的理解不一样。我认可技术无罪，但是我同时也认为技术需要约束，或者说技术背后的人需要被约束。

为了约束模块，我限制了模块的使用。这样带来的坏处是不够自由，好处却有很多：

1. 整个生态很纯粹。诸如外挂、破解、黑灰产以及各路牛鬼蛇神都无法沾染太极。
2. 模块作者的利益会得到保障，盗版无法生存；我个人对此深恶痛绝。
3. 框架相对安全可控。

如果你仅仅是觉得模块更新不够快，或者想使用一些现在不支持的正常模块，那你完全可以去 http://admin.taichi.cool 注册一个账号然后自行提交。

如果你不喜欢被束缚的感觉，我表示理解因为我也不喜欢，但是某些东西是需要约束的。

如果你是开源狂热者，我理解你的想法，但是太极可能不适合你。

如果你热衷于破解软件，那么很抱歉太极不会为你提供便利。

### 我还是接受不了，弃坑

你我之间，是普通的用户-开发者关系，并无利益纠葛。请不要觉得你使用太极就是临幸我。

### 如何获得无极体验码？

**无极模式真的没什么特别的。**

原则上，只要你是个普通的正常用户，都可以获得体验码。

然而现实情况是，我通常不会花太多的精力放在发放体验码上面。我现在在创业，日常有很多事务要处理；下班或者周末的时候也以享受生活为主。开发和维护太极，只是我生活中很少很少的一部分。

如果你真的迫切需要体验码，建议在**周末**的时候联系我，有空的时候我会统一处理邮箱的消息。我女朋友会处理公众号的留言，会为老粉丝和忠实粉丝发放体验码；为了她的方便，请不要刷屏，谢谢。公众号有个优势就是可以一定程度区分正常用户（通过微信的用户属性、留言和消息互动数），也可以过滤掉一些恶意刷屏重复要码的用户（已经发放的会被标记）。

PS: 开发者邮件联系我并标明**开发者无极码**我会优先处理。滥竽充数我会拉黑。

> 获得码的用户请不要炫耀，因为你这样会被我带来很多工作量。最近两天 TG 消息炸了以至于我基本无法正常使用，不处理消息吧，我会觉得辜负了一颗火热的心，要处理的话又回花费我很多时间。

### 这个方式太麻烦了，为什么非要这么干？

我很抱歉。但是我没有一个很好的方式来标记“正常用户”。

### 干嘛不做成收费的？

不会，我有自己的事业。如果做成收费的，势必要花费很多的时间来保证为付费用户提供良好的服务，而我有更重要的事情要处理，不会在这上面花费时间。

### 你这是为了给公众号引流？

你们也知道，我公众号一个月也不会发几篇文章，每个月的微信给的广告费在 1000RMB 左右；有时候会发个游戏链接，收到的费用会多点。这些钱对一个没有收入的学生来说或许很多，但对于我来说真的算不了什么。毕竟我曾经在经济低迷的时候 [主动放弃了在支付宝核心部门的工作](https://www.zhihu.com/question/26787893/answer/441362005)。如果你非要觉得我的赚钱方式是：先写个百万用户的 app 免费给人用，然后费尽心机地把用户导到公众号，最后每天收二三十块钱的广告费的话，那我只能说：夏虫不可语冰。

### 提示无极激活但是没有效果？

1. 请关闭太极之后重新打开。
2. 太极·阴如果依然如此，请给足够的权限。
3. 请尝试关闭太极的 阴阳之门。

### 太极阴可以进入无极吗？

可以。太极·阴和太极·阳都可以进入无极。但是，太极·阴模式下的无极状态依然无法使用太极·阳下的模块。

### 手机重启之后，无极没了？

1. 可以使用原来的无极码重新激活。
2. 建议升级太极 App 到 5.7.0 以上，已修复这个问题。

### 无极码什么时候会失效？

如果你拿到了无极码但是一直没激活，那么大约 2 周之后就会自动失效。

如果你已经激活，无极码绑定的是设备 ID。正常情况下只要你把码保存好，刷机之后依然是可以重新激活的。当然刷机之后设备 ID 偶尔会被重置，这时候码就会失效了。这种情况你可以发邮件给我处理，提供原来的码并且标题显著标明**无极码失效**即可，我会优先处理这种情况。

::: warning
如果你不是码失效而说是 **无极码失效**，我会当作垃圾邮件处理。
:::
