---
title: 最新版本注意事項
description: 了解  [!DNL Experience Cloud]  產品和服務的最新版本注意事項、新功能和新文件。尋找有關  [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和  [!DNL Document Cloud] 最新的說明與教學課程。
doc-type: release notes
last-update: May 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 8ddc70389416b26d1cd0c6be5a60c1d34f2cc954
workflow-type: tm+mt
source-wordcount: '4974'
ht-degree: 52%

---

# Adobe Experience Cloud 發行說明 - 2022 年 5 月

![橫幅](assets/experience-cloud-banner-3.png)

身為 Experience Maker，您的成功之道始於 [Adobe Experience League](https://experienceleague.adobe.com/?lang=zh-Hant#home)。尋找廣大的操作說明文件庫、自我引導式教學課程、操作說明影片、所有等級和角色適用的課程、線上同業社群，以及需要時的專家支援。

準備好開始使用了嗎？[進行 5 分鐘測驗並獲勝](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)！

>[!NOTE]
>
>若要收到關於本頁更新的每月電子郵件通知，請訂閱 [Adobe 優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)。請經常回來查看，持續了解 Experience League 最新消息。

上次更新日期：**2022 年 5 月 13 日**

* [[!DNL Experience League] 活動](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - 中央介面元件和管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
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

需要協助嗎？請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，了解產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

## ![圖示](/assets/experience-league.png) [!DNL Experience League] 活動 {#events}

若想學習、互動和了解 Adobe 產品專家的答案，Experience League 活動會是個好選擇！

**2022 年 5 月 13 日**&#x200B;更新

| 活動 | 類型 | 說明 |
| -----------|---------- | ----|
| [Adobe Analytics — 經驗創造者 — 技能交流](https://events.bizzabo.com/389219?promo=ExperienceLeague&amp;tr=true) | 技能交流 | 與我們一起參加這次免費的、三小時的數位活動，全部關注Adobe Analytics。 即時詢問最瞭解Workspace的專家和同行。<br>2022年5月18日@ 1:30pm-4:東部時間晚30點<br> [詳情和報名](https://events.bizzabo.com/389219?promo=ExperienceLeague&amp;tr=true) |
| [Adobe Campaign — 客戶成功網路研討會系列](https://peer2peerenhancecustomerjourney-ac-may2022.experienceleague.adobeevents.com/) | Peer2Peer:增強客戶通過Adobe Campaign的旅程。 | 與Streamotion旗下Kayo、Bove和Flash品牌的Engagement Operations負責人Anja Starun一起參加這次Peer2Peer現場討論。 直接從她那裡聽取她的團隊成功實施的策略，這些策略旨在利用Adobe Campaign建立個性化的客戶旅程。 <br>**日期：** 5月26日東部標準時間下午3點 <br>[詳細資訊和註冊](https://peer2peerenhancecustomerjourney-ac-may2022.experienceleague.adobeevents.com/) |
| [使用Journey Optimizer推送通知 — 如何輕鬆配置移動應用以推送](https://www.youtube.com/watch?v=t36Xjhukmro) | Experience League LIVE | 瞭解與Adobe Journey Optimizer一起使用推送通知的常見使用案例，並深入瞭解如何配置由Adobe Experience Platform支援的推送應用的技術詳細資訊。 <br>**日期：** 2022年5月12日上午9:30<br>[計畫和過去事件](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hant) |
| [Adobe Target 社群](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-4-27-22-8am-pt-jim-mctiernan/m-p/446940#M3096) | 問答休息時間 | 加入Adobe Target產品團隊的Brent Kostak和Drew Burns，他們可以回答您的Adobe Target問題，包括共用受眾、Real-Time CDP、第一方資料、端到端個性化工作流等。<br>觀看最近 [即時個性化網路研討會](https://experienceleaguecommunities.adobe.com:443/t5/adobe-target-discussions/webinar-recording-4-28-22-real-time-personalization-with-adobe/td-p/449012) 並將後續問題提交專家 [斷咖啡線](https://adobe.ly/3MyiDHa) 在Adobe Target社區！<br>**日期：** 2022年5月25日早8時<br>[詳細資訊和註冊](https://adobe.ly/3MyiDHa) |
| [Adobe [!DNL Developers Live]:商業](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2022/feb2022/overview.html?lang=en) | 按需視頻 | _Adobe Developers Live:商業2022_ 將擁有不同背景和獨特目的的開發商和經驗建築商聚集在一起，創造出令人難以置信的端到端體驗。 這一為期一天的虛擬會議具有重要的商務和開源開發人員更新、技術會議、社區網路機會等功能。 |
| [Marketo技能交流](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | 按需視頻 | 瞭解您的Marketo路線圖的重要性以及如何避免規劃不周。 獲取有關釋放程式成員自定義域的潛力、Marketo Engage提示和技巧的建議，以及 [!DNL Marketo] 技能交流，現在正在Experience League。 |
| [2022 年 Adobe Summit](https://business.adobe.com/summit/adobe-summit.html) | 隨選研討會 | 向 Adobe 高階主管 Ryan Reynolds、Walgreens Boots Alliance, Inc. 執行長 Rosalind Brewer、NIKE, Inc. 執行長 John Donahoe 以及美國紅十字會執行長 Gail J. McGovern 學習客戶體驗如何成為數位經濟的貨幣。<br>探索 2022 年 Adobe Summit 的[隨選研討會](https://business.adobe.com/summit/2022/sessions.html)。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 會提供有關 Adobe 產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/) 來查看。

如需最新版本資訊，請參閱 Adobe 系統狀態[版本注意事項](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=zh-Hant#status)。

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud - 中央介面元件和管理 {#ecloud}

Experience Cloud [中央介面元件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hant)包含首頁上可用的功能和永續性產品標題。這些功能包含使用者基本資料設定、偏好設定和搜尋。您也可以找到使用者和產品管理、客戶屬性以及 Experience Cloud Audiences 的說明。

未更新。

**更多有關 [!DNL Experience Cloud Central UI Components] 與管理的說明資源**

* Experience Cloud 中央 UI 元件[版本注意事項](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=zh-Hant)
* Experience Cloud 的[使用者和產品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) (管理)
* Places Service [版本注意事項](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hant)
* [People - 客戶屬性和對象庫](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hant)產品文件
* [整合式搜尋物件和實體](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=zh-Hant)

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 和 [!UICONTROL Mobile SDK] 的最新版本資訊和新文件：

計畫發放日期： **2022年5月25日**

* [Experience Platform 版本注意事項](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant)

### 新 [!DNL Experience Platform] 教學課程和其他課程 {#tutorials-platform}

專為 [!DNL Experience Platform] 發佈的新影片教學課程、文章和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 5 月 | [段匹配共用前見解](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-pre-share-insights.html) | 影片 | 在您決定與戰略合作夥伴共用資料時，瞭解客戶的匹配情況非常重要，這樣您就知道資料共用將有多大幫助。 段匹配允許您在共用任何資料之前查看與潛在資料夥伴的重疊。 | [!DNL Real-time Customer Data Platform] |
| 2022 年 5 月 | [段匹配連接設定](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-connection-setup.html?lang=en) | 影片 | 瞭解如何設定您與合作夥伴之間的連接以便您可以共用受眾。 配置此段匹配功能後，您將能夠與資料合作夥伴來回共用資料。 | [!DNL Real-time Customer Data Platform] |
| 2022 年 5 月 | [段匹配資料管理](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-data-governance.html?lang=en) | 影片 | 瞭解如何在Real-Time CDP設定和使用資料治理控制，以便您能夠限制哪些資料集（以及使用這些資料集的段）可以與資料合作夥伴共用。 | [!DNL Real-time Customer Data Platform] |
| 2022 年 5 月 | [段匹配配置流](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-configuration-flow.html?lang=en) | 影片 | 瞭解配置 [!UICONTROL 段匹配] 資料共用的實例。 | [!DNL Real-time Customer Data Platform] |
| 2022 年 5 月 | [連接到目標](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/connecting-to-destinations.html) | 影片 | 在從即時CDP向目標合作夥伴發送資料之前，首先要與這些合作夥伴建立連接。 此視頻通過此過程進行，通常由管理員執行。 | [!DNL Real-time Customer Data Platform] |
| 2022 年 5 月 | [建立方案](https://experienceleague.adobe.com/docs/platform-learn/tutorials/schemas/create-schemas.html) | 影片 | 此視頻顯示了如何使用XDM Individual Profile類和各種欄位組在Adobe Experience Platform建立架構。 | Experience Platform |
| 2022 年 5 月 | [Tableau中全通道的查詢服務分析與可視化](https://experienceleague.adobe.com/docs/platform-learn/tutorials/queries/analyze-and-visualize.html) | 影片 | 瞭解如何使用流失分析示例將Adobe Experience Platform的查詢服務與外部資料可視化工具一起使用。 | Experience Platform |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Adobe Mobile] SDK

如需了解 Adobe Experience Platform Mobile SDK，請參閱[版本注意事項和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期：**2022 年 5 月 18 日**

* Adobe Analytics [版本注意事項](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hant)
* Adobe Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)

### AppMeasurement {#appm}

發行版本：**2.22.4**

* [JavaScript 適用的 AppMeasurement 版本注意事項](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)

### 新 [!DNL Analytics] 教學課程和其他課程 {#tutorials-analytics}

專為 Adobe Analytics 發佈的新影片教學課程、文章和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 5 月 | [開始使用Report Builder](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/get-started-with-report-builder.html?lang=en) | 影片 | 瞭解使用Report Builder的基本知識，包括安裝、登錄和資料請求。 |
| 2022 年 5 月 | [導航新登錄頁](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/navigating-the-new-landing-page.html?lang=en) | 影片 | 瞭解如何充分利用新的分析登錄頁及其功能。 |
| 2022 年 5 月 | [下一/上一和頁摘要工作區面板和報告](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/using-panels/next-previous-and-page-summary-workspace-panels-reports.html) | 影片 | 請參閱Analysis Workspace中的兩種新面板類型 — 下一頁/上一頁和頁面摘要。 這些功能使Workspace與一些較流行的 [!UICONTROL 報告和分析] 報告。 |
| 2022 年 5 月 | [Analysis Workspace登錄頁更新](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analysis-workspace-basics/analysis-workspace-landing-page-updates.html?lang=en) | 影片 | 瞭解新登錄頁的一些重大改進和補充。 我們已經收集了您的客戶反饋，並嘗試合併最突出的功能，如調整列大小、新列類型、指向即時和bot報告的連結以及許多其他功能。 |
| 2022 年 5 月 | [你問對了問題嗎？](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/are-you-asking-the-right-questions.html) | 影片 | 瞭解如何更有價值地識別和收集可操作的資料點，而不是記錄每個可能的元素。 要有效地確定這些資料點，需要與利益相關方進行基本規劃和創造性討論。 |
| 2022 年 5 月 | [使用 [!UICONTROL Report Builder] 高級交付選項，用於Power BI](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/use-report-builder-advanced-delivery-options-for-power-bi.html?lang=en) | 影片 | 瞭解如何設定高級計畫以將Report Builder工作簿發送到Power BI。 |
| 2022 年 5 月 | [計畫Report Builder請求](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/exporting/report-builder/schedule-a-report-builder-request.html?lang=en) | 影片 | 瞭解如何設定Report Builder工作簿的基本計畫。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

發行日期：**2022 年 5 月 18 日**

* Customer Journey Analytics [版本注意事項](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hant)
* Customer Journey Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hant)

## ![圖示](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

上次更新： **2022年3月23日**

* [!DNL Streaming Media Analytics] [版本注意事項](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=zh-Hant)
* [!DNL Streaming Media Analytics] [產品文件與教學課程](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=zh-Hant)

<!-- ### New Customer Journey Analytics tutorials and courses {#tutorials-cja}

New video tutorials, articles, and courses published for Customer Journey Analytics.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|April 2022|[Overview of configuring Data Views for Customer Journey Analytics](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/overview-of-configuring-data-views-for-cja.html?lang=en)|Video |Learn about configuring [!UICONTROL Data Views] for Customer Journey Analytics. [!UICONTROL Data Views] are similar to [!UICONTROL Virtual Report Suites] in Adobe Analytics. They allow you to configure the incoming data so that it can be most useful for your reporting and analysis. |
|April 2022|[Connections Details Experience in CJA](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections-details-experience-in-cja.html?lang=en)|Video |Learn how to check the status of your connection’s datasets and of the ingestion process.|
-->

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修正與改善：

| 改善 | 說明 |
| -----------| ---------- |  
| 屬於其他公司的目標資料來源的驗證器 | Audience Manager 已發佈[批次資料上線流程](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=zh-Hant)的改善。為了防止檔案和資料意外上線至其他合作夥伴擁有的目標資料來源，Audience Manager 以在合作夥伴 ID (PID) 與其他合作夥伴擁有的資料來源 (DPID) 之間新增對應需求。 <ul><li>另請參閱[輸入資料檔案的 Amazon S3 名稱和檔案大小需求](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=zh-Hant#name-elements)中的 __DPID_TARGET_DATA_OWNER_ 欄位。</li><li>如需新的對應需求改善和如何請求新對應的詳細資訊，Adobe 內部顧問和客戶服務應閱讀[管理第二方資料的上線存取](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=zh-Hant)</li><li>_不_&#x200B;一定要請求現有資料共用關係的對應。將資料上線至屬於您的 PID 的目標資料來源時，也&#x200B;_不_&#x200B;一定需要對應。</li></ul> |

{style=&quot;table-layout:auto&quot;&quot;

如需自助資源，請參閱 Experience League 上的 [Audience Manager 文件與教學課程](https://experienceleague.adobe.com/docs/audience-manager.html?lang=zh-Hant)。

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Experience Manager 中的新功能、修正及更新。Adobe 建議使用內部部署的客戶部署最新修補程式，以確保擁有更出色的穩定性、安全性及效能。

Adobe 建議您造訪 [Experience Manager 版本更新與藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hant)頁面，以掌握最新的版本資訊。

### Experience Manager 產品版本

* **Experience Manager as a Cloud Service**

   觀看 [2022年4月發佈概述視頻](https://video.tv.adobe.com/v/342612?quality=12) 2022.4.0（2022年4月）版中添加的功能摘要。 <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [2022年3月發佈概述視頻](https://video.tv.adobe.com/v/341465)。
   * [2022年1月發佈概述視頻](https://video.tv.adobe.com/v/340120)。
   * [2021年12月發佈概述視頻](https://video.tv.adobe.com/v/339278)。
   * [2021年10月發佈概述視頻](https://video.tv.adobe.com/v/338253)。
   * [2021年9月發佈概述視頻](https://video.tv.adobe.com/v/337381)。

* **Experience Manager Sites as a Cloud Service**

   _新功能_

   * 現在，您可以將內容模型資料類型定義為 [可譯](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/content-fragments/content-fragments-models.html?lang=en#properties) 使用內容模型編輯器中的複選框。 此外，Experience Manager轉換規則和配置會自動更新。

   _預發行渠道中的新功能_

   * 將體驗片段發佈到預覽 — 若要預覽訪問者可以查看的最終體驗，可以將獨立體驗片段發佈到Experience Manageras a Cloud Service預覽服務。


* **Experience Manager Assets as a Cloud Service**

   _新功能_

   * 你現在可以 [排序標籤](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/organize-assets.html?lang=zh-Hant#use-tags-to-organize-assets) 按照標籤名稱、建立日期或修改日期的升序或降序排列。

* **Experience Manager Forms as a Cloud Service**

   _新功能_

   * **通信 — Formsas a Cloud ServiceSDK中的文檔操作API支援** - [文檔處理API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=zh-Hant) 幫助合併、重新排列和驗證PDF文檔。 現在，您可以借助Experience Manager Formsas a Cloud ServiceSDK在本地開發環境中使用Communications - Document Generation API。
   * **使用自定義XCI生成記錄文檔**  — 您現在可以 [使用自定義XCI檔案設定記錄文檔的各種屬性](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/generate-document-of-record-for-non-xfa-based-adaptive-forms.html?lang=en#use-a-custom-xci-file)。 它會以自訂變更覆寫主要 XCI。它提供了對記錄文檔生成的更多控制，增加了個性化和定制機會。
   * **以自適應形式使用不可見的驗證碼**  — 您可以使用 [只有在存在可疑活動時，才能顯示驗證碼挑戰](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-an-adaptive-form/add-components-to-an-adaptive-form/captcha-adaptive-forms.html?lang=en)。 如果未發現可疑活動，則不顯示驗證碼質詢。它有助於評估人形表單的完成情況，而無需複選框要求，減少定制工作，並改善最終用戶體驗。
   * **表單資料模型配置**  — 您現在可以 [跨環境重用表單資料模型配置](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/use-form-data-model/create-form-data-models.html?lang=en#runmode-specific-context-aware-config)、簡化資料整合併降低IT成本。

* **Experience Manager Screens as a Cloud Service**

   _新功能_

   * 批量通道分配 — 用戶可以在一個操作中選擇多個通道並同時分配給多個顯示器。

* **Experience Manager as a Cloud Service 基礎**

   _**SDK Build Analyzer**_

   Experience Manageras a Cloud ServiceSDK生成分析器Maven插件可檢測給定項目中的問題，包括缺少依賴項。 它為開發人員提供了在本地開發過程中發現問題的機會，而且遠在使用Cloud Manager部署到雲環境之前。

   最近添加了一個新分析器：

   * content-packages-validation — 驗證部署過程中安裝的軟體包的格式良好的內容語法和結構。
   Adobe建議您使用分析器的最新版本來更新您的主項目，或者如果尚未更新分析器，則包括該分析器。 查看 [文檔](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/build-analyzer-maven-plugin.html?lang=zh-Hant) 的子菜單。

* **Cloud Manager**

   _新功能_

   * 「Experience Manager」頁中有一列可顯示環境的「環境版本」。
   * 管道執行現在在執行螢幕上顯示用戶介面頂級錯誤。
   * 通過雲管理器用戶介面重新執行生產部署步驟。
   * 重新使用生成映像以重新執行生產部署步驟。
   * 新API，用於啟用網路基礎架構的自助刪除。

* **Best Practices Analyzer**

   _新功能_

   * 能夠檢測和報告不支援的Asset Manager API的使用情況。 有四個API在Experience Manageras a Cloud Service中不再受支援。 客戶應確保不再使用這些API，並應使用新的資產上載方法。
   * 能夠檢測內容片段模板的使用情況。 不再支援在Experience Manageras a Cloud Service上建立新內容片段模板。 客戶必須建立內容片段模型以替換內容片段模板。
   * 能夠在儲存庫中資產的元節點下檢測具有100個以上子體的資產。 Adobe建議您刪除不需要的元資料節點，以便在載入包含此類資產的資料夾時提高效能。
   * 能夠檢測並報告所使用的資料儲存類型。
   * 已為Experience Manager窗體門戶更新模式。

### 社群

* **記錄Experience ManagerGEM網路研討會**

   * [_集AEM成和CIF框架，構建豐富而逼真的電子商務體驗_](https://adobe.ly/3jorz5r)。

* Experience Manageras a Cloud Service [2022.4.0版本更新](https://adobe.ly/3LO0gOo)。

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022 年 5 月 | [AEM as a Cloud Service 2021.4.0 版本更新](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/2021/2021-4-0.html?lang=en) | 影片 | 聽取產AEM品團隊的意見，瞭解最新版Adobe Experience Manager的功能和創新。 | Asset AEM Essentials 、 Sites 、 Screens 、Forms和Cloud Foundation |
| 2022 年 5 月 | [雲5 AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-5/cloud5-introduction.html) | 影片 | 在5分鐘或更短的短視頻中獲AEM取您所需的有關as a Cloud Service的所有有用資訊。 從第一季開始。 | AEM CS |
| 2022 年 5 月 | [獲取整合的登錄令牌](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/cloud-5/cloud5-getting-login-token-integrations.html) | 影片 | 有關如何獲取用於Cloud Service整合的登錄令牌的深入指南，以及用於此操作的一些使用案例。 | CSAEM |
| 2022 年 5 月 | [在旋轉傳送器中顯示多個PDF文檔](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/display-pdf-in-carousel.html?lang=en) | 影片 | 瞭解在提交表單之前將多個PDF文檔顯示到表單填充器中以供審閱的常用案例。 | AEM Forms |
| 2022 年 5 月 | [無頭圖AEM像](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/images.html) | 影片 | 瞭解如何利用影像開發AEM豐富、極具吸引力的無頭體驗等。 | AEM Headless |
| 2022 年 5 月 | [帶無頭的富AEM文本](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/localized-content.html) | 影片 | 瞭解如何使用「多行文本」欄位，這是一種內容片段的資料類型，使作者能夠建立富文本內容。 | 無AEM頭 |
| 2022 年 5 月 | [專用輸出 IP 位址](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/dedicated-egress-ip-address.html) | 影片 | 了解如何設定及使用專用輸出 IP 位址，此位址允許來自 AEM 的輸出連線源自於專用 IP。 | CSAEM |
| 2022 年 5 月 | [部署代碼](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/deploy-code.html) | 影片 | 瞭解如何在as a Cloud Service中使用Cloud Manager管道將代碼部署到生產AEM中。 | CSAEM，雲管理器 |
| 2022 年 5 月 | [禁用後處理工作流執行](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/asset-microservices-configure-and-use.html#disable-post-processing-workflow-execution) | 文件 | 瞭解如何在不需要後處理時在「自動啟動工作流」(Auto-start Workflow)部分建立空的工作流模型。 | CSAEM |
| 2022 年 5 月 | [水印](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/watermarks.html?lang=en) | 影片 | AEMas a Cloud Service的水印功能允許使用任何PNG影像對自定義影像格式副本加水印。 | AEM Assets |

{style=&quot;table-layout:auto&quot;&quot;

### Experience Manager 版本資訊

所有 Experience Manager 的版本注意事項都會保留在以下頁面：

* [Experience Manager as a Cloud Service 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hant)
* [Experience Manager Cloud Manager 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hant)
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
* [Cloud Manager 使用手冊](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=zh-Hant)
* [Experience Manager 6.5 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hant)
* [Experience Manager 6.4 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=zh-Hant)
* [Experience Manager 6.3 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant)
* [Experience Manager 6.2 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant#previous-updates)
* [舊版 Experience Manager 文件](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic 說明首頁](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hant)
* [Experience Manager 文件：最近更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hant#aem-as-a-cloud-service)

## ![圖示](/assets/ec_appicon_24.png) 適用於 Adobe Experience Manager 的 XML 文件 {#xml-doc}

Adobe Experience Manager 的 XML 文件是部署至 AEM 的應用程式。這是一個功能強大、企業級元件內容管理解決方案 (CCMS)；此解決方案啟用 Adobe Experience Manager 的原生 DITA 支援、使 AEM 能夠處理以 DITA 為主的內容建立和傳遞。

了解更多關於 [AEM 的 XML 文件](https://www.adobe.com/tw/products/xml-documentation-for-experience-manager/features.html)。

### 其他資源

* [適用於 Adobe Experience Manager 的 XML 文件](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=zh-Hant) - Experience League 上的教學課程。
* [適用於 Adobe Experience Manager 的 XML 文件學習與支援](https://helpx.adobe.com/tw/support/xml-documentation-for-experience-manager.html) - 產品文件

## ![圖示](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

請參閱以下 Adobe Commerce 版本注意事項連結：

* [Adobe Commerce 和 Magento Open Source 2.4.x 版本注意事項](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 版本注意事項](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![圖示](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新時間： **2022年5月9日**

* 如需搶鮮版資訊，請參閱 [Adobe Target 搶鮮版](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)。
* 如需目前版本資訊，請參閱 [Adobe Target 版本注意事項](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hant)。

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新 Campaign 產品版本

瞭解中有關最新功能、改進和修復的詳細資訊 [市場活動v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hant)。 [市場活動v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html), [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hant) 發行說明。

### Campaign 說明資源

* Adobe Campaign v8：[文件](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hant)
* Adobe Campaign Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hant) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [操作說明影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hant)- [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hant) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hant) 操作說明影片

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

有了 Journey Optimizer，您就可以從單一應用程式為幾百萬名客戶管理排程的全通路行銷活動及一對一時刻，還有智慧型決策和見解讓整個旅程最佳化。

### 最新 Journey Optimizer 產品版本

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hant)中最新功能、改進功能和修正。

### Journey Optimizer 教學課程和課程 {#tutorials-ajo}

最新的 Journey Optimizer 教學課程：

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 5 月 | [建立決定規則](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-rules.html?lang=en) | 影片 | 瞭解如何針對決策管理建立決定規則。 規則或 _決策規則_ 是個性化服務所需的構件之一。 |
| 2022 年 5 月 | [建立位置](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-placements.html) | 影片 | 瞭解決策管理如何建立版位。 版位是優惠方案的建置區塊元件之一。 刊登版位是內容類型和管道的組合，例如電子郵件中的影像或網站上的 HTML 程式碼。 |
| 2022 年 5 月 | [建立決定](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-decisions.html) | 影片 | 瞭解如何為決策管理建立決策。 決策會將您的刊登和收藏合併為一個實體，決策會傳遞最相關的活動內容給客戶。 |
| 2022 年 5 月 | [使用 Decisions Hub API 傳遞優惠方案](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/deliver-offers-with-the-decisions-api.html) | 影片 | 了解如何使用 Decisions Hub API 傳遞優惠方案。 |
| 2022 年 5 月 | [建立後備優惠方案](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-fallback-offers.html) | 影片 | 瞭解如何建立用於決策管理的遞補優惠方案。 回退優惠是預設優惠，顯示給不符合您任何個性化優惠條件的客戶。 |
| 2022 年 5 月 | [建立集合](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/create-collections.html?lang=en) | 影片 | 瞭解如何為決策管理建立集合。 集合用於管理邏輯組中的服務，並且是為決策管理活動而構建的集合 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Journey Optimizer] 的更多資源

* [Journey Optimizer 文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hant)
* [決策管理文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html) - [最新文件更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hant)

## ![圖示](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

運用 Experience Platform 聰明地即時預測每個人的需求，在不同體驗管道大規模地協調客戶歷程。

### 最新 [!DNL Journey Orchestration] 產品版本

進一步了解 [[!DNL Journey Orchestration]  版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hant)中最新功能、改進功能和修正。

#### [!DNL Journey Orchestration] 的更多資源

* [Journey Orchestration 文件](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hant)

## ![圖示](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是適用於潛在客戶管理以及想要透過參與複雜購買旅程的每個階段來轉換客戶體驗的 B2B 行銷人員的完整應用程式。

新發佈的視頻Experience League:

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 5 月 | [Marketo技能交流](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | 影片 | 首先瞭解您的Marketo路線圖。 然後，發現將您的Marketo實例視為產品的重要性。 在此新發佈的內容中，獲取有關如何釋放程式成員自定義域的潛力、Marketo Engage提示和技巧等的建議 [Marketo技能交流](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) 從2021年8月開始，現在Experience League。 |

### Marketo Engage 核心更新

如需最新發行排程資訊和版本注意事項，請參閱[!DNL Marketo Engage] [發行排程](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hant)。

## ![圖示](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] 是統一的工作管理應用程式，用於共用構想、建立內容、管理複雜的流程並執行其最佳工作。

請參閱 [[!DNL Workfront]  發行版本](https://one.workfront.com/s/product-releases)頁面，以取得所有產品的最新資訊匯總。

## ![圖示](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 版本注意事項。

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [ [!DNL Advertising Cloud Search] 中的新功能](#adcloud-search)

<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

<!--
### New features in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Custom Reports | You can now create and manage [!DNL Amazon S3] and different types of FTP delivery locations, called *[!DNL report destinations]*, for your custom reports. Once you configure report destinations, you can set up each of your new custom reports to be delivered to one or more locations of a single destination type, or to email recipients. Updates to your [!DNL Amazon S3] and FTP credentials won't interrupt report delivery.<br><br>Your existing reports are still sent to the specified email recipients. To configure delivery to a different report destination, create a report with the new destination. |
| [!UICONTROL Packages], [!UICONTROL Placements], and [!UICONTROL Ads] views| When you view data for a single day, the trend charts now include hourly data. Hold the cursor over any point to see the data for that hour. |
| [!UICONTROL Placements] | The placement [!UICONTROL Inspector] now includes an [!UICONTROL Inventory] tab, which shows all deals and their associated metrics for the placement. Use the information to make quick adjustments or troubleshoot issues without generating a custom report. |
| [!UICONTROL Ads] | (Users with permission to include Clearcastclock numbers in their ads) DSP no longer shows an error if you use a clock number that's attached to another ad. **Note:**  The best practice is to use a unique clock number for each video ad. Otherwise, the publisher does not approve all the ads. |
| [!UICONTROL Deal IDs] | The [!UICONTROL Deal ID] settings and other places in the user interface reflect new branding for [!DNL Magnite] SSP:<br><ul><li>The SSP [!DNL Tremor] ([!DNL Telaria]) is now [!DNL Magnite CTV].</li><li>In the coming weeks, [!DNL Rubicon] will change to [!DNL Magnite DV+], where [!DNL DV+] stands for display, video, and other formats such as audio.</li></ul> |
| [!DNL Freewheel] programmatically guaranteed deals | You can now find the status of ads for [!DNL Freewheel] programmatically guaranteed deals from the [!UICONTROL Ads] view. Previously, you could check the status only from the [!UICONTROL Deals] view. |
-->

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search}

上次更新日期：**** 2022 年 14 月 12 日 (5 月 5 日發行版)

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 行銷活動] | 所有廣告商都可使用以下測試版功能：<ul><li>([!DNL Microsoft® Advertising] 帳戶) 為您在 [!DNL Microsoft® Audience Network] 上的現有原生廣告宣傳動提供同步、唯讀可見度和報告 (包括瀏覽資料) 支援，其中也包括 [!DNL Microsoft® Audience Ads]。</li><li>([!DNL Google Ads] 和 [!DNL Microsoft® Advertising] 帳戶)能夠導入 [!DNL Google Ads] 市場活動和市場活動結構 [!DNL Microsoft® Advertising] 從 [!UICONTROL 搜索] > [!UICONTROL 工具] > [!UICONTROL 導入市場活動測試版]。<br><br>導入市場活動後，您可以檢查導入作業的狀態、複查任何錯誤日誌，以及編輯、暫停或刪除導入計畫。</li></ul> |
| [!UICONTROL 行銷活動]<br><br>[!UICONTROL 組合] | ([!DNL Microsoft® Advertising] 市場活動)現在所有用戶都可使用以下競價策略：<ul><li>[!UICONTROL 目標印象共用]:您可以使用此策略配置市場活動，並根據需要設定目標印象共用、目標廣告位置和每次按一下的最大成本。 警告：混合投資組合尚不支援此選項，因此無法將其新增到標準投資組合中。</li><li>[!UICONTROL 最大化點擊率]:您可以使用此策略配置市場活動，並可選擇設定每次按一下的目標最大成本。 您可以在標準或混合投資組合中加入採用此策略的行銷活動。若要在混合組合中使用此策略，組合的目標必須僅包含 [!DNL Adobe] 屬性 (量度)，並且您必須啟用將 Advertising Cloud Search 目標上傳到 [!DNL Microsoft® Ads]。</li></ul> |
| 與 Adobe Analytics 整合 | （4月7日）在Advertising Cloud發送給 [!DNL Analytics]，資料 [!DNL Google Ads] 動態搜索廣告僅可從2022年5月7日開始直至廣告組級別。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

專為 Adobe Document Cloud 發佈的新教學課程和課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 5 月 | [共用帳戶訪問](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/share-account-access.html) | 影片 | 瞭解如何設定對其他用戶帳戶中事務的僅查看訪問權限。 | [!DNL Acrobat Sign] |
| 2022 年 5 月 | [管理文檔模板](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-managing/edit-a-template.html?lang=en) | 影片 | 瞭解如何編輯或刪除庫中的模板。 | [!DNL Acrobat Sign] |
| 2022 年 5 月 | [在Microsoft® Power Automate中建立您的第一流](https://experienceleague.adobe.com/docs/document-services/tutorials/pdfservices/create-workflow-power-automate.html?lang=en) | 文章 | 瞭解如何使用Microsoft®電源自動化連接器在Adobe PDF®電源自動化中建立您的第一個流。 | Document Services |
| 2022 年 5 月 | [獲取Microsoft® Power Automate的憑據](https://experienceleague.adobe.com/docs/document-services/tutorials/pdfservices/getting-credentials-power-automate.html?lang=en) | 文章 | 瞭解如何獲得證書以開始使用或試用Adobe PDF服務。 根據您是試用用戶還是現有客戶，本教程將介紹獲得憑據的正確步驟。 | 文檔服務 |

{style=&quot;table-layout:auto&quot;&quot;

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hant)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hant)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)

## ![圖示](/assets/creative-cloud-24.png) 適用於企業的 Adobe Creative Cloud {#creative-cloud}

如需了解最新教學課程，請參閱「[適用於企業的 Creative Cloud 教學課程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hant)」。

## ![圖示](/assets/experience-league.png) 客戶資料管理 - 對話 {#voices}

身為客戶資料管理技術和行銷實務主管和專家的您，[客戶資料管理對話](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=zh-Hant)是您的最終目的地。此教學課程集合是您聆聽同行的意見、獲取靈感並了解 MarTech 中發展的一站式中心。不用報名，按一下即可觀看。

## ![圖示](/assets/experience-league.png)數位體驗藍圖 {#blueprints}

[數位體驗藍圖](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=zh-Hant)是可重複的實施，可讓您處理策略，並快速解決既定的業務問題。每個藍圖都提供一系列成品，解釋高價值業務問題、架構、實施步驟、技術考量以及相關文件的連結。

[頁面頂端](#events)
