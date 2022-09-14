---
title: 最新版本注意事項
description: 閱讀最新發行說明以了解Adobe [!DNL Experience Cloud] 產品與服務。 了解近期活動和新的Experience League檔案。 探索 [!DNL Experience Cloud] 應用程式。
doc-type: release notes
last-update: September 2022
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: 9cabd3285eeaca306d9da14d98cfa6b0311f5d11
workflow-type: tm+mt
source-wordcount: '6495'
ht-degree: 39%

---

# Adobe Experience Cloud 版本注意事項 - 2022 年 9 月

![橫幅](assets/experience-cloud-banner-3.png)

身為 Experience Maker，您的成功之道始於 [ Experience League](https://experienceleague.adobe.com/?lang=zh-Hant#home)。尋找廣大的操作說明文件庫、自我引導式教學課程、操作說明影片、所有等級和角色適用的課程、線上同業社群，以及需要時的專家支援。

>[!NOTE]
>
>若要收到關於本頁更新的每月電子郵件通知，請訂閱 [Adobe 優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)。請經常回來查看，持續了解 Experience League 最新消息。

最新更新：**2022 年 9 月 12 日**

* [[!DNL Experience League] 活動](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - 中央介面元件和管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem) （已更新） **9月12日**)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [數位體驗藍圖 - 教學課程](#blueprints)

需要協助嗎？請造訪 [ Experience League](https://experienceleague.adobe.com/#home)，了解產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

## ![圖示](/assets/experience-league.png) [!DNL Experience League] 活動 {#events}

若要向 Adobe 產品專家學習、與之互動或獲得解答，Experience League 活動是您絕佳的選擇！請查看 Experience League 上的[活動](https://experienceleague.adobe.com/events/?lang=zh-Hant)，以掌握 2022 年 7 月活動的最新消息。

已更新 **2022年9月9日**

| 產品/事件名稱 | 類型 | 說明 |
| -----------|---------- | ----|
| **Experience League精彩案例** | 比賽 | 告訴Adobe您如何整合Experience Cloud產品，以建立創新且個人化的客戶體驗。 提交您的故事，讓Adobe認可！ **9月9日至29日接受的條目** - [詳細資料](https://experienceleaguecommunities.adobe.com/t5/experience-league-showcase-2022/con-p/exl-showcase-2022?sdid=3NQZB6J7&amp;mv=email) |
| **[!DNL Adobe Workfront]** | 研討會 | 尋找與其他客戶聯繫並討論的機會 [!DNL Workfront] 功能？ 加入我們的CS Connections系列！ 每月與其他客戶交流，討論貴組織的熱門話題的機會。<p>**日期：** 9月12日早7點手動 [詳細資訊與註冊](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,frxd5xOTA0WDD-QNQbG9Ww,N0rLVNiX1EKbZDmYfMbfKg,mwypq4e8M0qTYr1PjHWlgg?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Experience Cloud]** | 網路研討會 | _體驗製作者直播_ - Sara Blakely、Peyton Manning和Eli Manning的免費演講。<p>**日期：** 9 月 13 日 - 14 日 - [詳細資料和報名](https://business.adobe.com/events/experience-makers-live.html) |
| **[!DNL Adobe Campaign]** （傳統版和標準版） | 網路研討會 | 跨管道行銷人員的假日季和一年中最繁忙的時間即將推出。 計畫應該正在進行中。 此 [!DNL Adobe Campaign] Insider課程涵蓋有助於您進行電子郵件傳遞的主題， [!DNL Adobe Campaign] 效能調整，以及工作流程和傳送最佳實務，以確保您的執行個體處於最高峰活動狀態。<p>**日期：** 9月15日早上8點00分PT [詳細資訊與註冊](https://adobe-campaign-insider.dxfieldmarketing.adobeevents.com/) |
| **[!DNL Adobe Workfront]** | 研討會 | 圖表工作流程 — 與客戶成功團隊一起，即時討論並逐步介紹圖表工作流程（從進入到完成），並了解如何為有效的工作管理做法奠定堅實的基礎。 <p>**日期：** 9 月 20 日 -  日 - [詳細資料和報名](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,hKbbhANIJ0GUZ80-hyYRPQ,eHZZsesEKEW-f54PGw4z9w,8IgA8CD5yEyKFei9pwlDJA,iACjdG_hK0m1uoTTaMinZA,TEaHrWBF3USQb49XCqymTg?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | 網路研討會 | _系統管理要點：資源管理快速入門_  — 使用Adobe [!DNL Workfront] 要管理您的資源，DREAM是DREAM — 了解需要完成的工作、您可以存取哪些資源，並根據其可用性來分配它們。 加入我們，了解如何操作。<p>**日期：** 9月21日@英國早上8點 [詳細資訊與註冊](https://webinars.on24.com/adobe_workfront/AdminEssentialsRM?partnerref=exl) |
| **[!DNL Adobe Workfront]** | 研討會 | _價值實現系列：強調專案範本_  — 與我們一起討論 [!UICONTROL 專案範本] 以及它們為組織創造價值和提高效率的不同方式。 我們會集思廣益，運用不同的方法來建構範本，以支援您的專案，依行銷活動、交付內容等等。 我們演示了一些收藏夾，並逐步介紹了最新的藍圖。 <p>**日期：** 9月21日中午12點30分手動 [詳細資訊與註冊](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,fir0yEdzREq77VYkVxk2kw,W3nJ9w4q-U69PVqUTk7D6Q,zs6GtWtgRkyikfMUMzBEmw?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | 研討會 | _10個通訊提示，可讓您和您的使用者保持一致_  — 有效溝通是您、您的使用者、最終是公司成功不可或缺的一環。 本研討會提供10個提示，包括內外 [!DNL Workfront]  — 幫助提高效能、提高生產力並降低不必要問題的風險。 <p>**日期：** 9月22日晚上7點00分手動 [詳細資訊與註冊](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,PiX3iDTmREqs2eOICcUIoA,5KJVGb6S_Uiiki7ErNALgw,Jcg3aU0zf0uG9pB-_vmCUg,pdnZcB-mqk2_nMKUQEQnsA,xYRXQWa6OU6_tvNTp_vuFQ?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Campaign Classic]** 和 **[!DNL Adobe Campaign Standard]** | 研討會 | _社區問答茶歇_  — 與Tamara Wulf和Earl Ross一起討論您對 [!DNL Adobe Campaign] 線上講座內容 _節假日和旺季的成功清單_. <p>**日期：** 9月22日晚上8點手動 [詳細資訊與註冊](https://adobe.ly/3KHrGpl) |
| **[!DNL Adobe Workfront]** | 研討會 | _使用控制面板推動採用：規劃者_  — 加入客戶成功團隊，繼續根據 [!DNL Adobe Workfront] 角色。 此會議重點介紹您的規劃人員，他們通常在項目或計畫管理角色中工作。 了解如何建立主動、以團隊為導向的空間，以提高活動意識和問責性。 <p>**日期：** 9月27日上午9點00分手動 [詳細資訊與註冊](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,hKbbhANIJ0GUZ80-hyYRPQ,eHZZsesEKEW-f54PGw4z9w,Y1He1usOwUaIvlln-RiUCw,PbQY6cwRBkiHr0Uxk8YBow,2QMMEWx0e0C65kbQ1d4cIA?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | 研討會 | _價值實現系列：規劃您的Workfront歷程_  — 您的Workfront歷程接下來會是什麼？ 與我們一起討論如何為貴組織的Adobe Workfront建立專屬藍圖。 我們將分享您最喜愛的里程碑的一些想法，以加入您的藍圖，以及我們以前的系統管理員身分提供的體驗。<p>**日期：** 10月4日中午12點30分手動 [詳細資訊與註冊](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,Bx3LyyABjkC6f0LfiHlHgw,F_Tenijn5UulPjqprok8eg,7lni6LpvlEWagR1OIDfosA?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | 研討會 | _CS連接：分享策略最佳實務_  — 尋找與其他客戶交流並討論Workfront功能的機會？ 加入我們的CS Connections系列！  每月與其他客戶交流，討論貴組織的熱門話題的機會。 我們將與系統管理員一起集思廣益，以解決難題、分享想法並討論最佳實務。 <p>**日期：** 10月10日早上7點00分手動 [詳細資訊與註冊](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,gw8sK1IYp0qugO85lvn9HA,1hAkk731fE2cuzI1JCe2Aw,Lox5X4bDSUC_HaF3SDUy7A?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | 研討會 | _透過使用者管理推動採用_  — 您是否開始使用Workfront，並想要更熟悉與使用者相關的設定功能？ 加入客戶成功團隊，一起檢閱報表和控制面板的實作範例，為成功的使用者管理奠定基礎，並建立有用且資訊豐富的使用者體驗。<p>**日期：** 10月18日早上9點00分手動 [詳細資訊與註冊](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,hKbbhANIJ0GUZ80-hyYRPQ,eHZZsesEKEW-f54PGw4z9w,lJV3sMGDTE2CpLxcuzZQXg,KGHthDBZ80q9JJ-wzHyqBQ,mY-6BCClJkmc_bRvqGebtQ?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |
| **[!DNL Adobe Workfront]** | 研討會 | _採用系列：讓Workfront開心（前）!_ 需要採納想法嗎？ 我們抓到了！ 我們的團隊已經經歷了用戶採用的高低，專注於樂趣是成功的關鍵。 我們將討論一些對我們有用的東西，並為與其他客戶分享想法的公開討論提供充足的時間。<p>**日期：** 10月20日中午12點30分MT [詳細資訊與註冊](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,0qiSuEYEcUSxTibSYXD-jA,8QGOKlkyJE25EiBggDF6Ng,WmVegsyV2E6ZDPSMCifdVw?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1) |

{style=&quot;table-layout:auto&quot;}

請查看 Experience League 上的[活動](https://experienceleague.adobe.com/events/?lang=en)，以掌握即將舉辦的活動和過去集數的最新消息。

## ![圖示](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 會提供有關 Adobe 產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/) 來查看。

如需最新版本資訊，請參閱 Adobe 系統狀態[版本注意事項](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=zh-Hant#status)。

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud - 中央介面元件和管理 {#ecloud}

Experience Cloud [中央介面元件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hant)包含首頁上可用的功能和永續性產品標題。這些功能包含使用者基本資料設定、偏好設定和搜尋。您也可以找到使用者和產品管理、客戶屬性以及 Experience Cloud Audiences 的說明。

### 佈建更新

>[!IMPORTANT]
>
>管理員，不要錯過這則關於 Experience Cloud 佈建的[重要通知](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=zh-Hant#july---2022) (2022 年 7 月發佈)。

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 和 [!UICONTROL Mobile SDK] 的最新版本資訊和新文件：

計畫發行： **2022年9月28日**

* [Experience Platform發行說明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant)  — （2022年8月24日）

### [!DNL Adobe Mobile] SDK

已更新： **2022年9月1日**  — 請參閱 [發行說明和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes) (適用於Adobe Experience Platform Mobile SDK)。

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

下一版： **2022年9月14日**

上次更新： **2022年9月6日**

* Adobe Analytics [版本注意事項](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hant)
* Adobe Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)

### AppMeasurement {#appm}

發行版本：**2.22.4**

* [JavaScript 適用的 AppMeasurement 版本注意事項](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)

### 新 [!DNL Analytics] 教學課程和其他課程 {#tutorials-analytics}

專為 Adobe Analytics 發佈的新影片教學課程、文章和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 9 月 | [建立流量視覺效果](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-visualization.html?lang=en) | 影片 | 了解如何使用「流量」視覺效果來探索客戶與您品牌的確切歷程。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

最新更新：**2022 年 9 月 6 日**

* Customer Journey Analytics [版本注意事項](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hant)
* Customer Journey Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hant)

### 新的 Customer Journey Analytics 教學課程和其他課程 {#tutorials-cja}

針對 CJA 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 9 月 | [適用於 Customer Journey Analytics 的對象發佈](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/audiences/audience-publishing-for-cja.html) | 影片 | 了解如何使用Customer Journey Analytics，將您在分析中發現的受眾發佈至Adobe Experience Platform即時客戶設定檔，以便使用Adobe Real-time Customer Data Platform或Adobe Journey Optimizer啟用區段。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

上次更新：**2022 年 3 月 23 日**

* [!DNL Streaming Media Analytics] [版本注意事項](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=zh-Hant)
* [!DNL Streaming Media Analytics] [產品文件與教學課程](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=zh-Hant)

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

未更新

如需自助資源，請參閱 Experience League 上的 [Audience Manager 文件與教學課程](https://experienceleague.adobe.com/docs/audience-manager.html?lang=zh-Hant)。

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Experience Manager 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

<!-- See [Current Release Notes for Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current.html) -->

Adobe 建議您造訪 [Experience Manager 版本更新與藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hant)頁面，以掌握最新的版本資訊。

### 產品更新影片

觀看 [2022年8月發行概述影片](https://video.tv.adobe.com/v/345409/?quality=12) 2022.8.0版（2022年8月）中新增功能的摘要。 <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

* [2022年7月發行概述影片](https://video.tv.adobe.com/v/345409/?quality=12)
* [2022 年 6 月版本概觀影片](https://video.tv.adobe.com/v/344308/?quality=12)
* [2022 年 5 月版本概觀影片](https://video.tv.adobe.com/v/343321/?quality=12)
* [2022 年 4 月版總覽影片](https://video.tv.adobe.com/v/342612?quality=12)
* [2022 年 3 月版總覽影片](https://video.tv.adobe.com/v/341465)
* [2022 年 1 月版總覽影片](https://video.tv.adobe.com/v/340120)
* [2021 年 12 月版總覽影片](https://video.tv.adobe.com/v/339278)
* [2021 年 10 月版總覽影片](https://video.tv.adobe.com/v/338253)
* [2021 年 9 月版總覽影片](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Assets] as a [!DNL Cloud Service]

_新功能_

* 以連結形式共用數位資產時，使用者可以立即將URL複製到剪貼簿。 此增強功能可讓您以更快、更方便的方式共用資產。此功能可讓您更快速且便利地共用資產。
* 當您上傳 TXT 檔案時，資產微服務會自動產生縮圖。 PNG 縮圖是 TXT 檔案的轉譯，可幫助用戶在一定程度上識別內容或檔案，而不需要開啟檔案。 在預設情況下，此功能不需要任何組態設定就能使用。

_發行前管道中可用的新功能_

* 使用者現在可以在「欄」和「卡片」檢視中，對搜尋結果中顯示的資產進行排序。 排序功能適用於名稱、建立時間、修改時間或無等欄。

### Experience Manager [!DNL Forms] as a [!DNL Cloud Service]

_新功能_

* AEMFormsas a Cloud Service的原型專案現在包含 [Microsoft® Dynamics和Salesforce.com的表單資料模型](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/setup-environment/setup-local-development-environment.html?lang=en#forms-cloud-service-local-development-environment).
* 基於Acroform的記錄文檔：Experience Manager Formsas a Cloud Service支援使用 [Adobe Acrobat表單PDF(AcroformPDF)](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/generate-document-of-record-for-non-xfa-based-adaptive-forms.html) 作為記錄檔的範本，而非以XFA為基礎的表單範本。
* Microsoft® Azure資料儲存連接器：您現在可以 [將表單資料模型連接到Microsoft® Azure儲存](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/use-form-data-model/configure-azure-storage.html). 它可讓您擷取並儲存最適化表單資料至Microsoft® Azure儲存，做為BLOB。

_Beta 版的 Forms 功能_

* **統一儲存連接器**  — 使用Unified Storage Connector將客戶管理的儲存庫中的流程中資料外部化。 例如，您可以
   * 啟用Forms Portal的儲存和繼續功能，並將最適化表單草稿儲存在客戶管理的資料存放庫中。
   * 儲存在客戶管理的存放庫中包含敏感個人資料(SPD)的處理中Experience Manager工作流程資料(Experience Manager工作流程變數資料)。
* **Experience Manager Formsas a Cloud Service，通訊** - [通訊API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html) 幫助您結合XDP模板和XML資料，以生成各種格式的打印文檔。 此服務可讓您以同步模式產生文件。 這些 API 可讓您建立以下用途的應用程式：
   * 使用 XML 資料填寫範本檔案來產生文件。
   * 產生多種格式的輸出表單，包括非互動式 PDF 列印資料流。
   * 從 XFA 表格 PDF 和 Adobe Acrobat Form 產生列印 PDF 檔案。您可以寫信寄到 [formscsbeta@adobe.com](mailto:formscsbeta@adobe.com) 來註冊 beta 版計劃。

_發行前管道中可用的新功能_

* **在適用性表單中使用Adobe Sign角色**  — 適用於業務和企業服務級別的Adobe Sign可以選擇將協定收件者的角色擴展到簽署者之外，以更好地滿足其工作流要求。 您現在可以[啟用每個協議收件者，以便在最適化表單中設定其角色](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/use-adobe-sign/working-with-adobe-sign.html?lang=en#addsignerstoanadaptiveform)，並將簽署者設定為預設角色。
* **適用性Forms**  — 您現在可以透過Adobe Analytics for Adaptive Forms擷取及追蹤一般使用者行為，以收集一般使用者分析。 這有助於根據資料做出明智的決策，以改善一般使用者體驗。
* **輕鬆連接Experience Manager Forms與Microsoft® Dynamics和Salesforce.com**  — 此服務提供Microsoft® Dynamics的現成可用資料來源設定和資料模型，以及 [Salesforce.com](https://www.salesforce.com/?bc=DF). 這個能力讓 [開發人員可更快更輕鬆地配置Microsoft® Dynamics 365和Salesforce雲端服務，以適應性表單](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/use-form-data-model/configure-msdynamics-salesforce.html).

### Experience Manager Screens as a Cloud Service

_新功能_

* Screens as a Cloud Service現在支援基本播放監控。 播放器現在會報告各種播放量度，每次偵測（預設為30秒）。 根據這些量度，它可以偵測各種邊緣情況 (停滯體驗、空白螢幕、排程問題等)。 此功能可讓團隊在遠端監控播放器是否有正確地播放內容。 它也會改善對空白螢幕或現場中斷體驗的反應能力，並減少向一般用戶顯示中斷體驗的風險。
請參閱 [基本播放監控](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/screens-as-cloud-service/manage-player-registration/installing-screens-cloud-player.html?lang=en#playback-monitoring) 以取得更多詳細資訊。
* Screens as a Cloud Service現在支援的視訊縮圖支援。 內容作者可以定義視訊的縮圖，以便將影像用作預留位置。 他們可以適當地測試內容播放和目標定位，同時由適當的團隊完成實際影片。 如果影片播放失敗，也可以使用該影像。
請參閱 [影片的縮圖支援](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/screens-as-cloud-service/core-product-features/thumbnail-support-videos.html) 以取得更多詳細資訊。

### [!DNL Cloud Manager]

_新功能_

* Cloud Manager使用的AEM原型專案版本現已更新為30版。
* Cloud Manager登陸頁面上的方案卡片和相關聯的體驗現在會重新整理。
* 程式碼品質步驟記錄現在包含有關 OakPal 掃描程序的詳細記錄資訊。
* 「活動」頁面功能表選項現在包含已完成代碼產生器執行的「下載記錄」選項。 選取此選項會下載建置步驟的記錄檔。
* 直接按一下「方案」卡片，現在會導覽至「Cloud Manager概觀」頁面。
* Cloud Service客戶現在可以在Cloud Manager中檢視SLA（服務等級協定）報表。 此功能將在未來幾個月逐步推出。
請參閱 [SLA報告](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/sla-reporting.html) 了解更多。
* IndexType和IndexDamAssetLucene質量規則的類型和嚴重性已更改。 這兩個都是Bugs of Blocker嚴重性。
* 我們引進了新的 Oak 索引品質規則來涵蓋非同步和 Tika 組態設定。
* 將每個程式的 SSL 憑證數上限增加到 50。
* 自助服務功能，可讓使用者透過Cloud Manager使用者介面建立和管理多個存放庫。
* SonarQube在不必要地閱讀Git歷史資料。 在大型程式碼基底中，這可能會導致不必要的組建效能損失。
* 現在有一個 API 可讓每個管道的 Maven 相依性快取失效。
* Cloud Manager使用的AEM原型專案版本現已更新為29版。

### 社群

* AEMas a Cloud Service2022.7.0 - [版本更新](https://adobe.ly/3paYDAo).
* **Experience League精彩案例**  — 向我們和全世界展示您可以如何使用多個Adobe Experience Cloud產品。 [立即提交您的報導！](https://experienceleaguecommunities.adobe.com/t5/experience-league-showcase-2022/con-p/exl-showcase-2022?sdid=3NQZB6J7&amp;mv=email)
* AEM使用者群組聚會 |AdobePTP，班加羅爾 | 2022年9月30日 | [在這裡註冊](https://adobe.ly/3DlsUos) | [論社區主線](https://adobe.ly/3DhQwub).

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022 年 9 月 | [AEM as a Cloud Service 2022.8.0 版本更新](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/2022/2022-8-0.html?lang=tw) | 影片 | 聽聽AEM產品團隊的意見，了解最新版Adobe Experience Manager的功能與創新 [!DNL Assets], [!DNL Assets Essentials], [!DNL Sites]、商務整合架構、 [!DNL Forms]，和 [!DNL Cloud Manager]. | AEM |
| 2022 年 9 月 | [網頁最佳化影像傳送](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/components/web-optimized-image-delivery.html?lang=en) | 影片 | 了解如何使用AEM核心元件，在AEMas a Cloud Service網站上啟用網頁最佳化影像傳送。 | AEM Sites |
| 2022 年 9 月 | [與Microsoft®電源自動化整合](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-cs-and-power-automate/integrate-formscs-power-automate.html?lang=en) | 影片 | 在最適化表格提交時叫用您的電源自動化流程。了解設定及整合Forms CS與Microsoft®電源自動化的步驟。 剖析已提交的表單資料，並以電子郵件附件的形式傳送DoR。 | AEM Forms CS |
| 2022 年 9 月 | [Adobe內容管理論壇活動系列 — 2022](https://experienceleague.adobe.com/docs/adobe-content-management-forum-events/events/2022/welcome.html?lang=en) | 影片 | 觀看Elliot Sedegah提供的歡迎辭並取得AEM概觀。 此外，它還涵蓋釋放內容速度的力量等。 | AEM CS |
| 2022 年 9 月 | [技能交換 — 開發人員追蹤 — 體驗製作者精選](https://experienceleague.adobe.com/docs/skill-exchange-events/events/aem/aug2022/developer-track/spotlight.html?lang=en) | 影片 | 加入我們，聚焦兩位專業AEM使用者。 每個人都分享自己最好的AEM秘訣或技巧。 | AEM CS |
| 2022 年 9 月 | [技能交流 — 市場營銷人員/ Web發佈商](https://experienceleague.adobe.com/docs/skill-exchange-events/events/aem/aug2022/marketer/reusability.html?lang=en) | 影片 | 了解如何運用體驗片段，促進生態系統的重複使用和效率。 這會影響投資報酬率和驅動速度。 | AEM CS |
| 2022 年 9 月 | [如何使用AEM React Editable Components v2](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/spa-editor/how-to/react-core-components-v2.html?lang=en) | 影片 | 了解如何使用AEM React可編輯的元件。 AEM提供AEM React可編輯元件v2，此SDK是以Node.js為基礎，可建立React元件，支援使用AEM SPA編輯器進行內容內容元件編輯。 | AEM CS |

{style=&quot;table-layout:auto&quot;}

### Experience Manager 版本資訊

所有 Experience Manager 的版本注意事項都會保留在以下頁面：

* [Experience Manager as a Cloud Service 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hant)
* [Experience Manager Cloud Manager 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=zh-Hant)
* [Automated Forms Conversion Service 版本注意事項](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hant)
* [Experience Manager 6.5 Service Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=zh-Hant)
* [Experience Manager 6.4 Cumulative Fix Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hant)
* [Experience Manager Assets Dynamic Media 版本注意事項](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hant)
* [Experience Manager Brand Portal 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hant)
* [Experience Manager 桌面應用程式版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hant)
* [Experience Manager Dispatcher 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hant)
* [Adobe Primetime 版本注意事項](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=zh-Hant)
* [Livefyre 版本注意事項](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=zh-Hant)

### 適用於 Experience Manager 的其他說明資源

* [Experience Manager as a Cloud Service 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=zh-Hant)
* [Cloud Manager 使用手冊](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=zh-Hant)
* [Experience Manager 6.5 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hant)
* [Experience Manager 6.4 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hant)
* [Experience Manager 6.3 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant)
* [Experience Manager 6.2 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant#previous-updates)
* [舊版 Experience Manager 文件](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 說明首頁](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hant)
* [Experience Manager 文件：最近更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hant#aem-as-a-cloud-service)

## ![圖示](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] 是部署至 AEM 的應用程式。這是一個功能強大、企業級元件內容管理解決方案 (CCMS)；此解決方案啟用 Adobe Experience Manager 的原生 DITA 支援，使 AEM 能夠處理以 DITA 為主的內容建立和傳遞。

進一步了解 [[!DNL Experience Manager Guides]](https://www.adobe.com/tw/products/xml-documentation-for-experience-manager/features.html)。

### 其他資源

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=zh-Hant) - Experience League 上的教學課程
* [[!DNL Experience Manager Guides] 學習與支援](https://helpx.adobe.com/tw/support/xml-documentation-for-experience-manager.html) - 產品文件

## ![圖示](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

請參閱以下 Adobe Commerce 版本注意事項連結：

* [Adobe Commerce 和 Magento Open Source 2.4.x 版本注意事項](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 版本注意事項](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)
* [支付服務發行說明](https://experienceleague.adobe.com/docs/commerce-merchant-services/payment-services/release-notes.html)
* [產品Recommendations發行說明](https://experienceleague.adobe.com/docs/commerce-merchant-services/product-recommendations/release-notes.html)
* [Live Search發行說明](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/release-notes.html)
* [商店完成發行說明](https://experienceleague.adobe.com/docs/commerce-merchant-services/store-fulfillment/release-notes.html)
* [Amazon發行說明Sales Channel](https://experienceleague.adobe.com/docs/commerce-channels/amazon/release-notes.html)

>[!NOTE]
>
>[!DNL Adobe Search&Promote] 服務終止計畫為 **2022年9月1日**. 對於產品和商務搜索， [即時搜尋](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/overview.html?lang=en) 是Adobe的搜尋應用程式。 請參閱 [終止公告](https://experienceleague.adobe.com/docs/search-promote/using/sp-eol.html?lang=en) 以取得更多資訊。

### 新的 Adobe Commerce 教學課程和文件 {#tutorials-commerce}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 9 月 | [使用 Adobe Experience Manager 提供無頭式體驗](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=zh-Hant) | 影片 | 了解使用最新 Experience Manager 內容片段增強功能的無頭式體驗管理，以及用於無頭式內容提供的新 GraphQL API。 |
| 2022 年 9 月 | [Adobe Commerce目錄管理指南](https://experienceleague.adobe.com/docs/commerce-admin/catalog/guide-overview.html) | 影片 | 取得內容與設計功能的詳細資訊，包括建立基本內容元件。 |
| 2022 年 9 月 | [設定多個商務系統](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/administering/multiple-commerce-systems-setup.html) | 影片 | 了解如何使用多個Adobe商務環境設定AEM。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新： **2022年9月6日**

* 如需搶鮮版資訊，請參閱 [Adobe Target 搶鮮版](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)。
* 如需目前版本資訊，請參閱 [Adobe Target 版本注意事項](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hant)。

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新 Campaign 產品版本

在 [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hant)、[Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) 和 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hant) 版本注意事項中進一步了解最新功能、改進與修正。

### 新 [!DNL Campaign] 教學課程和其他課程 {#tutorials-campaign}

針對 Adobe Campaign 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 9 月 | [為 Adobe Campaign 設定簡訊](https://experienceleague.adobe.com/?recommended=Campaign-A-1-2022.classic.setupsms) | 課程 | 了解如何將Campaign執行個體連結至SMTP提供者，以及如何分析和疑難排解設定。 | Campaign Classic v7 |
| 2022 年 9 月 | [為 Adobe Campaign 設定簡訊](https://experienceleaguecommunities.adobe.com/t5/adobe-campaign-classic/course-discussion-set-up-sms-for-adobe-campaign/m-p/542687#M2301) | 課程 | 了解如何將Campaign執行個體連結至SMTP提供者，以及如何分析和疑難排解設定。 | Campaign v8 |
| 2022 年 9 月 | [SMPP 協定深入剖析和疑難排解](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/smpp-deep-dive-and-troubleshooting.html?lang=zh-Hant) | 影片 | 瞭解如何建立 SMPP 連線以及 SMPP 如何通過 PDU 交換資料。 瞭解如何疑難排解連線問題。 | 促銷活動v8 |

{style=&quot;table-layout:auto&quot;}

### Campaign 說明資源

* Adobe Campaign v8：[文件](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hant)
* Adobe Campaign Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hant) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [操作說明影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=zh-Hant) - [做法影片](https://experienceleague.adobe.com/docs/control-panel-learn/tutorials/control-panel-overview.html?lang=en)的做法影片

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

使用 [!DNL Journey Optimizer]，您可以透過單一應用程式為數百萬客戶管理已排程的全通路行銷活動和一對一交流，而整個歷程都透過智慧決策和深入分析而最佳化。

### 最新 Journey Optimizer 產品版本

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hant)中最新功能、改進功能和修正。

### 全新的 Journey Optimizer 教學課程和其他課程 {#tutorials-ajo}

針對Adobe發佈的新影片、教學課程或課程 [!DNL Journey Optimizer].

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 9 月 | [行銷人員決策管理快速入門](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1.offerdecisioning) | 影片 | 了解Adobe Journey Optimizer的決策管理功能。 本課程專為想要透過向客戶提供最佳優惠方案來提升收入、客戶體驗和忠誠度的行銷人員而設計 |
| 2022 年 9 月 | [建立行銷活動](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-campaigns/create-a-campaign.html?lang=en) | 影片 | 了解如何透過立即執行動作或依指定排程傳送一次性內容給特定對象。 |

{style=&quot;table-layout:auto&quot;}

### [!DNL Journey Optimizer] 的更多資源

* [Journey Optimizer 文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hant)
* [決策管理文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioning/get-started-decision/starting-offer-decisioning.html) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hant)

## ![圖示](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

運用 Experience Platform 聰明地即時預測每個人的需求，在不同體驗管道大規模地協調客戶歷程。

### 最新 [!DNL Journey Orchestration] 產品版本

進一步了解 [[!DNL Journey Orchestration]  版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hant)中最新功能、改進功能和修正。

#### [!DNL Journey Orchestration] 的更多資源

* [Journey Orchestration 文件](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hant)

## ![圖示](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是適用於潛在客戶管理以及想要透過參與複雜購買旅程的每個階段來轉換客戶體驗的 B2B 行銷人員的完整應用程式。

### Marketo Engage 核心更新

如需最新發行排程資訊和版本注意事項，請參閱「[!DNL Marketo Engage] [發行排程](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hant)」。

### 最新 Marketo 教學課程與課程 {#tutorials-marketo}

針對 Adobe Marketo 發佈的新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 8 月 | [Marketo Engage 教學課程](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) | 影片 | 如需 Marketo Engage 所有過去和最新的教學課程，請造訪 [Marketo Engage 教學課程首頁](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en)。 |

{style=&quot;table-layout:auto&quot;}

如需最新的產品文件，請參閱 [Marketo 產品文件](https://experienceleague.adobe.com/docs/marketo/using/home.html?lang=zh-Hant)首頁

## ![圖示](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] 是統一的工作管理應用程式，用於共用構想、建立內容、管理複雜的流程並執行其最佳工作。

### 最新 Adobe Workfront 課程與教學課程 {#tutorials-workfront}

最新Workfront課程和Experience League教學課程系列。

**注意：** 即將翻譯所有Workfront教學課程和產品檔案的Experience League!

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 9 月 | [Workfront課程](https://experienceleague.adobe.com/?recommended=Workfront-A-1-2022.1.admin) | 課程 | 瀏覽我們針對Workfront提供的Experience League課程。 |
| 2022 年 9 月 | [最佳作法](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/best-practices/agile-bp.html?lang=en) | 文章 | 從內部和外部了解最佳實務 [!DNL Workfront] 如何使用的專家 [!DNL Workfront] 增強工作流程的工具。 |
| 2022 年 9 月 | [展示板](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/agile/boards/add-and-edit-column-settings-on-a-board.html?lang=en) | 影片 | 觀看說明如何使用新展示板工具及其最新功能的新教學課程。 |
| 2022 年 9 月 | [敏捷：Scrum](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/agile/scrum/create-a-scrum-agile-team.html?lang=en) | 影片 | 了解如何建立敏捷團隊、選取scrum方法，以及決定scrum團隊的設定。 觀看教學課程從移轉 [!DNL Workfront One] 說明如何在 [!DNL Workfront]. |
| 2022 年 9 月 | [敏捷：看板](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/agile/kanban/create-a-kanban-team.html?lang=en) | 影片 | 觀看教學課程從移轉 [!DNL Workfront One] 說明如何在 [!DNL Workfront] |
| 2022 年 9 月 | [個人休假日曆](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/manage-resources/personal-time-off-calendar/how-time-off-affects-project-timelines.html?lang=en) | 文章 | 檢視教學課程，說明個人休假為何重要，以及如何將其加入Workfront中以更輕鬆的方式管理資源。 |
| 2022 年 9 月 | [Workfront融合訓練](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/fusion/welcome-to-workfront-fusion/workfront-fusion-overview.html?lang=en) | 影片 | 每個Workfront Fusion章節都包含多個教學課程，每個教學課程會呈現您在處理下一個教學課程之前需要了解的概念。 逐步練習可協助您掌握大部分概念。 |

{style=&quot;table-layout:auto&quot;}

請參閱[[!DNL Workfront] 產品版本](https://experienceleague.adobe.com/docs/workfront/using/product-announcements/product-releases/product-releases.html)頁面，以取得所有產品的最新資訊匯總。

## ![圖示](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 版本注意事項。

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
* [ [!DNL Advertising Cloud DSP] 中的新功能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] 中的新功能](#adcloud-search)
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **August 9, 2022**

| Feature | Description |
| ------- | ----------- |
| Integration with [!DNL Adobe Analytics] | (August 6 release) Improvements to the data feed that Advertising Cloud sends to [!DNL Analytics] result in fewer mismatches between click/cost/impression data from the search engines and related conversion data in [!DNL Analytics]. |

{style="table-layout:auto"}
  
-->

### [!DNL Advertising Cloud DSP] 中的新功能 {#adcloud-dsp}

上次更新日期：**2022 年 9 月 12 日**

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 封裝和放置步調] | （9月12日發行版本）現在可對飛行步調和當天步調進行單獨的步調控制。 以前，單一策略會同時控制兩者。 現有套件和版位的設定對應如下：<ul><li>舊版 **[!UICONTROL 步調填充策略]**=*[!UICONTROL 平均]*  — 現已設定為 **[!UICONTROL 飛行步調]**=*[!UICONTROL 平均]* 和 **[!UICONTROL 當天步調]**=*[!UICONTROL 平均]*</li><li>舊版 **[!UICONTROL 步調填充策略]**=*[!UICONTROL 稍微向前]*  — 現已設定為 **[!UICONTROL 飛行步調]**=*[!UICONTROL 稍微向前]* 和 **[!UICONTROL 當天步調]**=*[!UICONTROL 平均]*</li><li>舊版 **[!UICONTROL 步調填充策略]**=*[!UICONTROL Frontload]*  — 現已設定為 **[!UICONTROL 飛行步調]**=*[!UICONTROL Frontload]* 和 **[!UICONTROL 當天步調]**=*[!UICONTROL 盡快]*</li><li>舊版 **[!UICONTROL 步調填充策略]**=*[!UICONTROL 積極的Frontload]*  — 現已設定為 **[!UICONTROL 飛行步調]**=*[!UICONTROL 積極的Frontload]* 和 **[!UICONTROL 當天步調]**=*[!UICONTROL 盡快]*</li></ul> |

{style=&quot;table-layout:auto&quot;}

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search}

上次更新： **2022年9月9日** 9月10日發行

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 行銷活動] | ([!DNL Google Ads] 賬戶；測試版功能)您現在可以建立和管理 [!DNL Google Ads] 績效最大促銷活動，可使用 [!DNL Google Ads] 智慧競標，使用 [!UICONTROL 促銷活動類型] &quot;[!UICONTROL 效能最大值].&quot; |
|  | ([!DNL Google Ads] 帳戶)「促銷活動>廣告」檢視現在包含選用 [!UICONTROL 廣告強度] 欄，指出每個回應式搜尋廣告(RSA)遵循的成效 [!DNL Google Ads] 效能最佳實務。<br><br>[!DNL Microsoft® Advertising] 尚未透過其API啟用類似支援。 |
|  | ([!DNL Microsoft® Advertising] 帳戶)同步、唯讀和報告（包括閱覽資料）支援現在可用於您現有的原生廣告促銷活動，位於 [!DNL Microsoft® Audience Network]，包括 [!DNL Microsoft®] 對象廣告。 |
| [!UICONTROL 行銷活動], [!UICONTROL 報表] | 未來幾週，行銷活動管理檢視和報表中的欄將可使用更多發佈商曝光共用量度。 |
| [!UICONTROL 轉換值規則] | ([!DNL Google Ads accounts];測試版功能)您現在可以從 [!UICONTROL 最佳化] > [!UICONTROL 轉換值規則]. 廣告商與 [!DNL Google Ads] 個別帳戶層級或以下的轉換追蹤也可以建立和管理規則。<br><br>未來版本將提供轉換值規則的自動最佳化。 |
| [!UICONTROL 產品組合] | (選擇加入測試版功能； [!DNL Google Ads] 帳戶) [!DNL YouTube] 行銷活動 [!UICONTROL 最大化轉換] 混合組合中的競標策略現在包含在自訂模擬結果中。 混合組合只能包括 [!DNL YouTube] 行銷活動。<br><br>若要參與測試版計畫，請連絡您的客戶團隊。 |
| [!UICONTROL 廣告深入分析] | 此 [!UICONTROL Advertising Insights] 「視圖」具有新的外觀和工作流，基於可改進效能和可靠性的新基礎架構。 現在，只需按一下分析名稱，選取或輸入設定，然後按一下 [!UICONTROL 產生分析].<br><br>若要暫時返回舊視圖，請啟用 [!UICONTROL 切換至舊UI] 在右上角。 舊版檢視將於9月底移除。 |
|  | 此 [!UICONTROL 查詢交叉匹配測試版] 現已可使用分析。 |
| [!UICONTROL 報表] | ([!DNL Google Ads] 僅限帳戶)新專業報告 [!UICONTROL RSA Assets報告] 顯示每個資產的曝光量度([!UICONTROL 創作標題] 或 [!UICONTROL 說明])，適用於一或多個產品組合或一或多個帳戶、行銷活動和廣告群組中的回應式搜尋廣告(RSA)。 依預設，資料包含每個資產的一列，這些資產在指定資料範圍內至少收到一次曝光，即使在報告期間停用（移除）資產亦然。 **注意：** 選取「[!UICONTROL 包含沒有效能資料的行]，」資料仍不會包含從未收到資料之資產的資料。 |
|  | 如需回應式搜尋廣告(RSA)的其他支援，請參閱 [!UICONTROL 廣告變異報表]:<ul><ul>([!DNL Google Ads] 帳戶) [!UICONTROL 欄] 設定，新的&quot;[!UICONTROL 廣告強度]「 」清單示RSA的執行情況 [!DNL Google Ads] 效能最佳實務。 在 [!UICONTROL 行銷活動] > [!UICONTROL 廣告] 檢視。 [!DNL Microsoft® Advertising] 尚未透過其API啟用類似支援。</li><li>在 [!UICONTROL 欄] 設定，您可以依 [!UICONTROL 創意標題] 和 [!UICONTROL 說明].</li><li>在 [!UICONTROL 進階篩選] 設定，您可以依 [!UICONTROL 廣告文字] 欄位，此欄位適用於 [!UICONTROL 創意標題] 和 [!UICONTROL 說明].</li></ul> |
| [!UICONTROL 建議] | ([!DNL Google Ads] 賬戶；測試版功能)內 [!UICONTROL 前瞻分析與報表] > [!UICONTROL Recommendations Beta]，您可以：<ul><li>查看所有尚未採取行動的建議 [!DNL Google Ads] 帳戶。</li><li>申請並駁回帳戶建議。</li><li>檢視針對帳戶套用之每個建議的記錄。</li></ul> |
| [!UICONTROL 匯入促銷活動] | （測試版功能）您可以匯入 [!DNL Google Display Network] 行銷活動，包括廣告影像， [!DNL Microsoft® Advertising] 對象促銷活動 [!DNL Microsoft® Audience Network] 從 [!UICONTROL 工具] > [!UICONTROL 匯入促銷活動]. 匯入行銷活動後，您可以檢查匯入工作的狀態、檢閱任何錯誤記錄檔，以及編輯、暫停或刪除匯入排程。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

針對Adobe Document Cloud發佈的新教學課程和課程，包括 [!DNL Document Services] 和 [!DNL Acrobat Sign].

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 9 月 | [註冊開發人員帳戶](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/sign-up-developer-account.html?lang=en) | 影片 | 在 _Acrobat Sign內嵌快速入門手冊_，了解如何註冊Acrobat Sign API開發人員帳戶。 您的新開發人員帳戶已透過Sign和API功能完全啟用。 | Document Services |
| 2022 年 9 月 | [建立您的應用程式](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/creating-your-application.html?lang=en) | 影片 | 在 _Acrobat Sign內嵌快速入門手冊_，了解如何使用Acrobat Sign API建立應用程式。 | 檔案服務 |
| 2022 年 9 月 | [建立內嵌連結](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/creating-an-embed-link.html?lang=en) | 影片 | 在 _Acrobat Sign內嵌快速入門手冊_，了解如何建立OAuth的內嵌連結。 您的應用程式會使用此OAuth方法取得使用者的權限。 | 檔案服務 |
| 2022 年 9 月 | [產生存取權杖](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/generating-an-access-token.html?lang=en) | 影片 | 在 _Acrobat Sign內嵌快速入門手冊_，了解如何產生可與Acrobat Sign API搭配使用的存取權杖。 | 檔案服務 |
| 2022 年 9 月 | [建立暫時文檔](https://experienceleague.adobe.com/docs/document-services/tutorials/acrobatsign/creating-a-transient-document.html?lang=en) | 影片 | 在 _Acrobat Sign內嵌快速入門手冊_，了解如何建立暫時性檔案。 | 檔案服務 |
| 2022 年 9 月 | [自動調整版面](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/auto-adjust-layout.html?lang=en) | 影片 | 了解可重新排列內容並自動調整PDF中各頁面版面的新編輯模式。 | Acrobat |
| 2022 年 9 月 | [新增自訂頁面](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/getting-started/add-custom-page.html) | 影片 | 了解如何使用整合式Adobe Express應用程式將自訂頁面新增至PDF，該應用程式提供數千個範本供您選擇。 | Acrobat |
| 2022 年 9 月 | [修改現有的Web表單](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/modify-webform.html?lang=en) | 影片 | 了解如何停用、編輯和重新啟用現有的網路表單。 | Acrobat Sign |
| 2022 年 9 月 | [建立報表](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/creating-a-report.html?lang=en) | 影片 | 了解如何建立您自己的報表，以掌握檔案簽署程式的相關資訊，或了解個別群組或使用者的運作方式。 | Acrobat Sign |
| 2022 年 9 月 | [建立報表圖表](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-a-report.html?lang=en) | 影片 (已更新) | 了解如何透過新的報表體驗，以個人化的檢視建立、儲存及管理您自己的自訂報表和資料匯出。 | Acrobat Sign |
| 2022 年 9 月 | [建立自訂工作流程](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/building-a-custom-workflow.html?lang=en) | 影片 (已更新) | 了解如何量身訂造和自動化檔案工作流程，以取得電子簽名、收集表單資料，以及確認重要檔案的傳送，以簡化工作流程管理。 | Acrobat Sign |
| 2022 年 9 月 | [在Microsoft Teams中發送以進行簽名](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/adobe-sign-teams-mortgage.html?lang=en) | 影片 (已更新) | 了解如何從Microsoft Teams內發送協定以進行簽名、檢查協定的狀態以及發送提醒。 | Acrobat Sign |
| 2022 年 9 月 | [將欄位添加到文檔](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/adding-fields.html?lang=en) | 影片 (已更新) | 了解如何自動將欄位放置在檔案上，或在Acrobat Sign內使用拖放式製作環境。 | Acrobat Sign |
| 2022 年 9 月 | [設定傳送選項](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/sending-options.html?lang=en) | 影片 (已更新) | 了解如何在傳送檔案以供簽署時設定各種選項。 | Acrobat Sign |

{style=&quot;table-layout:auto&quot;}

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hant)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hant)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)

## ![圖示](/assets/creative-cloud-24.png) 適用於企業的 Adobe Creative Cloud {#creative-cloud}

針對 Adobe Campaign 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 9 月 | [用Adobe Fonts緩解字型焦慮 ](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/assets/TamingTypeAnxiety.pdf?lang=en) | PDF | 透過此實作教學課程了解Adobe Fonts的運作方式。 |
| 2022 年 9 月 | [Adobe Acrobat內容建立者](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/assets/AcrobatforContentCreators.pdf?lang=en) | PDF | 身為內容建立者，您可能會產生PDF，然後在Adobe Acrobat中定期檢視這些PDF檔案。 但是，Acrobat也包含許多有助於簡化一般創意工作流程的工具。 了解兩種特定工具： [!UICONTROL 與其他人共用] 和 [!UICONTROL 保護]. |

{style=&quot;table-layout:auto&quot;}

如需了解最新教學課程，請參閱「[適用於企業的 Creative Cloud 教學課程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en)」。

## ![圖示](/assets/experience-league.png) 客戶資料管理 - 對話 {#voices}

身為客戶資料管理技術和行銷實務主管和專家的您，[客戶資料管理對話](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=zh-Hant)是您的最終目的地。此教學課程集合是您聆聽同行的意見、獲取靈感並了解 MarTech 中發展的一站式中心。不用報名，按一下即可觀看。

## ![圖示](/assets/experience-league.png)數位體驗藍圖 {#blueprints}

[數位體驗藍圖](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=zh-Hant)是可重複的實施，可讓您處理策略，並快速解決既定的業務問題。每個藍圖都提供一系列成品，解釋高價值業務問題、架構、實施步驟、技術考量以及相關文件的連結。

[頁面頂端](#events)
