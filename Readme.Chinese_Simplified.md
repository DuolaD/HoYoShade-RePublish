# HoYoShade-RePublish

[EN](Readme.md)|**简体中文**|[繁體中文](Readme.Chinese_Traditional.md)  

[开发中]重新发行所有受到DMCA影响的旧版本HoYoShade和过时源码等。(当然是肯定会移除DMCA内容啦，想啥呢)  

> [!NOTE]
> 翻译并非100%准确，翻译工作主要基于OpenAI-GPT4T，谷歌翻译和本人的校对组成。 但即使如此，最终成品也难免会产生一定的问题。 如果你发现或者你认为这是一个问题，请提交issues以帮助HoYoShade改进。



## 〢 目录

- [介绍](#〢-介绍)
- [为什么会有这个附属库?](#〢-为什么会有这个附属库)
- [支持游戏列表](#〢-支持游戏列表)
- [来源](#〢-来源)
- [OpenHoYoShade和HoYoShade](#〢-OpenHoYoShade和HoYoShade)
- [如何安装?](#〢-如何安装)
- [推荐游戏图像设置](#〢-推荐游戏图像设置)
- [截图展示](#〢-截图展示)
- [关于DMCA](#〢-关于DMCA)
- [鸣谢](#〢-鸣谢)
- [赞助](#〢-赞助)
- [联系我](#〢-联系我)
- [贡献者](#〢-贡献者)

## 〢 介绍

该仓库是[HoYoShade](https://github.com/DuolaD/HoYoShade)的附属仓库。  

主要的目的是用于在移除受DMCA影响的内容后重新发行受DMCA影响的Release，以及对过时内容进行归档。  
请注意，重新发行受影响的Release更重要的意义在于提供参考资料用于第三者进行二次开发时用于参考，而并非在现阶段有更稳定的版本时仍然让你使用旧版。  
如果你什么都不懂，不想二次开发，只是想正常在米哈游系列游戏中使用ReShade,请访问[HoYoShade](https://github.com/DuolaD/HoYoShade)主仓库，在查看Readme.md文档后选择合适你的最新版Release下载即可。  

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

