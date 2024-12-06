---
title: NyaProxy の 入门保姆式指令
description: 
published: true
date: 2024-12-06T13:43:48.466Z
tags: 
editor: markdown
dateCreated: 2024-12-02T00:08:33.464Z
---

# NyaProxy の 基础使用指令
![](https://img.shields.io/badge/Fisunia_Faint-pink?style=for-the-badge&label=Writer) ![](https://img.shields.io/badge/juice-orange?style=for-the-badge&label=Writer)

<br>
<div class="highlight-box">
<img src="https://photo.vteamer.cc/i/2024/12/02/hahf0h.png" alt="Minecraft 经验瓶" class="icon"> <!-- Minecraft 经验瓶图标 -->    <div class="content">
        <strong>这是精品!!!</strong><br>
        您目前在浏览的页面是一个精品页面！精品页面意味着该页面的内容十分客观，充实且详细，是其他编辑者学习的榜样。
<br>
同时我们会赠送专属勋章 保留在顶部!<br>
如果你认为某个页面应该是精品，请前往我们的GitHub仓库，提出Issue告诉我们。<br>
    </div>
</div>

> **你需要重点关注**
该页是指导你能够正常使用 NyaProxy 产品的一页
如果你是 **第一次使用本产品/使用此新架构系统前的元老用户** 请详细阅读本页
 {.is-info}
 
 ## 需要准备的 Item 有
1. 准备一个 QQ账号 **该账号在将来你会一直使用**[注意: 这个账号对你来说十分重要，对以后的正常使用 以及 平台的迁移/同步 都起着重要地位] 如果你的无脑操作/绑定导致账号数据清空<kbd>**我们并不会受理你的换绑请求，您需要重新购买你的服务**</kbd>
2. 准备一台能 正常登录QQ账号的 设备<mark>[不限于操作系统/设备类型]</mark>
3. 你的刚买的卡密
4. 确保你的 QQ账号 已进入本产品的 QQ群

## 指令
进入本产品 QQ群 后
直接在群里发指令  `/help` 或 `!help`

你将会收到来自 机器人 的回复
> 当前可用的指令有：
    /landy  我是抖 M
    `/migrate`  从旧版 NyaProxy 中转移剩余时长
    `/redeem`  兑换服务
    `/services`  查看已有的服务及其剩余时长/到期时间
    `/showlogs`  查看用户审计日志
    `/start`  初始化服务
    `/stop`  停止服务
    `/transfer`  将主服务的剩余时长转移到 EU 按时计费服务
输入“`/help 指令名`”查看特定指令的语法和使用示例。

### [Migrate]使用此新架构系统前的元老用户
`/migrate`  
此指令输入后将会从 旧版-NyaProxy 数据库 中迁移剩余时长 到 新版-NyaProxy-NG 数据库 中

### [Redeem]激活-第一次使用本产品的用户
进入 主群QQ群 后，拿好你买好的卡密
在群中输入该指令 激活/兑换
`/redeem`
此指令输入后，将会兑换你的卡密并绑定你的 QQ账号
一般卡密样式为:
> examplePrefix-(balanceTime)-xxxxxxxxxx

比如:
> Nya-20hours-yuanshenqidonq
Nya-DXGisBu11Shit
Milk-20hours-milkserver
{.is-info}

兑换卡密的格式:
> `/redeem Nya-DXGisBu11Shit`
{.is-success}

**你拿到的卡密请不要捏头掐尾的去掉东西，不然会兑换失败**
> `/redeem 20hours-yuanshenqidonq`
`/redeem DXGisBu11Shit`
{.is-danger}

### [Services]查看你剩余的时长
`/services` 
此指令用于查看本产品剩余可使用的时间

### [Showlogs]查看你的时长走向
`/showlogs`
此指令用于查看本产品你的已使用时长的走向，包括 自行使用走向/管理员时长调整 

---
> 下面将是重点，请初次使用服务的用户重重点留意
**只是注意关注，并不会操作困难，请用户放心**
{.is-warning}

# 使用 NyaProxy 服务的指令
## 开始计费
`/start`
初始化服务计费
该指令的全通用格式为:
`/start <servicesMode> [-t <targetServer>]`

> `<servicesMode>`：使用服务模式.目前用户常用的服务模式有以下几种:
  usagebased.cn.hypixel 计费模式 目标服务器 [美国:Hypixel]
  usagebased.de.any 计费模式 目标服务器 ***[欧洲:未指定.需自行定向]***
  subscription.de.any 订阅模式 目标服务器 ***[欧洲:未指定.需自行定向]***
 `[-t <targetServer>]`: 指定目标服务器.目前该代码是专门为 [ subscription.de.any/usagebased.de.any] ***这种未指定的目标服务所使用，其他情况下并不需要该附加命令式***
{.is-info}

**通常情况下，如果直接使用命令**
`/start` 此时目标服务器默认为 *usagebased.cn.hypixel*
~~当然，如果你想炫耀你神速の打字速度的话，你也可以~~
`/start usagebased.cn.hypixel`
当您在 Hypixel 上惨遭看门狗或者 Staff 的封禁，请千万记住更换IP，具体方法为重新启动服务。如果您未重新启动服务可能会被 Suspicious Activity Ban，NyaProxy 不会为此类封禁负责。

如果你需要使用EU-Proxy *[指 subscription.de.any/usagebased.de.any 服务]*
那你需要添加指定目标服务器进行加速
以游玩 BlocksMC.com 服务器为举例
使用指令
> `/start usagebased.de.any -t Blocksmc.com`
{.is-success}

当你输入之后，耐心等待主控初始化服务，当机器人回复你的时候，就说明启动成功啦～
> @xxxxx 服务 < servicesMode > 已初始化。查看你的 QQ 邮箱以获取连接地址。

## 停止计费
`/stop`
暂停服务并结算计费
~~这个指令没啥好说的~~

## 转移服务时长 [HYP ---> EU]
`/transfer`
将 *usagebased.cn.hypixel* 的时长
转移至 *usagebased.de.any* 服务
该指令的格式为:
`/transfer <convertiveAmount>`
> `<convertiveAmount>` :将该数量HYP时长转换成EU时长
{.is-info}

使用举例:
> `/transfer 600`
**BOT MSG:**
@UnknownUser 成功将 600 分钟剩余时长转移到 EU 服务，增加 300 分钟。
{.is-success}

> 注意：该时长转换是 ***有比例的*** 其转换的比例为 HYP:EU ＝ 2:1
**请注意时长转换量!!**
{.is-warning}

若你需要单独使用 EU 服务 ， 你可以前往这里 **↓** 购买独售卡密
> 想直达独售卡密商品窗口? **[点击我跳转到购买页面](http://shop.nyaproxy.xyz?cid=1&mid=32)**
{.is-info}





