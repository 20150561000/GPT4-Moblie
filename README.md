# GPT4-Moblie

原作者是NijikaMyWaifu。发布在reddit的一个油猴脚本，在 ChatGPT 网页版使用 GPT-4 Mobile 模型。

如果你对版权有异议，请提交issue。

If you have an objection to copyright, please submit an issue。

# Use GPT-4 Mobile UserScript

这个油猴脚本用于修改 OpenAI 聊天室中使用的语言模型，将默认的语言模型切换为" GPT-4 Mobile"。目前GPT4M没有和GPT4一样的25R/3H限制。

具体的分析还可以阅读本项目的 [code-review](code-review.md) 、 [compare](compare.md) 、[models-review](models-review.md) ，可以进一步了解有关GPT版本的一些事情。

## 要求和限制

1. 你可以正常访问OPENAI相关的网站，尤其是 `chat.openai.com` 。[推荐一个能通OPENAI和ChatGPT官网的VPS](https://my.frantech.ca/aff.php?aff=4329)。
2. 同时你要能在浏览器直接访问这个域名的网站，而不是其他需要替换域名反向代理等，除非你会魔改。
3. 建议使用Chrome浏览器、或者EDGE浏览器等Chrome的异父异母的亲兄弟。
4. 一个浏览器扩展，我建议是 Tampermonkey ，建议去谷歌浏览器扩展应用商店下。
5. 中英文基本的阅读能力。
6. 一个OPENAI账号，且开通了ChatGPT Plus订阅，不然你访问不了GPT4-Mobile模型。如果不知道怎么获取订阅，请阅读本文档末尾。

## 安装

1. 首先，你需要安装一个支持 UserScript 的浏览器扩展，例如 Tampermonkey。
2. 在你的 UserScript 扩展中，创建一个新的脚本并将这个脚本的内容粘贴进去。
3. 保存脚本，然后去 `chat.openai.com`打开使用即可。
4. 需要开启GPT-4 Mobile 时勾选网页正下方的按钮。如果不需要开启，则可以取消勾选或者在插件处停用该脚本。

## 使用

在 `chat.openai.com` 上，你将看到页面底部有一个 "Use GPT-4 Mobile" 的复选框。选中此复选框，即可切换到 "GPT-4 Mobile" 模型。你的选择将会被保存，所以在你下次访问时，这个选项将保持上次的状态。

## 功能

- 可以切换语言模型为 "GPT-4 Mobile"（会覆盖其他选择，包括网页上的GPT3.5和GPT4）。
- 复选框的状态会被保存，方便下次访问时使用。

## 注意事项

- 这个脚本可能不会与 OpenAI 的所有更新保持兼容。
- 使用此脚本时需要注意，因为它会修改默认的语言模型，如果你勾选了那个按钮的话。
- 你需要本身就能在对应浏览器访问ChatGPT4（网络、浏览器、PLUS订阅）
- 如果你在无痕模式使用则需要注意是否在扩展插件设置中启用了无痕的支持。
- 不得用于违法违规行为，后果自行承担，和本人无关。
- 该方式随时可能会被阻止、封锁等。甚至对你的账号、IP等造成损失，比如被封号等。由此产生的经济损失和法律风险由使用者自行承担。

## 版权

该油猴脚本原版出处为Reddit用户 https://www.reddit.com/user/NijikaMyWaifu/ 的帖子 https://www.reddit.com/r/saraba2nd/comments/13mbiw1 标题为 “一个油猴脚本，在 ChatGPT 网页版使用 GPT-4 Mobile 模型”。

OpenAI相关为 https://openai.com/ 网站控制者所有。

油猴相关为 https://greasyfork.org/ 网站控制者所有。

如果你对版权有异议，请提交issue。

If you have an objection to copyright, please submit an issue。

## 版本

在 [compare](compare.md)  中，可以注意到截至2023-05-26 HKT，GPT官方在GPT4-Mobile、GPT4-Browser两个环境下，不使用联网模式是不能认知到自己是GPT4模型的，而GPT3.5和GPT4以及进行联网的GPT4-Browser没有这个问题，可以认知到自己的模型版本

## 账号、订阅、购买、付费等

### 账号

目前手动注册需要
1. 邮箱/谷歌苹果微软账号x1，建议邮箱，一旦注册了不可复用，注销也是。
2. 服务区手机号，不支持虚拟号（尤其是美国、Google Voice）、不支持中国包括大陆香港，支持常见的英国实体手机号。也有人用的什么接码。
3. 可用的网络、浏览器

### 付费

升级付费需要服务区发行的银行卡（包括借记卡），网关是Stripe，不支持大陆、香港卡，非美国卡失败率也很高，基本都是用美国发行的卡。注意API订阅只能走卡付款。结算方式是月结账单，每月初扣费。

### 订阅

之前只能在网页版购买PLUS，规则是月滚动扣款。后来开通了IOS商店付费。现在在苹果商店US即可付费PLUS订阅（但是API的那种付费不支持）。苹果商店CN和HK别想太多。

苹果US的付费方式主要是 美国卡、美国PayPal、余额。目前余额可以用礼品卡充值没什么难度；美国卡就正常的都行，可以参考我博客；美国PayPal不推荐，目前注册也是要求美国非虚拟号且日常封号，基本不太可能弄。注意没有卡和P时，使用余额可能要求绑定付款方式，原因是你没有使用美国IP。【其他可用区请看下面】

### 购买

账号其实也可以去各类第三方网站购买，这类网站很多，空号基本1-3CNY 一个。

### ChatGPT For IOS 可用区
2023-05-18 开放 美国

2023-05-25 开放 阿尔巴尼亚、克罗地亚、法国、德国、爱尔兰、牙买加、韩国、新西兰、尼加拉瓜、尼日利亚和英国

2023-05-26 开放 阿尔及利亚、阿根廷、阿塞拜疆、玻利维亚、巴西、加拿大、智利、哥斯达黎加、厄瓜多尔、爱沙尼亚、加纳、印度、伊拉克、以色列、日本、约旦、哈萨克斯坦、科威特、黎巴嫩、立陶宛、毛里塔尼亚、毛里求斯、墨西哥、摩洛哥、纳米比亚、瑙鲁、阿曼、巴基斯坦、秘鲁、波兰、卡塔尔、斯洛文尼亚、突尼斯、阿拉伯联合酋长国 


