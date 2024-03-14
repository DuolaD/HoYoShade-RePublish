# HoYoShade-RePublish

[EN](Readme.md)|**简体中文**|[繁體中文](Readme.Chinese_Traditional.md)  

[开发中]重新发行所有受到DMCA影响的旧版本HoYoShade和过时源码等。(当然是肯定会移除DMCA内容啦，想啥呢)  

> [!NOTE]
> 翻译并非100%准确，翻译工作主要基于OpenAI-GPT4T，谷歌翻译和本人的校对组成。 但即使如此，最终成品也难免会产生一定的问题。 如果你发现或者你认为这是一个问题，请提交issues以帮助HoYoShade改进。

请注意，Main分支仅仅只有Readme.md自述文件用于说明该仓库的一些信息，以及为本仓库各个分支进行一个目录归总和描述。  

## 〢 目录

- [介绍](#〢-介绍)
- [为什么会有这个附属库?](#〢-为什么会有这个附属库)
- [仓库分支目录](#〢-仓库分支目录)
- [支持游戏列表](#〢-支持游戏列表)
- [来源](#〢-来源)
- [OpenHoYoShade和HoYoShade](#〢-OpenHoYoShade和HoYoShade)
- [如何安装?](#〢-如何安装)
- [鸣谢](#〢-鸣谢)
- [赞助](#〢-赞助)
- [联系我](#〢-联系我)
- [贡献者](#〢-贡献者)

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

