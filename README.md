# Pallas-Bot

我是来自米诺斯的祭司帕拉斯，会在罗德岛休息一段时间......虽然这么说，我渴望以美酒和戏剧被招待，更渴望走向战场。

## 牛牛有什么功能？

牛牛的功能就是废话和复读。牛牛几乎所有的发言都是从群聊记录中学习而来的，并非作者硬编码写入的。群友们平时怎么聊，牛牛就会怎么回，可以认为是高级版的复读机

## 那为什么牛牛说了一些群里从来没说过的话？

牛牛有跨群功能，若超过 N 个群都有类似的发言，就会作为全局发言，在任何群都生效

## 你说牛牛没有功能，为什么有时候查询信息、或者一些其它指令，牛牛会回复？

从别的机器人（可能是其他群）那里学来的

~~你这机器人功能不错呀，现在牛牛也会了！~~

## 有时候没人说话，牛牛自己突然蹦出来几句话

哈，是主动发言功能！内容同样从群聊里学来的！

## 怎么教牛牛说话呢？

正常聊天即可，牛牛会自动学。

如果想强行教的话，可以这样：

```text
—— 牛牛你好
—— 你好呀
—— 牛牛你好
—— 你好呀
—— 牛牛你好
—— 你好呀
```

如此重复 3 次以上，下一次再发送 “牛牛你好”，牛牛即会回复 “你好呀”

## 牛牛说了一些不合适的话，要怎么删除？

群管理员 **回复** 牛牛说的那句话 “不可以” 即可，同样的若超过 N 个群都禁止了这句话，就会作为全局禁止，在任何群都不发

## 怎么把牛牛拉到自己的群里呢？

~~加好友，再邀请加群，即可。牛牛都会自动同意的~~

牛牛的号天天被冻结，所以御坂牛牛计划正式启动（）

详情请加 [牛牛调教群](#qq群)，在群文件的在线表格里挑一只你喜欢的牛牛牵走~

## 题外话

牛牛的说什么完全依赖于大家聊什么，希望大家不要故意教牛牛一些不好的东西。发现牛牛学了一些不合适的话及时帮忙删除。

大家一起教出更棒更聪明的牛牛！✿✿ヽ(°▽°)ノ✿

## 如何配置一只自己的牛牛？

### 方式一

加 [牛牛调教群](#qq群)，按照群公告的步骤操作后，将自己的 QQ 小号账号密码发送给我，与大牛牛共享同一份数据（御坂牛牛！）

### 方式二

配置一只全新的牛牛

1. 安装 [nonebot2](https://github.com/nonebot/nonebot2)
2. clone 本仓库，并安装 requirements
3. 依次安装每个 [插件](src/plugins) 的额外依赖或配置，请查阅对应的 README ~
4. 使用 `nb run` 运行 bot
5. 访问 `http://127.0.0.1:8080/go-cqhttp/#/` 添加或管理你的账号

## QQ群

牛牛调教群：831322617  
开发者群：716692626
