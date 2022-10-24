# MoCA如何让我的家庭网络比网状Wifi更快

> 原文:[https://life hacker . com/how-moca-make-my-home-network-fast-than-mesh-wifi-1846927535](https://lifehacker.com/how-moca-made-my-home-network-faster-than-mesh-wifi-1846927535)

我喜欢摆弄wifi，但当我在一个新的地方——房子、公寓或任何地方——构建网络主干时，我倾向于尽可能多地使用有线网络。无线网桥和三频网格/扩展器设置非常方便，但我一直很欣赏以太网电缆的稳定性和速度。

Watch

当我最近主动帮助我的朋友安装有线主干网时，我遇到了一个有趣的问题:他们的房间都没有以太网连接。这并没有让我感到惊讶，因为这往往是一个更现代的便利，而老房子根本没有。然而，它*是*有点烦人，特别是当你没有很多时间来启动和运行一些东西，并且你不是真的想自己在墙上打洞和穿电缆的时候。(我做过；他们只是不太热衷于花这么长时间，尤其是当他们可以使用wifi并结束一天的工作时。)

这个问题的巧妙解决方案？MoCA，即“同轴电缆多媒体”我很早就知道这项技术，但直到现在才有时间(或需要)去玩它。我朋友家的每个房间都用同轴电缆布线，这是一个理想的解决方案。我可以用MoCA来代替以太网——从技术上来说，MoCA 2.0使*的速度达到了千兆位，对于我朋友的大约400Mbps的互联网计划来说应该绰绰有余(即使它没有*那么快)。不像我，他们不会在自己的生活空间里发送一堆文件，所以最大化速度也不是主要问题。**

我拿到了两包的[TrendNET TMO-311 c2k](https://www.trendnet.com/support/support-detail.asp?prod=105_TMO-311C2K)适配器，开始工作，总共花了五分钟，因为我在装傻。毫不奇怪，把MoCA适配器插到房子周围的各种同轴端口上完全没有实现*。没有信号。如果我以前对MoCA大惊小怪，这不会是一个大惊喜。但从以太网土地来后，我只是期望从墙出来的一切都连接在一起。当涉及到同轴电缆连接时，就不那么重要了。*

*一部分原因是因为在房子周围安装电缆的本质。与以太网不同，在以太网中，你用一个相对便宜的交换机将16根不同的电缆连接在一起，每个连接仍然可以实现理论上的最高速度1Gbps，连接八根不同的同轴电缆将导致衰减或信号损失，这是你需要如何 [分割信号](https://support.channelmaster.com/hc/en-us/articles/200383715-How-Much-Signal-Do-I-Lose-Going-Through-A-Splitter-CM-3212HD-CM-3213HD-) 的结果。当你只是想用一根电缆连接两个房间时，这可能并不重要，但如果你想让*的每个*房间都有稳固的同轴连接，你至少需要一个放大器。*

*这只是说，当我发现我朋友家周围的许多同轴电缆根本没有连接到任何东西时，我并不太惊讶。我最终能够通过追踪房子外面的电线来证实这一点，在那里我找到了所有断开的电缆的终端。然后我去拿起 [其中一个](https://smile.amazon.com/gp/product/B076DP1534?asc_campaign=InlineText&asc_refurl=https://lifehacker.com/how-moca-made-my-home-network-faster-than-mesh-wifi-1846927535&asc_source=&psc=1&tag=kinjalifehackerlink-20) 来测试哪根电缆连接到房子的哪个房间:*

*我还拿了一个 [MoCA PoE滤镜](https://smile.amazon.com/gp/product/B00DC8IEE6?asc_campaign=InlineText&asc_refurl=https://lifehacker.com/how-moca-made-my-home-network-faster-than-mesh-wifi-1846927535&asc_source=&psc=1&tag=kinjalifehackerlink-20) 和一个单独的 [高质量分路器](https://smile.amazon.com/gp/product/B0113JAN8K?asc_campaign=InlineText&asc_refurl=https://lifehacker.com/how-moca-made-my-home-network-faster-than-mesh-wifi-1846927535&asc_source=&psc=1&tag=kinjalifehackerlink-20) 来给房子提供尽可能好的信号。您可能已经知道，我的目标是使用MoCA通过基于同轴电缆的以太网连接楼下的房间和楼上的房间。因为楼上的房间是房子的电缆调制解调器所在的地方，所以我可以:*

*   *在楼下设置一个无线接入点。通过MoCA将它连接到楼上的路由器，以创建两个具有高速有线主干的wifi“气泡”。*
*   *还要将楼上的路由器连接到电缆调制解调器。*
*   *将电缆调制解调器连接到楼上的MoCA适配器，路由器也将连接到该适配器(通过以太网)。*

*换句话说，电缆连接将承担家里所有繁重的数据传输工作，由于MoCA适配器，我可以连接基于同轴电缆的设备(电缆调制解调器)和基于以太网的设备(其他任何设备)。*

*容易得很。我不只是油嘴滑舌；一旦我连接了PoE过滤器和分离器，连接了两个房间的电缆连接，MoCA适配器就亮了，让我知道他们可以看到彼此。五分钟后，我的网络启动并运行，这再简单不过了。房子的两层现在都有wifi，这是一个比我的朋友们以前处理的网格设置更快的解决方案。(尽管这可能很方便，但它并没有让我的朋友们像现在一样，在MoCA作为他们网络主干的情况下体验到最大的速度。)*

*我吗？我将把MoCA添加到我的网络武器库中的工具列表中。虽然我曾经有一种思维模式，“我们只要在每个地方都用以太网电缆连接起来，那就太棒了，”但如果能够将一个50美元的小适配器连接到房间现有的同轴电缆连接上，那就简单多了。当然，价格更高，但现在我不必为家里的电缆管理而烦恼了。我想知道我将如何处理过去几年一直随身携带的这条75英尺的Cat6以太网电缆。*

**更新于2022年3月2日，新增详细信息。**