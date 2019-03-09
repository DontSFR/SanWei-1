# 三味书屋图书商店后台
## 1. 根据bookId获取图书所有内容（简介、详情、评论）
* url地址：/getBookById
* 请求方式：post
* 参数：
```$xslt
bookId:ce703fd2-3e62-11e9-8f83-1c2b8518ea4c
```  
* 返回格式：
```$xslt
{
	"code": 200,
	"reason": null,
	"res": {
		"bookId": "ce703fd2-3e62-11e9-8f83-1c2b8518ea4c",
		"name": "巨人的陨落",
		"writer": "[英]肯·福莱特/于大卫",
		"publisher": "江苏凤凰文艺出版社",
		"date": "2016-5-1",
		"img": "https://img3.doubanio.com/view/subject/m/public/s28668834.jpg",
		"type": 1,
		"introduce": "在第一次世界大战的硝烟中，每一个迈向死亡的生命都在热烈地生长——威尔士的矿工少年、刚失恋的美国法律系大学生、穷困潦倒的俄国兄弟、富有英俊的英格兰伯爵，以及痴...",
		"grade": "8.9",
		"people": "42803",
		"price": "129.80",
		"no": "26698660",
		"detailUrl": "https://book.douban.com/subject/26698660/",
		"createTime": "2019-03-04 17:49:30.0",
		"updateTime": "2019-03-04 17:49:30.0",
		"detail": {
			"detailId": "3a6799b3-a2b5-4ab8-90f1-580e4667c2d7",
			"bookId": "ce703fd2-3e62-11e9-8f83-1c2b8518ea4c",
			"writer": "肯·福莱特\nKen\nFollett\n(1949\n-)，现象级畅销小说大师。1978年出版了处女作《风暴岛》，并于次年获得爱伦坡奖，声名鹊起，专职写作。2010年，荣登全球作家富豪榜上第5名。2013年，获得爱伦坡终身大师奖。他的小说出版前，都会请历史学家审读书稿，绝不容许出现任何史实错误。有出版人曾指出，肯·福莱特\n“没有一个饱受折磨的灵魂”，他愉快地承认了，“大家都在写内心的痛苦，可我总是觉得很开心”。他说：“很多作家只写能取悦他们自己的东西，并模模糊糊地希望这也能取悦别人。但我每写一页都在清醒地思考：读者会怎么想？读者觉得这真的会发生吗？读者关心这些吗？读者想要知道接下来会发生什么吗？我敬佩那些用文字和新奇结构进行文学实验的作家，但我从不这么玩。”\n作者官方网站：www.ken-follett.com",
			"content": "在第一次世界大战的硝烟中，每一个迈向死亡的生命都在热烈地生长——威尔士的矿工少年、刚失恋的美国法律系大学生、穷困潦倒的俄国兄弟、富有英俊的英格兰伯爵，以及痴情的德国特工… 从充满灰尘和危险的煤矿到闪闪发光的皇室宫殿，从代表着权力的走廊到爱恨纠缠的卧室，五个家族迥然不同又纠葛不断的命运逐渐揭晓，波澜壮阔地展现了一个我们自认为了解，但从未如此真切感受过的20世纪。",
			"catalog": " 序 成人礼\n Part 1 天地失色\n Part 2 巨人之战\n Part 3 世界重生\n · · · · · · (\n) \n",
			"createTime": "2019-03-05 19:49:53.0",
			"updateTime": "2019-03-05 19:49:53.0"
		},
		"comments": [{
			"commentId": "3ffcc935-4b38-4f7e-994b-c5d8e5a2a800",
			"bookId": "ce703fd2-3e62-11e9-8f83-1c2b8518ea4c",
			"person": "CHANTEY",
			"commentContent": "超级小说《巨人的陨落》征集超级好书评！",
			"commentDate": "2016-09-27 11:38",
			"comentGrade": null,
			"createTime": "2019-03-05 19:49:53.0",
			"updateTime": "2019-03-05 19:49:53.0"
		}]
	}
}
```