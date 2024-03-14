# HoYoShade-RePublish

[EN](Readme.md)|**简体中文**|[繁體中文](Readme.Chinese_Traditional.md)  

重新发行所有受到DMCA影响的旧版本HoYoShade和过时源码等。(当然是肯定会移除DMCA内容啦，想啥呢)  

> [!NOTE]
> 翻译并非100%准确，翻译工作主要基于OpenAI-GPT4T，谷歌翻译和本人的校对组成。 但即使如此，最终成品也难免会产生一定的问题。 如果你发现或者你认为这是一个问题，请提交issues以帮助HoYoShade改进。

请注意，Main分支仅仅只有Readme.md自述文件用于说明该仓库的一些信息，以及为本仓库各个分支进行一个目录归总和描述。  

## 〢 目录

- [**介绍**](#〢-介绍)
- [**为什么会有这个附属库?**](#〢-为什么会有这个附属库)
- [**仓库分支目录**](#〢-仓库分支目录)
- [**支持游戏列表**](#〢-支持游戏列表)
- [**来源**](#〢-来源)
- [**OpenHoYoShade和HoYoShade**](#〢-OpenHoYoShade和HoYoShade)
- [**如何安装?**](#〢-如何安装)
- [**鸣谢**](#〢-鸣谢)
- [**赞助**](#〢-赞助)
- [**联系我**](#〢-联系我)
- [**贡献者**](#〢-贡献者)

## 〢 介绍

该仓库是[HoYoShade](https://github.com/DuolaD/HoYoShade)的附属仓库。  

主要的目的是用于在移除受DMCA影响的内容后重新发行受DMCA影响的Release，以及对过时内容进行归档。  
请注意，重新发行受影响的Release更重要的意义在于提供参考资料用于第三者进行二次开发时用于参考，而并非在现阶段有更稳定的版本时仍然让你使用旧版。  

> [!NOTE]
> 请注意，重新发行的Releases版本号后缀均为'RePublish'。

HoYoShade是一个非官方Reshade，使其能在突破米哈游对于官方Reshade的封锁下正常用于所有可在PC端运行的米哈游游戏。

ReShade的工作原理是拦截CPU和GPU之间的通信，并修改渲染信息以达到提高图像质量的目的。HoYoShade集成了一些基于官方ReShade的开源项目(具体列表请查看[来源页面](#〢-来源))并对其进行修改，使其与PC上所有的米哈游游戏兼容，并制作一些有针对性的预设。未来，它将支持更多的米哈游游戏。

有关本仓库贡献者的信息，请访问[贡献者界面](#〢-贡献者)

## 〢 为什么会有这个附属库

自HoYoShade首个版本发行后，HoYoShade便受到了来自中国大陆地区视频博主的关注和赞助。在经过了一段时间后，便有博主提出将Pascal Gilcher团队的付费效果库集成在HoYoShade的Release中。直至V2.12.2 Stable版本后，我们收到了来自Pascal Gilcher团队的DMCA警告。  

在受到警告的第一时间后，HoYoShade便以最快的速度下架了所有版本Release的下载链接，并已将相关源码进行备份，并在第二天发布了不受DMCA警告影响的V2.013.0 Stable版本。  

在此，DuolaDStudio全体成员向Pascal Gilcher团队标示深深的歉意，并保证和承诺今后的任何一个HoYoShade的Release绝不会出现Pascal Gilcher团队中的内容。  

Pascal Gilcher团队是ReShade中非常知名的付费效果库开发团队，他们的每个付费效果库都具有很好的质量(例如：RTGI)。  
如果你想使用付费效果库或者是支持Pascal Gilcher团队的话，请[点击这里](https://www.patreon.com/mcflypg/posts)前往他们官方Patreon界面购买套餐后自行安装至HoYoShade。  

而该附属库存在的目的便是在去除Pascal Gilcher团队的内容后重新发行Releases，以便为第三者进行二次开发的时候可以提供具有一定价值的参考资料。  

## 〢 仓库分支目录

- **仓库分支目录**(本分支，用于本仓库各个分支进行一个目录归总和描述)
- [**V1.X.X-Outdated_Source**](https://github.com/DuolaD/HoYoShade-RePublish/tree/V1.X.X-Outdated_Source) (V1.X.X的过时程序源码文件等)
- [**V1.X.X-Final**](https://github.com/DuolaD/HoYoShade-RePublish/tree/V1.X.X-Final) (V1.X.X大版本最终框架(更多还是纪念意义*1))
- [**V2.X.X-Outdated_Source**](https://github.com/DuolaD/HoYoShade-RePublish/tree/V2.X.X-Outdated_Source) (V2.X.X的过时程序源码文件等)  

*1：在此特别感谢阿向菌|AXBro提供资金支持让V2.X.X版本顺利开发!感恩!  

## 〢 支持游戏列表

不同游戏版本的(Open)HoYoShade支持游戏列表和功能也会有有所不同，具体受支持游戏情况请查看各版本Releases界面描述。  
如果你什么都不懂，不想二次开发，只是想正常在米哈游系列游戏中使用ReShade,请访问[HoYoShade](https://github.com/DuolaD/HoYoShade)主仓库，在查看Readme.md文档后选择合适你的最新版Release下载即可。  

最新版本的[HoYoShade](https://github.com/DuolaD/HoYoShade)可以保证受支持的游戏和功能最多，同时稳定性高于本仓库任何一个RePublish版本。  

> [!NOTE]
> ·对于私服玩家来说，如果私服需要的对应客户端出现在支持的游戏列表中，则说明HoYoShade可以提供支持。  
> ·对于并未出现在支持游戏列表中的游戏，你可以自行尝试选择使用注入器中已支持的游戏/在开发者选项中选择自定义注入来尝试注入HoYoShade。

## 〢 来源

对于V1.X.X版本:  

| 名字 | 介绍 | 网址 |
| --- | --- | --- |
| **非官方ReShade** | ReShade 4.9.2 UnOfficial移除网络通信验证版本*1 | [官方仓库](https://github.com/crosire/reshade),[官方网站](https://reshade.me/) |
| **Crosire的ReShade注入器** | 这只是一个注入器 | [前往ReShade官方仓库查看源码](https://github.com/crosire/reshade/blob/main/tools/injector.cpp) |

*1:自ReShade Official V5.X.X版本开始,从官网上下载的'with full add-on support'安装程序内的ReShade32.dll和ReShade64.dll就已经移除了网络通信验证。而在此之前的ReShade Official所有安装包内的ReShade32.dll和ReShade64.dll均含有网络通信验证。  

网络通信验证会检测游戏在游戏具有高网络请求的时候自动禁用ReShade以防止反作弊检测到ReShade进而导致游戏账号出现封禁(来自ReShade官方的描述)，但这很显然不适用于MiHoYo/HoYoVerse旗下的游戏中。所以我们需要移除网络通信验证以让ReShade可以正常在MiHoYo/HoYoVerse旗下游戏运行。  

## 

对于V2.X.X版本:  

| 名字 | 介绍 | 网址 |
| --- | --- | --- |
| **ReShade官方** | Releases中的ReShade版本号会在5.9.2至6.0.1不等 | [官方仓库](https://github.com/crosire/reshade),[官方网站](https://reshade.me/) |
| **Crosire的ReShade注入器** | 这只是一个注入器 | [前往ReShade官方仓库查看源码](https://github.com/crosire/reshade/blob/main/tools/injector.cpp) |
| **Aria2** | 用于非强制版本检测器下载版本信息和最新Mod包 | [官方仓库](https://github.com/aria2/aria2),[官方网站](https://aria2.github.io/) |

请注意，基于Aria2开发的更新器于V2.0131.0 Stable版本中开始发行，这并不属于本仓库RePublish的范围之中。  

## 〢 OpenHoYoShade和HoYoShade

我们将会在每一个RePublish版本中发布HoYoShade RePublish包和OpenHoYoShade RePublish包。
不同版本中的(Open)HoYoShade功能和特性可能都有所不同，具体情况请查看各版本Releases界面描述。  

OpenHoYoShade为HoYoShade底层基本框架，它涵盖了使ReShade注入至全系米哈游旗下游戏的所有必要文件。  
OpenHoYoShade存储占用会比HoYoShade小, 但OpenHoYoShade并没有内置ReShade效果库，预设等，适用于想对HoYoShade进行二次开发的二次开发者。  

如果你只是想在MiHoYo/HoYoVerse游戏下使用ReShade，请下载HoYoShade。  
如果你想要开发一个可以在MiHoYo/HoYoVerse游戏下使用的ReShade，但是你又不想学习过多的东西，那么你可以选择下载OpenHoYoShade。  

要使 OpenHoYoShade 快速工作，您唯一需要做的就是将效果库和预设放在各自正确的位置。  
但如果你愿意，你可以进行进一步的开发，比如注入器、Reshade.ini构建器等等等等，甚至重新发行！（开源万岁！)  
(哦对了......在你重新发行文件时，确保你重新发行的文件遵守了BSD-3开源协议)  

当然了,如果你想要获得旧版注入程序/更多信息，请在[仓库分支目录](#〢-仓库分支目录)中前往对应的分类分支中下载文件。  

如果你还是不明白OpenHoYoShade和HoYoShade之间有什么不同，那么以下的图表也许可以很好的帮助你说明：

|  | OpenHoYoShade | HoYoShade |
| --- | --- | --- |
| **ReShade** | 有 | 有 |
| **使ReShade注入至全系米哈游旗下游戏的所有必要文件** | 有 | 有 |
| **程序源代码** | 有 | 没有 |
| **Reshade的效果库(包括插件)** | 没有(你需要自行准备) | 有 |
| **预设** | 没有(你需要自行准备) | 有 |
| **谁会需要他们？** | 二次开发者 | 普通游戏玩家 |

## 〢 如何安装

从[本仓库的发行页面](https://github.com/DuolaD/HoYoShade-RePublish/releases) 下载最新版本的HoYoShade RePublish。    

对于V1.X.X RePublish版本：  
-使用注入器启动注入程序，然后使用启动器启动游戏即可。  

对于V2.X.X RePublish版本：  
-使用注入器  
-将生成在模组根目录下的ReShade.ini复制至游戏进程根目录
-启动注入程序，然后使用启动器启动游戏即可。

## 〢 鸣谢
感谢以下合作伙伴的支持：  
| 名字 | 介绍 | 网址 |
| --- | --- | --- |
| **CY Team** | HoYoShade合作伙伴/微软企业存储计划提供/动态链接转静态链接解决方案 | [官方网站](https://www.cyteam.cn/) |
| **Cloudflare, Inc.** | V2.0131.0 Stable版本更新器域名托管和管理 | [官方网站](https://www.cloudflare.com/) |

## 〢 赞助

 **点击对应按钮来赞助HoYoShade**  
赞助的金额由你自行设定。

<div align="center"><p><span ><a href="https://patreon.com/DuolaD"><img src="https://img.shields.io/badge/Patreon-000000.svg?logo=patreon" /></a> <a href="https://www.paypal.com/paypalme/Dmou114514233"><img src="https://img.shields.io/badge/PayPal-003087.svg?logo=paypal" /></a> <a href="Readme.md-image/WechatDonateCode.JPG"><img src="https://img.shields.io/badge/微信支付-07C160.svg?logo=wechat&logoColor=white" /></a> <a href="Readme.md-image/AirPayDonateCode.png"><img src="https://img.shields.io/badge/支付宝-1677FF.svg?logo=alipay&logoColor=white" /> </span></p></a></div>

## 〢 联系我

> [!NOTE]
> ·如果你处于中国大陆地区，则某些联系方式可能不可用。结尾带星号标识'*'的联系方式可以保证在中国大陆地区使用，并且可以获得更快速的响应和支持。  
> ·如果你在使用此模组时有任何的问题，请先在本仓库创建一个issue。

 **点击对应按钮来联系我：**
  
<div align="center"><p><span ><a href="https://discordapp.com/users/960705009866137631"><img src="https://img.shields.io/badge/Discord-可用-5865F2.svg?logo=discord" /></a> <a href="https://www.douyin.com/user/MS4wLjABAAAAGUohNGixQiCHKSoHJy0Ae6WS3R7pMd7lSfi5O4A9zH7gdcEd4JEX787i-RFNH257"><img src="https://img.shields.io/badge/抖音*-可用-000000.svg?logo=tiktok" /></a> <a href="https://t.me/D_mou"><img src="https://img.shields.io/badge/Telegram-可用-26A5E4.svg?logo=telegram" /></a> <a href="https://qm.qq.com/q/njKy8OrUU8"><img src="https://img.shields.io/badge/QQ*-可用-EB1923.svg?logo=tencentqq" /></span></p></a>

<div align="left">

## 〢 贡献者
感谢所有贡献者对本项目的奉献！

<div align="center">
    <table>
        <tr>
            <td>
                <h3>DuolaDStudio Hong Kong Ltd.</h3>
                <a href="https://github.com/DuolaDStudio">
                    <img src="https://avatars.githubusercontent.com/u/152937804?s=200&v=4" width="70" style="border-radius: 50%" alt="DuolaDStudio Hong Kong Ltd.">
                </a>
		<h3>也就是以下成员：</h3>
		<h5>哆啦D夢|DuolaD & 琳尼特|LynetteNotFound</h5>
		<a href="https://github.com/DuolaD"><img src="https://avatars.githubusercontent.com/u/110040721?v=4" width="70" style="border-radius: 50%" alt="DuolaD"></img></a>
		<a href="https://github.com/LynetteNotFound">
                    <img src="https://avatars.githubusercontent.com/u/159673876?v=4" width="70" style="border-radius: 50%" alt="LynetteNotFound">
                </a>
            </td>
	    <td>
                <a href="https://github.com/DuolaDStudio">组织的GitHub主页</a><br>
		<a href="https://github.com/DuolaD">哆啦D夢|DuolaD的GitHub个人主页</a><br>
		<a href="https://github.com/LynetteNotFound">琳尼特|LynetteNotFound的GitHub个人主页</a><br>
		<br>
		<a>注意:哆啦D夢|DuolaD其它个人主页链接见上;</a><br>
		<a>琳尼特|LynetteNotFound没有公开联系方式</a>
            </td>
	</tr>
        <tr>
            <td>
                <h3>阿向菌|AXBro</h3>
                <a href="https://www.youtube.com/@AXBroCN">
                    <img src="Readme.md-image/AXBro-Logo.jpg" width="70" style="border-radius: 50%" alt="AXBro">
                </a>
            </td>
            <td>
		<a href="https://www.hoyolab.com/accountCenter/postList?id=368916437">HoYoLAB个人主页</a><br>
		<a href="https://www.youtube.com/@AXBroCN">YouTube频道</a><br>
                <a href="https://www.tiktok.com/@axbrocn?_r=1&_d=eaij8279i83mcl&sec_uid=MS4wLjABAAAAv9yK1VQOks5sB_wbFyXogwDO909TuxhAZ-e-qnpFlMiZ1B4FTIGrh9jdg5KTsuMr&share_author_id=7293608271650030634&sharer_language=en&source=h5_m&u_code=eaij8b3012e2l5&ug_btm=b8727%2Cb0&sec_user_id=MS4wLjABAAAAv9yK1VQOks5sB_wbFyXogwDO909TuxhAZ-e-qnpFlMiZ1B4FTIGrh9jdg5KTsuMr&utm_source=copy&social_share_type=4&utm_campaign=client_share&utm_medium=ios&tt_from=copy&user_id=7293608271650030634&share_link_id=9E0D9FA7-E376-4EAA-B1A1-21F25EE8A746&share_app_id=1233">TikTok频道</a><br>
		<a href="https://space.bilibili.com/436127696">BiliBili频道</a>
            </td>
        </tr>
        <tr>
            <td>
                <h3>REL(Ex_M)</h3>
                <a href="https://github.com/34736384">
                    <img src="Readme.md-image/REL-Logo.jpg" width="70" style="border-radius: 50%" alt="REL">
                </a>
            </td>
            <td>
                <a href="https://github.com/34736384">GitHub个人主页</a><br>
		<a href="https://space.bilibili.com/44434084?spm_id_from=333.337.0.0">BiliBili频道</a>
            </td>
        </tr>
    </table>
</div>
