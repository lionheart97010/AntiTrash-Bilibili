
# BilibiliAntiDemo

摆脱睿智弹幕从我做起。直接下载并导入本表单即可。导入之前请先备份自己的屏蔽列表。

如果导入失败或导入后显示乱码，请手动编辑表单并另存为编码Unicode。

# Users

每个被封禁的用户都有写封禁原因备注。（如果不能导入请用记事本编辑表单手动删除备注行。文件编码为Unicode或UTF-8）

每个由于刷屏而被封禁的用户都在*非弹幕狂欢位置*刷了*不止一次*弹幕。所以，一律鲨掉没有复活环节。

# Text

如果有三条或以上比较相似的文本屏蔽规则，则会将这些条目移动至正则表达式屏蔽列表。

# RegularExpression

由于bilibili的正则表达式不是正常的正则表达式匹配模式，正则表达式的屏蔽范围可能比预想的要宽。
（只要能匹配出某条弹幕的一部分，即使某些特征，如该匹配必须在字符串头部，不符合正则表达式要求，也可能会被匹配并屏蔽（待测试）。而且稍微长一点的表达式就会被拒绝同步，即使能通过正则表达式测试且少于明示的要求50字符。）

TODO：日期的同步规则。之前写的日期同步规则都不能同步。如果实在不行我会考虑将本来能在一个表达式内表示的几个连接符可能性拆成若干个单独的表达式。

目前能够想到的日期格式有：

2019年6月28日

2019-06-28

2019/06/28

2019、06、28

2019\06\28

2019 06 28

二〇一九年六月二十八日

这几种可能。欢迎补充。


Eng.Ver.

Maybe out of date.


# BilibiliAntiDemo

Get rid of Fxxking annoying meaningless barrages.

You can delete all your items in your banlist. But before you do that,always remember to BACKUP.

# Users

There are comments to tell why they've been banned below every users. Always remember to save as Unicode.

# Text

If there are three or more similar items in "text.xml" , I may move them into "regularExpression.xml".

# RegularExpression

Rules for blocking:

Dates

Meaningless repeating(single character)

There're some hidden rules in the website. If some of the clauses cannot upload to the server, please mark it here. 

TODO:blocking those fxxking dates.
