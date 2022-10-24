# 安装和更新所有Windows应用程序的最简单方法

> 原文:[https://life hacker . com/the-easy-ways-to-install-and-update-all-your-windows-1848805116](https://lifehacker.com/the-easiest-ways-to-install-and-update-all-your-windows-1848805116)

随着Windows 11的更新，微软的Windows Store实验终于获得了一些动力。但并不是每个应用都能在微软商店预览版上使用。如果您正在设置一台新的Windows PC，或者想要创建一个工作流来一键更新您的所有应用程序(不仅仅是Microsoft Store应用程序)，可以考虑一些有吸引力的第三方选项。

Watch

你可以使用一键安装工具，或者基于命令行的实用程序，这取决于你所提供的。

## 通过一键Ninite安装程序安装和更新应用程序

Ninite是一款流行的Windows应用安装程序。它已经存在了很长时间，受到了几家公司的信任，并且它提供了一个点击式可执行文件，可以安装和更新任何选择的应用程序。

进入 [Ninite网站](https://ninite.com/) ，选择想要安装的应用，下载安装程序。它将下载并安装选定的应用程序，仅此而已——没有插件，没有工具栏，没有快捷方式，什么都没有。以后，您可以重新启动相同的安装程序来更新已安装的应用程序。

## 使用Windows包管理器安装更多应用

微软给Windows带来了一个Linux风格的包管理器——并不是每个人都知道它。这是一个命令行实用程序，让您可以浏览、安装和更新超过3，000个应用程序——所有这些都只需一个命令，没有臃肿。

在开始这个过程之前，你需要确保你的Windows电脑已经安装了(如果你使用的是最新版本的Windows，你已经有了)。然后，启动命令提示符，输入“ **winget** ”您将看到所有可用命令的列表，以及您可以使用它们做什么。

例如，要安装Notepad++之类的应用程序，请输入以下命令进行搜索:

`winget search notepad++`

这将为您提供所有匹配应用程序的列表。看到要安装的app，看PowerShell ID。这是你实际安装应用程序所需要的。命令如下:

`winget install Notepad++.Notepad++`

按下Enter键后，Windows将下载并安装该应用程序。给安装者许可，你就可以开始了。想卸载，一个app？使用以下命令:

`winget uninstall Notepad++.Notepad++`

Windows包管理器也使更新应用程序变得容易。使用这个命令来一起更新所有应用程序:

`winget upgrade —all`

## 为Windows软件包管理器获得一个类似Ninite的GUI工具

现在，Windows包管理器很容易使用，但不是每个人都习惯命令行。别担心，您可以拥有自己的Windows应用程序，并且安装也很简单。只需使用 [Winstall](https://winstall.app/) ，一个免费的类似Ninite的GUI工具，让你从3000多个应用程序中选择安装。

就像Ninite一样，访问该网站，搜索一个应用程序，或从列表中选择该应用程序(或其中一个管理包)，并向下滚动到“获取包”部分。在这里，选择PowerShell或批处理选项，并单击**“复制到剪贴板**”来复制整个安装命令。

然后在PC上打开 **PowerShell** app，粘贴命令，按 **Enter** 键。应用程序将开始安装过程。如果任何应用程序需要权限，Windows会提示您。

## 使用RuckZuck保持应用程序更新

感兴趣的工具，将自动扫描和更新您所有安装的应用程序？看一看[RuckZuck](https://ruckzuck.tools/)T3。这是一个简单的应用程序，可以帮助您更新已安装的应用程序。它有一个超过300个流行的应用程序库，包括显卡驱动程序。 

打开应用程序，选择**更新应用程序**选项，你会看到一个可用应用程序更新列表。在这里，您可以选择安装所有应用程序更新，也可以选择单个应用程序。拉克扎克会处理剩下的事。