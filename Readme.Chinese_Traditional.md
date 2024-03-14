# HoYoShade-RePublish

[EN](Readme.md)|[简体中文](Readme.Chinese_Simplified.md)|**繁體中文**  

重新發行所有受到DMCA影響的舊版HoYoShade和過時原始碼等。 (當然是一定會移除DMCA內容啦，想啥呢)  

> [!NOTE]
> 翻譯并非100%準確，翻譯工作主要基於OpenAI-GPT4T，谷歌翻譯和本人的校對組成。但即使如此，最終成品也難免會產生一定的問題。如果你發現或者你認爲這是一個問題，請提交issues以幫助HoYoShade改進。  

請注意，Main分支僅只有Readme.md自述文件用於說明該倉庫的一些信息，以及為本倉庫各個分支進行一個目錄歸總和描述。  

## 〢 目錄

- [介紹](#〢-介紹)
- [為什麼會有這個附屬庫?](#〢-為什麼會有這個附屬庫)
- [倉庫分支目錄](#〢-倉庫分支目錄)
- [支持游戲列表](#〢-支持游戲列表)
- [來源](#〢-來源)
- [OpenHoYoShade和HoYoShade](#〢-OpenHoYoShade和HoYoShade)
- [如何安裝?](#〢-如何安裝)
- [鳴謝](#〢-鳴謝)
- [贊助](#〢-贊助)
- [聯繫我](#〢-聯繫我)
- [貢獻者](#〢-貢獻者)

## 〢 介紹

該倉庫是[HoYoShade](https://github.com/DuolaD/HoYoShade)的附屬倉庫。  

主要的目的是用於在移除受DMCA影響的內容後重新發行受DMCA影響的Release，以及對過時內容進行歸檔。  
請注意，重新發行受影響的Release更重要的意義在於提供參考資料用於第三者進行二次開發時用於參考，而並非在現階段有更穩定的版本時仍然讓你使用舊版。  

> [!NOTE]
> 請注意，重新發行的Releases版本號後綴均為'RePublish'。

HoYoShade一個非官方Reshade，使其能在突破米哈遊對於官方Reshade的封鎖下正常用於所有可在PC端運行的米哈遊遊戲。

ReShade的工作原理是攔截CPU和GPU之間的通信，並修改渲染信息以達到提高圖像質量的目的。HoYoShade集成了一些基於官方ReShade的開源項目(具體列表請查看[來源頁面](#〢-來源))並對其進行修改，使其與PC上所有的米哈遊遊戲兼容，並製作一些有針對性的預設。未來，它將支持更多的米哈遊遊戲。

有關本倉庫貢獻者的信息，請訪問[貢獻者界面](#〢-貢獻者)

## 〢 為什麼會有這個附屬庫

自從HoYoShade首個版本發行後，HoYoShade便受到了來自中國大陸地區視頻博主的關注和贊助。 在經過了一段時間後，便有部落客提出將Pascal Gilcher團隊的付費效果庫整合在HoYoShade的Release中。 直至V2.12.2 Stable版本後，我們收到了Pascal Gilcher團隊的DMCA警告。  

在受到警告的第一時間後，HoYoShade便以最快的速度下架了所有版本Release的下載鏈接，並已將相關源碼進行備份，並在第二天發布了不受DMCA警告影響的V2.013.0 Stable版本。  

在此，DuolaDStudio全體成員向Pascal Gilcher團隊標示深深的歉意，並保證並承諾今後的任何一個HoYoShade的Release絕不會出現Pascal Gilcher團隊中的內容。  

Pascal Gilcher團隊是ReShade中非常知名的付費效果庫開發團隊，他們的每個付費效果庫都具有很好的品質(例如：RTGI)。
如果你想使用付費效果庫或支援Pascal Gilcher團隊的話，請[點擊這裡](https://www.patreon.com/mcflypg/posts)前往他們官方Patreon介面購買方案後自行安裝至HoYoShade。  

而該附屬庫存在的目的便是在去除Pascal Gilcher團隊的內容後重新發行Releases，以便為第三者進行二次開發的時候可以提供具有一定價值的參考資料。  

## 〢 倉庫分支目錄

- **倉庫分支目錄**(本分支，用於本倉庫各分支進行一個目錄歸總和描述)
- [**V1.X.X-Outdated_Source**](https://github.com/DuolaD/HoYoShade-RePublish/tree/V1.X.X-Outdated_Source) (V1.X.X的過時程式原始碼檔案等)
- [**V1.X.X-Final**](https://github.com/DuolaD/HoYoShade-RePublish/tree/V1.X.X-Final) (V1.X.X大版本最終框架(更多還是紀念意義*1))
- [**V2.X.X-Outdated_Source**](https://github.com/DuolaD/HoYoShade-RePublish/tree/V2.X.X-Outdated_Source) (V2.X.X的過時程式原始碼檔案等)  

*1：在此特別感謝阿向菌|AXBro提供資金支持讓V2.X.X版本順利開發!感恩!  

## 〢 支持游戲列表

不同遊戲版本的(Open)HoYoShade支援遊戲清單和功能也會有有所不同，具體支援遊戲情況請查看各版本Releases介面描述。  
如果你什麼都不懂，不想二次開發，只是想正常在米哈遊系列遊戲中使用ReShade,請訪問[HoYoShade](https://github.com/DuolaD/HoYoShade)主倉庫，在查看Readme. md文檔後選擇適合你的最新版Release下載即可。  

最新版本的[HoYoShade](https://github.com/DuolaD/HoYoShade)可以保證受支援的遊戲和功能最多，同時穩定性高於本倉庫任何一個RePublish版本。  

> [!NOTE]
> ·對於私服玩家來說，如果私服需要的對應客戶端出現在支援的遊戲清單中，則表示HoYoShade可以提供支援。  
> ·對於未出現在支援遊戲清單中的遊戲，你可以自行嘗試選擇使用注入器中已支援的遊戲/在開發者選項中選擇自定義注入來嘗試注入HoYoShade。

## 〢 來源

對於V1.X.X版本:  

| 名字 | 介紹 | 網址 |
| --- | --- | --- |
| **非官方ReShade** | ReShade 4.9.2 UnOfficial移除網路通訊驗證版本*1 | [官方倉庫](https://github.com/crosire/reshade),[官方網站](https://reshade.me/) |
| **Crosire的ReShade注入器** | 這只是一個注入器 | [前往ReShade官方倉庫查看源碼](https://github.com/crosire/reshade/blob/main/tools/injector.cpp) |

*1:自ReShade Official V5.X.X版本開始,從官網上下載的'with full add-on support'安裝程式內的ReShade32.dll和ReShade64.dll就已經移除了網路通訊驗證。 而在此之前的ReShade Official所有安裝包內的ReShade32.dll和ReShade64.dll都含有網路通訊驗證。  

網路通訊驗證會偵測遊戲在遊戲具有高網路請求的時候自動停用ReShade以防止反作弊偵測到ReShade進而導致遊戲帳號出現封禁(來自ReShade官方的描述)，但這很顯然不適用於MiHoYo/HoYoVerse旗下的 遊戲中。 所以我們需要移除網路通訊驗證以讓ReShade可以正常在MiHoYo/HoYoVerse旗下遊戲運作。  

## 

對於V2.X.X版本:  

| 名字 | 介紹 | 網址 |
| --- | --- | --- |
| **ReShade官方** | Releases中的ReShade版本號碼會在5.9.2至6.0.1不等 | [官方倉庫](https://github.com/crosire/reshade),[官方網站](https://reshade.me/) |
| **Crosire的ReShade注入器** | 這只是一個注入器 | [前往ReShade官方倉庫查看源碼](https://github.com/crosire/reshade/blob/main/tools/injector.cpp) |

請注意，基於Aria2開發的更新器於V2.0131.0 Stable版本中開始發行，這並不屬於本倉庫RePublish的範圍之中。

## 〢 OpenHoYoShade和HoYoShade

我們將會在每個RePublish版本中發布HoYoShade RePublish包和OpenHoYoShade RePublish包。  
不同版本中的(Open)HoYoShade功能和特性可能都有所不同，具體情況請查看各版本Releases介面描述。  

OpenHoYoShade为HoYoShade底层基本框架，它涵盖了使ReShade注入至全系米哈游旗下游戏的所有必要文件。  
OpenHoYoShade存储占用会比HoYoShade小, 但OpenHoYoShade并没有内置ReShade效果库，预设等，适用于想对HoYoShade进行二次开发的二次开发者。  

如果你只是想在MiHoYo/HoYoVerse遊戲下使用ReShade，請下載HoYoShade。  
如果你想要開發一個可以在MiHoYo/HoYoVerse遊戲下使用的ReShade，但是你又不想學習過多的東西，那麼你可以選擇下載OpenHoYoShade。  

要讓 OpenHoYoShade 快速運作，您唯一需要做的就是將效果庫和預設放在各自正確的位置。  
但如果你願意，你可以進行進一步的開發，例如注入器、Reshade.ini建構器等等等等，甚至重新發行！ （開源萬歲！)  
(哦對了......當你重新發行文件時，確保你重新發行的文件遵守了BSD-3開源協議)  

當然了,如果你想要獲得舊版註入程序/更多信息，請在GitHub倉庫中點擊‘Code’按鈕，然後選擇‘Download Zip’。  

如果你還是不明白OpenHoYoShade和HoYoShade之間有什麼不同，那麼以下的圖表或許可以很好的幫助你說明：  

|  | OpenHoYoShade | HoYoShade |
| --- | --- | --- |
| **ReShade** | 有 | 有 |
| **使ReShade注入至全系米哈遊旗下遊戲的所有必要文件** | 有 | 有 |
| **程式原始碼** | 有 | 没有 |
| **Reshade的效果庫(包含插件)** | 沒有(你需要自行準備) | 有 |
| **預設** | 沒有(你需要自行準備) | 有 |
| **誰會需要他們？** | 二次開發者 | 普通遊戲玩家 |

## 〢 如何安裝

從[本倉庫的發行頁面](https://github.com/DuolaD/HoYoShade-RePublish/releases) 下載最新版本的HoYoShade RePublish。  

對於V1.X.X RePublish版本：  
-使用注入器啟動注入程序，然後使用啟動器啟動遊戲即可。  

對於V2.X.X RePublish版本：  
-使用注入器  
-將產生在模組根目錄下的ReShade.ini複製至遊戲進程根目錄  
-啟動注入程序，然後使用啟動器啟動遊戲即可。  

## 〢 鳴謝
感謝以下合作伙伴的支持：  
| 名字 | 介紹 | 網址 |
| --- | --- | --- |
| **CY Team** | HoYoShade合作伙伴/微軟企業存儲計劃提供/動態鏈接轉靜態鏈接解決方案 | [官方網站](https://www.cyteam.cn/) |
| **Cloudflare, Inc.** | V2.0131.0 Stable版本更新器網域託管與管理 | [官方網站](https://www.cloudflare.com/) |

## 〢 贊助
**點擊對應按鈕來贊助HoYoShade**  
贊助的金額由你自行設定。

<div align="center"><p><span ><a href="https://patreon.com/DuolaD"><img src="https://img.shields.io/badge/Patreon-000000.svg?logo=patreon" /></a> <a href="https://www.paypal.com/paypalme/Dmou114514233"><img src="https://img.shields.io/badge/PayPal-003087.svg?logo=paypal" /></a> <a href="Readme.md-image/WechatDonateCode.JPG"><img src="https://img.shields.io/badge/微信支付-07C160.svg?logo=wechat&logoColor=white" /></a> <a href="Readme.md-image/AirPayDonateCode.png"><img src="https://img.shields.io/badge/支付寶-1677FF.svg?logo=alipay&logoColor=white" /> </span></p></a></div>

## 〢 聯繫我

> [!NOTE]
> ·如果你處於中國大陸地區，則某些聯繫方式可能不可用。結尾帶星號標識'*'的聯繫方式可以保證在中國大陸地區使用，並且可以獲得更快速的響應和支持。
> ·如果你在使用此模組時有任何的問題，請先在本倉庫創建一個issue。

**點擊對應按鈕聯絡我：**
  
<div align="center"><p><span ><a href="https://discordapp.com/users/960705009866137631"><img src="https://img.shields.io/badge/Discord-可用-5865F2.svg?logo=discord" /></a> <a href="https://www.douyin.com/user/MS4wLjABAAAAGUohNGixQiCHKSoHJy0Ae6WS3R7pMd7lSfi5O4A9zH7gdcEd4JEX787i-RFNH257"><img src="https://img.shields.io/badge/抖音*-可用-000000.svg?logo=tiktok" /></a> <a href="https://t.me/D_mou"><img src="https://img.shields.io/badge/Telegram-可用-26A5E4.svg?logo=telegram" /></a>  <a href="https://qm.qq.com/q/njKy8OrUU8"><img src="https://img.shields.io/badge/QQ*-可用-EB1923.svg?logo=tencentqq" /> </span></p></a>

<div align="left">

## 〢 貢獻者
感謝所有貢獻者對本項目的奉獻！

<div align="center">
    <table>
        <tr>
            <td>
                <h3>DuolaDStudio Hong Kong Ltd.</h3>
                <a href="https://github.com/DuolaDStudio">
                    <img src="https://avatars.githubusercontent.com/u/152937804?s=200&v=4" width="70" style="border-radius: 50%" alt="DuolaDStudio Hong Kong Ltd.">
                </a>
		<h3>也就是以下成員：</h3>
		<h5>哆啦D夢|DuolaD & 琳尼特|LynetteNotFound</h5>
		<a href="https://github.com/DuolaD"><img src="https://avatars.githubusercontent.com/u/110040721?v=4" width="70" style="border-radius: 50%" alt="DuolaD"></img></a>
		<a href="https://github.com/LynetteNotFound">
                    <img src="https://avatars.githubusercontent.com/u/159673876?v=4" width="70" style="border-radius: 50%" alt="LynetteNotFound">
                </a>
            </td>
	    <td>
                <a href="https://github.com/DuolaDStudio">組織的GitHub主頁</a><br>
		<a href="https://github.com/DuolaD">哆啦D夢|DuolaD的GitHub個人主頁</a><br>
		<a href="https://github.com/LynetteNotFound">琳尼特|LynetteNotFound的GitHub個人主頁</a><br>
		<br>
		<a>注意:哆啦D夢|DuolaD的其它個人主頁連結見上;</a><br>
		<a>琳尼特|LynetteNotFound沒有公開聯係方式</a>
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
		<a href="https://www.hoyolab.com/accountCenter/postList?id=368916437">HoYoLAB個人主頁</a><br>
                <a href="https://www.youtube.com/@AXBroCN">YouTube頻道</a><br>
		<a href="https://www.tiktok.com/@axbrocn?_r=1&_d=eaij8279i83mcl&sec_uid=MS4wLjABAAAAv9yK1VQOks5sB_wbFyXogwDO909TuxhAZ-e-qnpFlMiZ1B4FTIGrh9jdg5KTsuMr&share_author_id=7293608271650030634&sharer_language=en&source=h5_m&u_code=eaij8b3012e2l5&ug_btm=b8727%2Cb0&sec_user_id=MS4wLjABAAAAv9yK1VQOks5sB_wbFyXogwDO909TuxhAZ-e-qnpFlMiZ1B4FTIGrh9jdg5KTsuMr&utm_source=copy&social_share_type=4&utm_campaign=client_share&utm_medium=ios&tt_from=copy&user_id=7293608271650030634&share_link_id=9E0D9FA7-E376-4EAA-B1A1-21F25EE8A746&share_app_id=1233">TikTok頻道</a><br>
		<a href="https://space.bilibili.com/436127696">BiliBili頻道</a>
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
                <a href="https://github.com/34736384">GitHub個人主頁</a><br>
		<a href="https://space.bilibili.com/44434084?spm_id_from=333.337.0.0">BiliBili頻道</a>
            </td>
        </tr>
    </table>
</div>
