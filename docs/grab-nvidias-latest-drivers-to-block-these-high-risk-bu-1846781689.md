# 获取Nvidia的最新驱动程序来阻止这些高风险的错误

> 原文:[https://life hacker . com/grab-nvidias-latest-drivers-to-block-these-high-risk-bu-1846781689](https://lifehacker.com/grab-nvidias-latest-drivers-to-block-these-high-risk-bu-1846781689)

使用Nvidia显卡的Windows用户应该立即更新他们的显示驱动程序，以修补几个有问题的(可能导致崩溃的)错误。

英伟达近期 [安全公告](https://nvidia.custhelp.com/app/answers/detail/a_id/5172) 概述十三大漏洞；我影响了英伟达的显示驱动程序，其中八个出现在英伟达的vGPU软件中。虽然所有13个都是严重的威胁，但五个显示驱动程序错误对普通用户构成了最大的风险,因为它们会影响所有装有Nvidia GPU的Windows和Linux电脑。

Watch

*   [**CVE-2021-1074**](https://nvd.nist.gov/vuln/detail/CVE-2021-1074):7.5[CVSS](https://nvd.nist.gov/vuln-metrics/cvss)评级。允许本地攻击者物理访问您的电脑来操纵Nvidia安装程序。攻击者可以利用这个漏洞运行恶意代码，窃取您的数据，或者执行拒绝服务攻击。
*   [**CVE-2021-1075**](https://nvd.nist.gov/vuln/detail/CVE-2021-1075)T5】:7.3 CVSS评级。Nvidia的Windows显示驱动程序中的一个内存问题，使您的电脑容易受到各种恶意软件攻击和远程访问。
*   [**CVE-2021-1076**](https://nvd.nist.gov/vuln/detail/CVE-2021-1076)T5】:6.6 CVSS评分。Windows和Linux驱动程序中的一个问题，可能会让黑客访问、窃取和/或破坏您电脑的数据并执行拒绝服务攻击。 
*   [**CVE-2021-1077**](https://nvd.nist.gov/vuln/detail/CVE-2021-1077)T5】:6.6 CVSS评分。【Windows和Linux驱动程序中的另一个问题，可用于发起拒绝服务攻击。 
*   [**CVE-2021-1078**](https://nvd.nist.gov/vuln/detail/CVE-2021-1078)T5】:5.5 CVSS评分。Windows驱动程序中的一个问题可能会导致电脑突然崩溃。 

Nvidia上周推出了一个紧急补丁来修复这些漏洞。您可以通过GeForce experience app，下载更新的驱动程序，或者直接从 [Nvidia的下载页面](https://www.nvidia.com/Download/index.aspx) 获取安装文件。

至于八个vGPU软件错误，四个是高严重性的，CVSS等级为7.8，其他的CVSS威胁等级从5.1到7.5不等。它们允许几种可能的结果，例如特权提升攻击、任意代码执行、信息泄露、数据篡改、拒绝服务攻击、内存损坏等等。这些也是严重的威胁，但只影响那些授权Nvidia的vGPU软件。

[ [TechRadar](https://www.techradar.com/news/nvidia-warns-gamers-to-update-their-gpu-drivers-right-now-due-to-severe-security-problems)