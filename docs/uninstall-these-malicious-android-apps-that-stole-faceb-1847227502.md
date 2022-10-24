# 卸载这些窃取脸书密码的恶意安卓应用

> 原文:[https://life hacker . com/uninstall-these-malicious-Android-apps-that-skeet-faceb-1847227502](https://lifehacker.com/uninstall-these-malicious-android-apps-that-stole-faceb-1847227502)

来自Web博士的研究人员发现，有九个应用程序的总下载量超过580万次，这些应用程序使用真正的脸书登录页面偷偷窃取用户的脸书密码。截至发稿时，谷歌已经禁止了该开发者，并从Play Store中移除了这九款应用，但如果你已经下载了其中任何一款，是时候更改密码了。

Watch

## 应用程序是如何窃取数据的？

据网络博士 的 [研究人员称，开发者chikumburahamilton开发了功能齐全的应用程序，用于照片编辑、锻炼、星座和垃圾清理(等等)。一段时间后，这些应用程序会提示用户使用脸书登录，以解锁应用程序的全部功能。](https://news.drweb.com/show/?i=14244&lng=en)

当用户这样做时，应用程序将启动他们自己的C&C服务器(一个由开发者控制的命令控制服务器，用于复制和存储网页数据)。从C&C服务器收到设置后，应用程序加载，然后加载合法的脸书登录页面。

然后，该应用程序将从C&C服务器接收的JavaScript加载到脸书登录页面(JavaScript代码是通用的，可以在任何点插入，甚至当用户只需点击文本字段时)。这段Javascript代码随后被用来复制用户名和密码。

然后，JavaScript将复制的数据传递给应用程序，应用程序又将数据传递给应用程序的C&C服务器，并保存在那里。一旦用户登录该应用程序，该应用程序还会从当前授权会话中窃取cookiess，这些cookie会被发送给网络犯罪分子。

在这种情况下，应用程序只使用脸书的正版登录页面。但是由于JavaScript和C&C服务器的工作方式，它们可以很容易地对任何需要你登录的服务做到这一点。

## 你能做些什么呢？

你应该做的第一件事是检查你是否运行了这九个应用中的一个:

1.  PIP照片
2.  处理照片
3.  垃圾清洁机
4.  英威尔健身
5.  星座日报
6.  应用程序锁定保持
7.  Lockit主机
8.  星座圆周率
9.  应用锁定管理器

如果您安装了这些应用程序，第一步是卸载该应用程序。

然后，如果你用脸书登录了app，你需要立即 [重置你的密码](https://www.facebook.com/help/213395615347144) 。

接下来，保持警惕。使用类似 [Malwarebytes](https://play.google.com/store/apps/details?id=org.malwarebytes.antimalware) 的可信反病毒应用程序来检测带有恶意代码的应用程序。如果可能的话，避免将脸书等第三方服务与从Play Store下载的随机应用程序连接。由于Play Store的工作方式，开发者很容易重新输入和重新提交应用程序，即使它们已经被删除(开发者许可证只需25美元)。

最后，为任何允许的站点打开 [双因素认证](https://lifehacker.com/no-one-knows-about-two-factor-authentication-and-privat-1838913065) ，并将其与 [密码管理器](https://lifehacker.com/how-to-get-started-with-a-password-manager-1846890484) 配对。这将帮助您安全地生成和存储长密码。即使网站泄露泄露了您的密码，双因素身份验证也会保护您免受黑客攻击。

[]