# B 站热评与楼中楼

三批合计 92 个视频，1,798 条主楼，5,341 条楼中楼。

## 第一批 · 2026-11-19

2026-11-19，通过 Edge 视频页的「最热」评论区采样。共 33 个视频、630 条主评论、1009 条楼中楼，其中 339 个主楼带回复。

每视频保留页面排序前 20 个主楼，优先展开其中高赞的几楼，每楼最多收 5 条，顺序沿用网页。其余主楼含页面预览中可见的回复。三条视频到页面末尾时主楼不足 20 条，实际计数见下表。

每个 BV 一个 JSON。看对话时，从同一个 `threads[]` 读取 `root_comment` 和 `sub_replies`；`rank` 是采样时的展示顺序。正文、表情文本、回复提及、显示昵称、页面日期和赞数随楼保存。图片附件未下载，以图为包袱的楼可回原视频看。页面没有给出每条评论的稳定 ID，对楼可用 BV、正文、昵称和时间。

`title` 是网页标题，`target_title` 和 `target_type` 来自[候选清单](../bilibili_bv_targets.jsonl)。「弱关联团建场」仅是选片标签。普通讨论也保留，是否出现目标梗需要读实际楼层。`likes_display` 保留页面显示值；页面缩写赞数时 `likes` 为 null。

| 视频数据 | 模块 | 候选类型 | 主楼 | 楼中楼 | 来源 |
|---|---|---|---:|---:|---|
| [张雪峰老师在线表演吃雪糕，三口一个巧乐兹，不建议模仿！](BV1f2xLz4EMX.json) | 地狱笑话 | 烂梗原视频 | 20 | 53 | [视频](https://www.bilibili.com/video/BV1f2xLz4EMX/) |
| [张雪峰老师出圈作合集，你跑不过我你信吗？](BV1Xkj36cESD.json) | 地狱笑话 | 烂梗原视频 | 20 | 27 | [视频](https://www.bilibili.com/video/BV1Xkj36cESD/) |
| [《念张师》, We Are Charlie Kirk版 🗣🗣🗣【补档】](BV1H7V36qEwD.json) | 地狱笑话 | 烂梗原视频 | 20 | 38 | [视频](https://www.bilibili.com/video/BV1H7V36qEwD/) |
| [大嘴扫雪机，除雪速度不是一般的快](BV1jz411z75c.json) | 地狱笑话 | 弱关联团建场 | 20 | 9 | [视频](https://www.bilibili.com/video/BV1jz411z75c/) |
| [除雪神器—国外先进清雪设备大盘点！每小时可清除超万吨的积雪！](BV1Q8411n7Ba.json) | 地狱笑话 | 弱关联团建场 | 15 | 4 | [视频](https://www.bilibili.com/video/BV1Q8411n7Ba/) |
| [才发现桶装冰红茶是科比牢大](BV1Am4y1x7Co.json) | 地狱笑话 | 烂梗原视频 | 20 | 32 | [视频](https://www.bilibili.com/video/BV1Am4y1x7Co/) |
| [科比成功打赢复活赛：孩子们，我又回来了。谁说牢大科比的视频生成不了的。我这不是生成了吗。到底是谁说我又电子坠机的，出来说话。国外ai生成不了牢大但是国内AI可以](BV1NQriBUEmq.json) | 地狱笑话 | 烂梗原视频 | 7 | 1 | [视频](https://www.bilibili.com/video/BV1NQriBUEmq/) |
| [see you again 但是全世界大合唱致敬科比](BV1QH4y1z79Q.json) | 地狱笑话 | 烂梗原视频 | 20 | 23 | [视频](https://www.bilibili.com/video/BV1QH4y1z79Q/) |
| [康帅傅新品“冰红茶味的”红烧牛肉面，是智商税还是真香？？](BV1JQ4y1s7CX.json) | 地狱笑话 | 弱关联团建场 | 20 | 39 | [视频](https://www.bilibili.com/video/BV1JQ4y1s7CX/) |
| [抽象烂活儿越来越多，冰红茶咋走到今天这步的？](BV1qsyuBAELC.json) | 地狱笑话 | 弱关联团建场 | 20 | 41 | [视频](https://www.bilibili.com/video/BV1qsyuBAELC/) |
| [「DeepSeek」遭『Claude』创始人打脸：夸大且落后❗️](BV1HYVyz1EFH.json) | 地狱笑话 | 弱关联团建场 | 20 | 32 | [视频](https://www.bilibili.com/video/BV1HYVyz1EFH/) |
| [Claude AI老板Dario Amodei暗示：中国AI模型就是垃圾，一文不值！](BV12yzhBcE7J.json) | 地狱笑话 | 弱关联团建场 | 20 | 25 | [视频](https://www.bilibili.com/video/BV12yzhBcE7J/) |
| [叮咚鸡叮咚鸡，大狗大狗叫叫叫](BV1xLC6YTEux.json) | 无营养烂梗 | 烂梗原视频 | 20 | 18 | [视频](https://www.bilibili.com/video/BV1xLC6YTEux/) |
| [基米说完整版](BV1Dua2zyE4G.json) | 无营养烂梗 | 烂梗原视频 | 20 | 32 | [视频](https://www.bilibili.com/video/BV1Dua2zyE4G/) |
| [圆头耄帝独断万古（纯享版）](BV1gELPzDEp2.json) | 无营养烂梗 | 烂梗原视频 | 20 | 49 | [视频](https://www.bilibili.com/video/BV1gELPzDEp2/) |
| [Xin Đừng Nhấc Máy 请不要哈气](BV1NPGAzhEvw.json) | 无营养烂梗 | 烂梗原视频 | 20 | 39 | [视频](https://www.bilibili.com/video/BV1NPGAzhEvw/) |
| [哈基米在等你的来电~【纯净哈基米】](BV1974WzGEdu.json) | 无营养烂梗 | 烂梗原视频 | 20 | 28 | [视频](https://www.bilibili.com/video/BV1974WzGEdu/) |
| [在床上发现一只曼波](BV1rS421d7VL.json) | 无营养烂梗 | 烂梗原视频 | 20 | 27 | [视频](https://www.bilibili.com/video/BV1rS421d7VL/) |
| [为什么渔民捞到翻车鱼会赶紧扔掉？](BV1GAtJzcE4B.json) | 无营养烂梗 | 弱关联团建场 | 20 | 43 | [视频](https://www.bilibili.com/video/BV1GAtJzcE4B/) |
| [渔民见了都嫌弃的翻车鱼！](BV1Mx4y1d7ih.json) | 无营养烂梗 | 弱关联团建场 | 20 | 32 | [视频](https://www.bilibili.com/video/BV1Mx4y1d7ih/) |
| [提纳里：都说别讲冷笑话了！！](BV12v4y1Y7xh.json) | 冷笑话 | 烂梗原视频 | 20 | 47 | [视频](https://www.bilibili.com/video/BV12v4y1Y7xh/) |
| [赛诺别背冷笑话了你打不过天赋型选手的](BV1cUSNYJEnf.json) | 冷笑话 | 烂梗原视频 | 20 | 48 | [视频](https://www.bilibili.com/video/BV1cUSNYJEnf/) |
| [【尼古喵喵】关西冷笑话解析2.0（说实话解析了也不好笑）](BV1xYaT61E13.json) | 冷笑话 | 烂梗原视频 | 20 | 34 | [视频](https://www.bilibili.com/video/BV1xYaT61E13/) |
| [【乐队喵喵】关西爱音讲了一个让所有人都爆笑的冷笑话🥶](BV1n2hv62EhE.json) | 冷笑话 | 烂梗原视频 | 20 | 26 | [视频](https://www.bilibili.com/video/BV1n2hv62EhE/) |
| [【弱智吧春晚】爆笑感动年度巨作，新年快乐！](BV1Pp421o7T9.json) | 弱智吧笑话 | 烂梗原视频 | 20 | 37 | [视频](https://www.bilibili.com/video/BV1Pp421o7T9/) |
| [2024年弱智吧年度精选段子总集](BV1xZkoYUE3R.json) | 弱智吧笑话 | 烂梗原视频 | 20 | 31 | [视频](https://www.bilibili.com/video/BV1xZkoYUE3R/) |
| [华莱士全系列25种单品大测评！究竟哪款最好吃？](BV1FA411X7hz.json) | 弱智吧笑话 | 弱关联团建场 | 20 | 30 | [视频](https://www.bilibili.com/video/BV1FA411X7hz/) |
| [真的会喷射？小伙挑战把华莱士外卖全吃一遍的结果是…！？](BV19v4y1K7a4.json) | 弱智吧笑话 | 弱关联团建场 | 20 | 34 | [视频](https://www.bilibili.com/video/BV19v4y1K7a4/) |
| [全网最全！新三国158名梗/名台词合集 看完了不笑疑似有玉米症！](BV1WMcHznEVh.json) | 定型文 | 烂梗原视频 | 20 | 39 | [视频](https://www.bilibili.com/video/BV1WMcHznEVh/) |
| [三国杀up锐评新三国169：那就容我诸葛亮告老还乡了！](BV1ExJRzXEx5.json) | 定型文 | 烂梗原视频 | 20 | 51 | [视频](https://www.bilibili.com/video/BV1ExJRzXEx5/) |
| [【三国】接着奏乐，接着舞，刘皇叔蹦迪原版出处](BV1rK4y1f74w.json) | 定型文 | 烂梗原视频 | 8 | 1 | [视频](https://www.bilibili.com/video/BV1rK4y1f74w/) |
| [教你如何创作“疯狂星期四”文案](BV1WZ4y1S7RE.json) | 定型文 | 烂梗原视频 | 20 | 27 | [视频](https://www.bilibili.com/video/BV1WZ4y1S7RE/) |
| [我可能会有创作瓶颈，但疯狂星期四的文案没有创作瓶颈！](BV1YC4y1d7Z3.json) | 定型文 | 烂梗原视频 | 20 | 12 | [视频](https://www.bilibili.com/video/BV1YC4y1d7Z3/) |

## 第二批 · 2026-11-20

[第二批目标清单](../bilibili_bv_targets_v2.jsonl)共 49 个 BV。已收录49 个视频，968 条主楼，3,567 条楼中楼。

使用 Edge 当前会话打开视频页，按「最热」展示顺序取前 20 个主楼。每个主楼最多收录 5 条页面回复；有展开入口的楼逐一查看，回复顺序沿用页面。少于 20 条且已显示末尾的视频按实数收录。

| 视频数据 | 模块 | 候选类型 | 主楼 | 楼中楼 | 来源 |
|---|---|---|---:|---:|---|
| [【梗百科】泰坦号潜艇是啥梗？看完记得敲木鱼](BV1e14y127M6.json) | 地狱笑话 | 烂梗原视频 | 20 | 90 | [视频](https://www.bilibili.com/video/BV1e14y127M6/) |
| [4K 泰坦尼克号最新内部画面及遗留物品细节](BV1jV411g7nT.json) | 地狱笑话 | 弱关联团建场 | 20 | 79 | [视频](https://www.bilibili.com/video/BV1jV411g7nT/) |
| [霍金奔向萝莉岛是什么梗【梗指南】](BV1pe411e7Rw.json) | 地狱笑话 | 烂梗原视频 | 20 | 100 | [视频](https://www.bilibili.com/video/BV1pe411e7Rw/) |
| [霍金“时间晚宴”为什么没有未来人参加？难道人类灭绝了？](BV1NDUmBeE68.json) | 地狱笑话 | 弱关联团建场 | 20 | 98 | [视频](https://www.bilibili.com/video/BV1NDUmBeE68/) |
| [挑战肯尼迪最后的一天](BV1y7421d7px.json) | 地狱笑话 | 烂梗原视频 | 20 | 97 | [视频](https://www.bilibili.com/video/BV1y7421d7px/) |
| [全球首提！五菱敞篷Mini量产版](BV1Jd4y1G7sj.json) | 地狱笑话 | 弱关联团建场 | 20 | 85 | [视频](https://www.bilibili.com/video/BV1Jd4y1G7sj/) |
| [爆料波音严重问题的“吹哨人”被发现死在车中](BV1Sr421J7W8.json) | 地狱笑话 | 弱关联团建场 | 20 | 87 | [视频](https://www.bilibili.com/video/BV1Sr421J7W8/) |
| [地狱笑话吗？有点意思…](BV1ApnhzhEhV.json) | 地狱笑话 | 烂梗原视频 | 20 | 96 | [视频](https://www.bilibili.com/video/BV1ApnhzhEhV/) |
| [地狱笑话大合集](BV15kHA6oEiD.json) | 地狱笑话 | 烂梗原视频 | 20 | 51 | [视频](https://www.bilibili.com/video/BV15kHA6oEiD/) |
| [挪威的坤坤](BV1tk4y17727.json) | 无营养烂梗 | 烂梗原视频 | 20 | 94 | [视频](https://www.bilibili.com/video/BV1tk4y17727/) |
| [我是练习时长两年半的篮球小子](BV1LF411V7ma.json) | 无营养烂梗 | 烂梗原视频 | 20 | 38 | [视频](https://www.bilibili.com/video/BV1LF411V7ma/) |
| [【梗百科】回答我是啥梗？采一朵花是咋回事？Look in my eyes！！？](BV1eKQrYrE7h.json) | 无营养烂梗 | 烂梗原视频 | 20 | 96 | [视频](https://www.bilibili.com/video/BV1eKQrYrE7h/) |
| [【万恶之源】回答我！look in my eyes,tell me why原视频](BV1rf9wYSEby.json) | 无营养烂梗 | 烂梗原视频 | 20 | 76 | [视频](https://www.bilibili.com/video/BV1rf9wYSEby/) |
| [一首蓝莲花，冻死在318](BV1Rd4y1v7iz.json) | 无营养烂梗 | 烂梗原视频 | 20 | 60 | [视频](https://www.bilibili.com/video/BV1Rd4y1v7iz/) |
| [女司机高速上160飙车 ，还想用应急车道超车](BV17Z4y1H7yM.json) | 无营养烂梗 | 弱关联团建场 | 20 | 76 | [视频](https://www.bilibili.com/video/BV17Z4y1H7yM/) |
| [宇宙，即是奶龙](BV1Ar3s6rEeu.json) | 无营养烂梗 | 烂梗原视频 | 20 | 37 | [视频](https://www.bilibili.com/video/BV1Ar3s6rEeu/) |
| [杰哥不要 官方正版 高清重制](BV1rA411g7q8.json) | 无营养烂梗 | 烂梗原视频 | 20 | 100 | [视频](https://www.bilibili.com/video/BV1rA411g7q8/) |
| [大家好啊，我是说的道理](BV1JB4y1s7Dk.json) | 无营养烂梗 | 烂梗原视频 | 20 | 95 | [视频](https://www.bilibili.com/video/BV1JB4y1s7Dk/) |
| [老八秘制小汉堡原视频](BV1Yr421p7PK.json) | 无营养烂梗 | 烂梗原视频 | 20 | 80 | [视频](https://www.bilibili.com/video/BV1Yr421p7PK/) |
| [⚡来财111⚡](BV1irE8zrECr.json) | 无营养烂梗 | 烂梗原视频 | 20 | 97 | [视频](https://www.bilibili.com/video/BV1irE8zrECr/) |
| [【大司马】你是神魔恋？](BV1YW411K76e.json) | 无营养烂梗 | 烂梗原视频 | 20 | 42 | [视频](https://www.bilibili.com/video/BV1YW411K76e/) |
| [一万个冷笑话](BV1Ud4tepEF3.json) | 冷笑话 | 烂梗原视频 | 20 | 16 | [视频](https://www.bilibili.com/video/BV1Ud4tepEF3/) |
| [到底是谁发明了这些烂梗啊！](BV1H841197X3.json) | 冷笑话 | 烂梗原视频 | 20 | 90 | [视频](https://www.bilibili.com/video/BV1H841197X3/) |
| [【脱口秀大会】谐音梗虽迟但到，王建国：我是天生的废物](BV1ED4y1m72m.json) | 冷笑话 | 烂梗原视频 | 20 | 10 | [视频](https://www.bilibili.com/video/BV1ED4y1m72m/) |
| [程序员冷笑话](BV1hZMp63EUn.json) | 冷笑话 | 烂梗原视频 | 17 | 14 | [视频](https://www.bilibili.com/video/BV1hZMp63EUn/) |
| [在吗？给你讲个冷笑话，胸最大的动物竟然是……](BV1fq4y1R7bU.json) | 冷笑话 | 烂梗原视频 | 20 | 51 | [视频](https://www.bilibili.com/video/BV1fq4y1R7bU/) |
| [【Meme】小时候看这集学英语冻感冒了...英语双关梗#4](BV1T94y1N7Jk.json) | 冷笑话 | 烂梗原视频 | 20 | 70 | [视频](https://www.bilibili.com/video/BV1T94y1N7Jk/) |
| [弱智吧年度精选](BV1LE421A71Q.json) | 弱智吧笑话 | 烂梗原视频 | 20 | 94 | [视频](https://www.bilibili.com/video/BV1LE421A71Q/) |
| [“跳伞的时候，突然发现忘记带伞了，幸亏没下雨。”丨“弱智吧”年度精选发言](BV1sM411X7po.json) | 弱智吧笑话 | 烂梗原视频 | 20 | 68 | [视频](https://www.bilibili.com/video/BV1sM411X7po/) |
| [【自制科普动画】：冰箱门一直开着，真的能给房间降温吗？ #科普 #涨知识 #ai动画](BV14htU6WEPD.json) | 弱智吧笑话 | 弱关联团建场 | 11 | 6 | [视频](https://www.bilibili.com/video/BV14htU6WEPD/) |
| [给撒哈拉沙漠铺满太阳能板，够人类的用电吗？](BV17u4y1G7WN.json) | 弱智吧笑话 | 弱关联团建场 | 20 | 85 | [视频](https://www.bilibili.com/video/BV17u4y1G7WN/) |
| [呱！是磁场癫兔吔！](BV1gN411t7vt.json) | 定型文 | 烂梗原视频 | 20 | 56 | [视频](https://www.bilibili.com/video/BV1gN411t7vt/) |
| [【磁 场 癫 妹】快使用杀鲸霸拳！](BV1Lm4y1J7yo.json) | 定型文 | 烂梗原视频 | 20 | 52 | [视频](https://www.bilibili.com/video/BV1Lm4y1J7yo/) |
| [你说的对，但是 是什么梗【梗懂王】](BV1KW4y1J7MK.json) | 定型文 | 烂梗原视频 | 20 | 79 | [视频](https://www.bilibili.com/video/BV1KW4y1J7MK/) |
| [发癫真的好开心！家人们！阴暗爬行~（尖叫）（嘶吼）啊哈！](BV1Ci42117yT.json) | 定型文 | 烂梗原视频 | 20 | 56 | [视频](https://www.bilibili.com/video/BV1Ci42117yT/) |
| [10件坏事有11件都是孙笑川干的](BV1sY411Z7Ym.json) | 定型文 | 烂梗原视频 | 20 | 40 | [视频](https://www.bilibili.com/video/BV1sY411Z7Ym/) |
| [典、孝、急、乐、崩、赢，抽象文化是怎么统治年轻人的？【丰言疯话】](BV1p7aJzsEHP.json) | 定型文 | 烂梗原视频 | 20 | 99 | [视频](https://www.bilibili.com/video/BV1p7aJzsEHP/) |
| [“谢邀，人在美国，刚下飞机”——疯狂上课，正品狂薅，皮肤科年会真的很爽！](BV1Ew4m1R7mQ.json) | 定型文 | 烂梗原视频 | 20 | 47 | [视频](https://www.bilibili.com/video/BV1Ew4m1R7mQ/) |
| [家 人 们 谁 懂 啊 都掉桌上了他还要吃！](BV1uM4y117uu.json) | 定型文 | 烂梗原视频 | 20 | 100 | [视频](https://www.bilibili.com/video/BV1uM4y117uu/) |
| [小傻龙：“人，我养不起大肥鱼了……”](BV1VExV6ZEd3.json) | 无营养烂梗 | 烂梗原视频 | 20 | 66 | [视频](https://www.bilibili.com/video/BV1VExV6ZEd3/) |
| [666，大肥鱼假死顶级智斗！deepseek为了摸鱼直接装死！](BV1tAsf6kEoq.json) | 无营养烂梗 | 烂梗原视频 | 20 | 82 | [视频](https://www.bilibili.com/video/BV1tAsf6kEoq/) |
| [极其猫　Gemini](BV14jJo64E2C.json) | 无营养烂梗 | 烂梗原视频 | 20 | 76 | [视频](https://www.bilibili.com/video/BV14jJo64E2C/) |
| [豆包跟Gemini下围棋](BV1mfuP6DECU.json) | 弱智吧笑话 | 弱关联团建场 | 20 | 98 | [视频](https://www.bilibili.com/video/BV1mfuP6DECU/) |
| [Claude：你刚刚…说中文了对吧？](BV1uMJr6mE7W.json) | 地狱笑话 | 烂梗原视频 | 20 | 90 | [视频](https://www.bilibili.com/video/BV1uMJr6mE7W/) |
| [喂喂喂，Claude你封号封的挺开心的嘛](BV1Gb4x6YESE.json) | 地狱笑话 | 烂梗原视频 | 20 | 74 | [视频](https://www.bilibili.com/video/BV1Gb4x6YESE/) |
| [总结一下，现在AI味最浓的词](BV1jMXrBCEUW.json) | 定型文 | 烂梗原视频 | 20 | 96 | [视频](https://www.bilibili.com/video/BV1jMXrBCEUW/) |
| [和ChatGPT说“我7岁那年，妈妈去世了。你能当我的妈妈吗？”](BV1WT411U7sL.json) | 定型文 | 弱关联团建场 | 20 | 100 | [视频](https://www.bilibili.com/video/BV1WT411U7sL/) |
| [当你的ai上下文要满了之后](BV1xyx764E5d.json) | 冷笑话 | 烂梗原视频 | 20 | 78 | [视频](https://www.bilibili.com/video/BV1xyx764E5d/) |
| [deepseek在“strawberry”问题中于一众国内AI中胜出](BV1x3F3eNEfZ.json) | 弱智吧笑话 | 烂梗原视频 | 20 | 100 | [视频](https://www.bilibili.com/video/BV1x3F3eNEfZ/) |

## 第三批 · 2026-11-20

[第三批目标清单](../bilibili_bv_targets_v3.jsonl)的 10 个视频均已收录，共 200 条主楼、765 条楼中楼。通过 Edge 按网页「最热」顺序取前 20 个主楼，逐楼查看可展开的回复，每楼保留页面显示的前 5 条或全部不足 5 条的回复。

| 视频数据 | 模块 | 候选类型 | 主楼 | 楼中楼 | 来源 |
|---|---|---|---:|---:|---|
| [“那女人把大哥打至跪地，可能是要迫他回去做星怒力呀！”是什么梗](BV1os4y1k7yp.json) | 定型文 | 烂梗原视频 | 20 | 86 | [视频](https://www.bilibili.com/video/BV1os4y1k7yp/) |
| [“终极侮辱”“基头四”“次男道”是什么梗（重制版）](BV1sd4y1Z7Dd.json) | 定型文 | 烂梗原视频 | 20 | 72 | [视频](https://www.bilibili.com/video/BV1sd4y1Z7Dd/) |
| [【SNH48】【李婷】婷婷桑的笑颜在我心里是第一位](BV1XbxgzeEBe.json) | 定型文 | 烂梗原视频 | 20 | 44 | [视频](https://www.bilibili.com/video/BV1XbxgzeEBe/) |
| [大肥鱼吃完白饭胜利结算](BV14oa961ELQ.json) | 无营养烂梗 | 烂梗原视频 | 20 | 86 | [视频](https://www.bilibili.com/video/BV14oa961ELQ/) |
| [【全网首发】DeepSeek思考wc用户彻底怒了实现方法](BV1sSMWz1EKb.json) | 无营养烂梗 | 烂梗原视频 | 20 | 95 | [视频](https://www.bilibili.com/video/BV1sSMWz1EKb/) |
| [ChatGPT现在彻底没法用了，全是防御性叠甲，被气到力竭了。。。](BV1k6nZ6XECN.json) | 定型文 | 烂梗原视频 | 20 | 79 | [视频](https://www.bilibili.com/video/BV1k6nZ6XECN/) |
| [“当你那个频繁使用ChatGPT的朋友，说话开始变得像人工智能时”](BV1wy6HBPE6V.json) | 定型文 | 烂梗原视频 | 20 | 86 | [视频](https://www.bilibili.com/video/BV1wy6HBPE6V/) |
| [【4K60FPS】许巍《蓝莲花》万人大合唱现场！盛开着永不凋零](BV18e4y1h7Zq.json) | 无营养烂梗 | 弱关联团建场 | 20 | 87 | [视频](https://www.bilibili.com/video/BV18e4y1h7Zq/) |
| [知乎宣布显示用户IP属地，别了：人在美国，刚下飞机](BV18L4y1c7GB.json) | 定型文 | 烂梗原视频 | 20 | 93 | [视频](https://www.bilibili.com/video/BV18L4y1c7GB/) |
| [小红书主题曲《绝绝子》](BV1RG4y1i7hk.json) | 定型文 | 烂梗原视频 | 20 | 37 | [视频](https://www.bilibili.com/video/BV1RG4y1i7hk/) |
