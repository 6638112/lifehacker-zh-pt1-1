# 用总统普林科预测选举结果

> 原文:[https://life hacker . com/forecast-election-results-with-presidential-plinko-1845313040](https://lifehacker.com/forecast-election-results-with-presidential-plinko-1845313040)

你看到《纽约时报》的“ [”选举针](https://www.nytimes.com/2020/02/03/upshot/needle-iowa-caucuses-faq.html) ”，你就焦虑了。你读了 [FiveThirtyEight](https://fivethirtyeight.com) ，你想知道你的候选人怎么会在选举前以一些看似可观的“点数”或民调领先后落败。

Watch

欢迎来到广阔的不确定性世界，当浏览统计数据、概率和纯粹的猜测时，许多人——包括我自己——都倾向于不相信这个世界。基于轮询的预测可以同时为真和不为真；是的，从理论上讲，你的候选人可能在民意调查中领先于T2，但最终还是会失败，因为民意调查没有准确地捕捉到它想要代表的人民的意愿。这个叫做“误差幅度”的小东西也很重要，尽管我们经常假装它不存在。

为了帮助我们更好地理解这一点，西北大学计算机科学助理教授马修·凯设计了一个相当聪明的方法来展示不确定性是如何影响民调数据的。

他用那个经典的*价格是对的*游戏、 [普林科](http://presidential-plinko.com) 来代表预测仍然可以产生这样或那样的结果。这完全取决于芯片——或虚拟的普林科球——如何下落。正如凯所描述的:

“简而言之，我用缩放和移位的二项式分布来近似每个预测者的预测分布，这最终决定了每个董事会的高度。然后，我通过棋盘确定可能导致最终预测分布的合理路径，最终预测分布显示为 [分位数点图](https://mucollective.northwestern.edu/project/when-ish-is-my-bus) 。因此，虽然输出看起来是随机的，但最终分布正是预测者公布的分布，精确到点状图的分辨率。方法的全部细节和源代码在Github库 中的 [。”](https://github.com/mjskay/election-galton-board)

这一切都很好，但我发现自己在凯的 [普林科游戏](http://presidential-plinko.com) 中一球接一球地掉球——你也可以在他的网站上为自己做这些。你可以选择丢下一个球或者让它们都掉下来。

我认为前者是你想走的路线，如果你把你的单个虚拟球概括为代表选举，无论它如何落地都是我们都会得到的结果。剧透:你的候选人可能不会赢，但这就是这个练习的全部意义。概率是一门科学，不是时光机。还记得2016年吗？

至于前面提到的我们很多人从《纽约时报》中熟悉的“针”，当人们了解它在做什么时，它是衡量对选举*的情绪的有用工具。*凯认为，使用针的，却让人们更容易曲解时代*’*贵族的做法。

“我认为针做对了一件事，又做错了一件事。正确的是，这种动画可以帮助人们体验不确定性。
这让可视化更强大，不确定性更难忽略。这种视觉化让人们焦虑，因为他们对自己关心的事情不确定。但是如果你对自己关心的事情不确定，*你应该感到焦虑，”*他写道。

"然而，我认为针也是一个*确定性识解错误的受害者* :
许多人更容易将针的机制与一些确定性的测量联系起来，而不是一个不确定的量。可以理解的是，这些人认为指针的快速移动反映了预测本身也在快速变化。”

现在，我们什么时候能得到由一杆进洞模拟的选举预测？这就是我想知道的。