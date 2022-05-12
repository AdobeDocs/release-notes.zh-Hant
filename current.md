---
title: 最新發行說明
description: 了解  [!DNL Experience Cloud]  產品和服務的最新版本注意事項、新功能和新文件。尋找有關 [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和 [!DNL Document Cloud] 最新的說明與教學課程
doc-type: release notes
last-update: April 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: cdf35cca137c192dfc32398565b693e4843b6418
workflow-type: tm+mt
source-wordcount: '6061'
ht-degree: 96%

---

# Adobe Experience Cloud 發行說明 - 2022 年 4 月

![橫幅](assets/experience-cloud-banner-3.png)

身為 Experience Maker，您的成功之道始於 [Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home)。Find a vast how-to documentation library, self-guided tutorials, how-to videos, and courses for all levels and roles, an online community of peers, and expert sup  port when you need it.

準備好開始使用了嗎？[進行 5 分鐘測驗並獲勝](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)！

>[!NOTE]
>
>若要收到關於本頁更新的每月電子郵件通知，請訂閱 [Adobe 優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)。 請經常回來查看，持續了解 Experience League 最新消息。

上次更新日期：**2022 年 4 月 22 日**

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

需要協助嗎？ 請造訪 [Adobe Experience League](https://experienceleague.adobe.com/#home)，了解產品和技術文件、Adobe 策畫的課程、教學課程影片、快速解答、社群見解，以及由講師授課的訓練課程。

## ![圖示](/assets/experience-league.png) [!DNL Experience League] 活動 {#events}

若想學習、互動和了解 Adobe 產品專家的答案，Experience League 活動會是個好選擇！

**2022 年 5 月 11 日**&#x200B;更新

| 活動 | 類型 | 說明 |
| -----------|---------- | ----|
| 活動 | 類型 | 說明 |
| — | — | — |
| [使用Journey Optimizer推送通知 — 如何輕鬆配置移動應用以推送](https://www.youtube.com/watch?v=t36Xjhukmro) | Experience League LIVE | 瞭解與Adobe Journey Optimizer一起使用推送通知的常見使用案例，並深入瞭解如何配置由Adobe Experience Platform支援的推送應用的技術詳細資訊。 <br>**日期：** 2022年5月12日上午9:30<br>[計畫和過去事件](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hant) |
| [Adobe Target社區](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/at-community-q-amp-a-coffee-break-4-27-22-8am-pt-jim-mctiernan/m-p/446940#M3096) | Q&amp;A Coffee Break | 加入Adobe Target產品團隊的Brent Kostak和Drew Burns ，他們將回答您的Adobe Target問題，包括共用受眾、Real-Time CDP、第一方資料、端到端個性化工作流等。<br>觀看最近 [即時個性化網路研討會](https://experienceleaguecommunities.adobe.com/t5/adobe-target-discussions/upcoming-webinar-4-28-22-real-time-personalization-with-adobe/td-p/449012) 並將後續問題提交專家 [斷咖啡線](https://adobe.ly/3MyiDHa) 在Adobe Target社區！<br>**日期：** 2022年5月25日早8時<br>[詳細資訊和註冊](https://adobe.ly/3MyiDHa) |
| [Adobe [!DNL Developers Live]:商業](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2022/feb2022/overview.html?lang=en) | 按需視頻 | _Adobe Developers Live:商業2022_ 將擁有不同背景和獨特目的的開發商和經驗建築商聚集在一起，創造出令人難以置信的端到端體驗。 這一為期一天的虛擬會議具有重要的商務和開源開發人員更新、技術會議、社區網路機會等功能。 |
| [Adobe Summit2022](https://business.adobe.com/summit/adobe-summit.html) | 按需會話 | 向Adobe執行官，瑞恩雷諾茲，羅莎琳德布魯爾，沃爾格林靴子聯盟公司首席執行官，耐克公司首席執行官約翰多納霍和蓋爾J學習。麥戈文，美國紅十字會首席執行官，他們分享客戶體驗是我們數字經濟的貨幣。<br>瀏覽 [按需會話](https://business.adobe.com/summit/2022/sessions.html) 2022年Adobe Summit。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]會提供有關 Adobe 產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。 請造訪 [status.adobe.com](https://status.adobe.com/) 來查看。

如需最新發行資訊，請參閱 Adobe 系統狀態[發行說明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=zh-Hant#status)。

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud - 中央介面元件和管理 {#ecloud}

Experience Cloud [中央介面元件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hant)包含首頁上可用的功能和永續性產品標題。這些功能包含用戶基本資料設定、偏好設定和搜尋。您也可以找到用戶和產品管理、客戶屬性、和 Experience Cloud Audiences 的說明。

| 功能 | 說明 |
| ------- |-------|
| 自然語言搜尋 | 通過統一搜索的單一介面即時獲得所有幫助問題的答案。 此功能始終可在Experience Platform和Journey Optimizer的每一頁上提供。 |

{style=&quot;table-layout:auto&quot;&quot;

**更多有關 [!DNL Experience Cloud Central UI Components] 與管理的說明資源**

* Experience Cloud Central UI Components [發行說明](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=zh-Hant)
* Experience Cloud (管理) [使用者和產品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)
* Places Service [發行說明](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hant)
* [People - 客戶屬性和對象庫](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hant)產品文件
* [整合式搜尋物件和實體](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=zh-Hant)

## ![表徵圖](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform]

發行日期：**2022 年 4 月 27 日**

* [Experience Platform 發行說明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant)

### 新 [!DNL Experience Platform] 教學課程和其他課程 {#tutorials-platform}

為發佈的新視頻教程、文章和課程 [!DNL Experience Platform]。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 4 月 | [Adobe Experience PlatformPrivacy Service入門](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2021.1.prvsvc) | 課程 | 學習Adobe Experience Platform [!UICONTROL Privacy Service]，包括如何準備資料以進行隱私操作，以及如何向服務發送客戶隱私請求。 |
| 2022 年 4 月 | [Adobe Experience Platform邊緣網路伺服器API](https://experienceleague.adobe.com/docs/platform-learn/data-collection/server-api/overview.html) | 影片 | 瞭解將資料發送到平台的好處 [!UICONTROL 邊緣網路] 使用安全、經過身份驗證的伺服器API。 |
| 2022 年 4 月 | [審核日誌](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-governance/audit-logs.html) | 影片 | 瞭解審核日誌功能如何幫助您滿足合規性要求並排除Adobe Experience Platform實施的故障。 |
| 2022 年 4 月 | [資料收集的資料準備](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/data-prep.html) | 影片 | 瞭解如何將資料層添加到中的新資料流 [!UICONTROL 資料收集]。 另外，瞭解如何使用 [!UICONTROL 資料收集的資料準備] 的子菜單。 |
| 2022 年 4 月 | [考慮將客戶端供應商標籤移動到事件轉發](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/consider-moving-tags.html) | 影片 | 瞭解如何評估客戶端供應商標籤以潛在地將其移動到事件轉發屬性。 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Adobe Mobile] SDK

如需了解 Adobe Experience Platform Mobile SDK，請參閱[版本注意事項和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期：**2022 年 4 月 20 日**

* [](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hant)
* Adobe Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)

### AppMeasurement {#appm}

發行版本：**2.22.4**

* [JavaScript 適用的 AppMeasurement 發行說明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)

### 新 [!DNL Analytics] 教學課程和其他課程 {#tutorials-analytics}

為Adobe Analytics發佈的新視頻教程、文章和課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 4 月 | [使用自定義分段和日期篩選資料](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.filterdata) | 課程 | 瞭解如何應用段、建立自定義段以及使用日期範圍在分析中更明智地工作。 |
| 2022 年 4 月 | [配置和管理Adobe Analytics的報告套件](https://experienceleague.adobe.com/?recommended=Analytics-A-1-2021.1.administration) | 課程 | 瞭解如何設定常規報告套件配置項、配置通信量和轉換變數、設定市場營銷渠道等。 |
| 2022 年 4 月 | [](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/telling-impactful-stories-with-data.html?lang=en) | 影片 | 當藝術和科學使用資料、視覺效果和敘述融合在一起，即可用資料述說故事。By effectively telling a story with data, Adobe Analytics can become more approachable to a wider audience, and you can increase the value you bring to your organization through data-driven decision making. |
| 2022 年 4 月 | [](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/gaining-a-seat-at-the-table.html?lang=en) | 影片 | 瞭解您作為分析管理員的角色，並獲取有關如何獲得專業知識的提示，以幫助您在業務決策表中獲得一席之地。 |
| 2022 年 4 月 | [](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/translating-adobe-analytics-technical-language.html?lang=en#) | 影片 | As your organization’s Adobe Analytics expert, you are key to helping your stakeholders understand the technical details and make the most out of your Adobe Analytics investment. |
| 2022 年 4 月 | [Analysis Workspace 中的快速區段](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/applying-segments/quick-segments-in-analysis-workspace.html?lang=en) | 影片 | __Learn how to build on-the-fly segments with up to three rules without having to leave your analysis workflow. |
| 2022 年 4 月 | [Analysis Workspace 中的註解](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/annotations-in-analysis-workspace.html?lang=en) | 影片 | 瞭解如何使用已知的資料問題、公共假日和活動啟動來注釋日期或日期範圍，以便更好地告知用戶他們為什麼在折線圖、表格等中看到內容。 |
| 2022 年 4 月 | [跨功能工作](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/working-cross-functionally.html?lang=en) | 影片 | 向一位Adobe Analytics冠軍學習如何在您的組織中跨職能部門工作。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

發行日期：**2022 年 4 月 20 日**

* [](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hant)
* Customer Journey Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hant)

## ![圖示](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

發行日期：**2022 年 4 月 20 日**

* [!DNL Streaming Media Analytics][](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=en)****
* [!DNL Streaming Media Analytics][](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=en)

### 新的Customer Journey Analytics教程和課程 {#tutorials-cja}

為Customer Journey Analytics發佈的新視頻教程、文章和課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 4 月 | [配置資料視圖以進行Customer Journey Analytics](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/overview-of-configuring-data-views-for-cja.html?lang=en) | 影片 | 瞭解配置 [!UICONTROL 資料視圖] Customer Journey Analytics。 [!UICONTROL 資料視圖] 與 [!UICONTROL 虛擬報告套件] 在Adobe Analytics。 它們允許您配置傳入資料，以便它對您的報告和分析最有用。 |
| 2022 年 4 月 | [CJA中的連接詳細資訊體驗](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections-details-experience-in-cja.html?lang=en) | 影片 | 瞭解如何檢查連接資料集和攝取過程的狀態。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

Audience Manager 中的修正與改良：

| 改善 | 說明 |
| -----------| ---------- |  
| 屬於其他公司的目標資料來源的驗證器 | Audience Manager 已發佈[批次資料上線流程](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=zh-Hant)的改善。為了防止檔案和資料意外上線至其他合作夥伴擁有的目標資料來源，Audience Manager 以在合作夥伴 ID (PID) 與其他合作夥伴擁有的資料來源 (DPID) 之間新增對應需求。 <ul><li>另請參閱[輸入資料檔案的 Amazon S3 名稱和檔案大小需求](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=zh-Hant#name-elements)中的 __DPID_TARGET_DATA_OWNER_ 欄位。</li><li>如需新的對應需求改善和如何請求新對應的詳細資訊，Adobe 內部顧問和客戶服務應閱讀[管理第二方資料的上線存取](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=zh-Hant)</li><li>_不_&#x200B;一定要請求現有資料共用關係的對應。將資料上線至屬於您的 PID 的目標資料來源時，也&#x200B;_不_&#x200B;一定需要對應。</li></ul> |

{style=&quot;table-layout:auto&quot;&quot;

如需自助資源，請參閱 Experience League 上的 [Audience Manager 文件與教學課程](https://experienceleague.adobe.com/docs/audience-manager.html?lang=zh-Hant)。

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe 建議您造訪 [Experience Manager 版本更新與藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hant)頁面，以掌握最新的版本資訊。

### Experience Manager 產品發行

* **Experience Manager as a Cloud Service**

   [](https://video.tv.adobe.com/v/341465)<!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [2022 年 1 月版本總覽新功能](https://video.tv.adobe.com/v/340120)影片。
   * [2021 年 12 月版本新功能的總覽影片](https://video.tv.adobe.com/v/339278)。
   * [](https://video.tv.adobe.com/v/338253)2021 年 10 月版本總覽 新功能影片。
   * [](https://video.tv.adobe.com/v/337381)2021 年 9 月版本總覽 新功能影片。

* **Experience Manager Assets as a Cloud Service**

   __

   * [](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=zh-Hant)This update positively impacts SEO to reflect updates made to your business context, such as rebranding.
   * 現在可以使用 Experience Manager Assets 使用者介面以便：
      * [](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-digital-assets.html?lang=en#detect-duplicate-assets)
      * [](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/watermark-assets.html?lang=en)
   * The administrators can now configure email service for large downloads. 它可讓使用者從 Experience Manager Assets 介面[啟用大量下載的電子郵件通知](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=zh-Hant#enable-email-notifications-for-large-downloads)。使用者在完成下載後會收到電子郵件通知，其中包含封存 zip 檔案夾的下載連結。
   * [管理發佈](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hant)功能有改進的使用者介面。[](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hant#add-content)[](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hant#include-folder-settings)[](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hant#publish-assets-later)

      _Experience Manager Assets 發行前管道中的新功能_

   * 你可以 [排序標籤](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/organize-assets.html?lang=en#use-tags-to-organize-assets) 建立智慧標籤時，以及使用標籤謂詞應用搜索篩選器時。

* **Experience Manager Forms as a Cloud Service**

   _Forms 的新增功能_

   * **通信 — 文檔生成API** — [文檔生成API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=zh-Hant) 幫助合併、重新排列和驗證PDF文檔。 此服務可讓您以同步模式產生文件。 The APIs lets you create applications to do the following:

      * 匯編PDF文檔
      * 拆卸PDF文檔
      * 轉換為並驗證符合PDF/A的文檔。
   * **自動將超過15頁的PDF forms轉換為自適應表單**  — 現在，您可以使用automated forms conversion服務將最多40頁的PDF forms轉換為自適應表單。 現在，該服務提供了將超過15頁的表單部分轉換為自適應表單片段的選項。 它有助於提高轉換表單的渲染速度，並使在自適應表單編輯器中載入大型表單更加容易。

   _Forms 發行前管道的新增功能_

   * **使用自定義XCI生成記錄文檔**  — 現在，您可以使用自定義XCI檔案來設定記錄文檔的各種屬性。 它用自定義更改覆蓋主XCI。
   * **以自適應形式使用不可見的驗證碼**  — 只有在發現可疑活動時，您才能使用不可見的驗證碼查來顯示驗證碼詢問。 如果未發現可疑活動，則不顯示驗證碼質詢。



* **CIF附加**

   _新功能_

   * Beta -Experience ManagerCIF搜索核心元件支援Commerce LiveSearch。
   * 針對多儲存場景的改進SEO — 現在可以通過CIF雲配置屬性在儲存級別上配置PDP/PLP的URL格式。
   * 產品選取器通過用戶介面中的新篩選器選項支援分階段產品。 此功能使內容從業人員能夠為即將推出的產品準備產品內容管理。
   * 使用CIF雲配置名稱（而不是配置代理URL）簡化CIF配置管理和錯誤處理。
   * 產品清單和旋轉傳送元件的手動類別選擇。 此功能允許內容從業人員在目錄體驗之外的內容頁面上使用這些元件。

* **Experience Manager as a Cloud Service 基礎**

   _新功能_

   * 為了更高效、更高效地排除雲環境中的自定義功能，Adobe發佈了一款新的開發人員工具： [儲存庫瀏覽器](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developer-tools/repository-browser.html?lang=en)。 它是一個輕量、只讀、HTML瀏覽器，您可以從開發人員控制台啟動。 瞭解發佈者、作者和預覽層以及所有環境（包括生產、舞台和開發）中的內容儲存庫。 瀏覽內容結構、查看屬性以及預覽和下載二進位檔案。
   * 現在，用於驗證伺服器到伺服器API調用（例如，GraphQL API請求）的憑據可以在開發人員控制台以自助服務方式過期之前刷新。 查看 [文檔](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/generating-access-tokens-for-server-side-apis.html?lang=en#refresh-credentials) 的子菜單。
   * 版本清除和審核日誌清除維護任務（以前未啟用）現在已為新環境啟用。 請參閱 [維護任務](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/maintenance.html?lang=en) 文章。
   * Experience Manageras a Cloud ServiceSDK Dispatcher Tools現在支援帶有M1晶片的Mac電腦。

* **Cloud Manager**

   _發行日期_

   The release date for Cloud Manager in Experience Manager as a Cloud Service 2022.02.0 was 10 February 2022.
下一版計劃於 2022 年 3 月 10 日發行。

   _新功能_

   * 新加速 [Web層配置管道](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/cicd-pipelines/introduction-ci-cd-pipelines.html?lang=en#web-tier-config-pipelines) 已引入專門部署HTTPD/dispatcher配置。

      * 您必須處於版AEM本 `2021.12.6151.20211217T120950Z` 或更新 [選擇Dispatcher工具的靈活模式](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/content-delivery/disp-overview.html?lang=en#validation-debug) 功能。
      * 該功能計畫在發佈後的兩週內分階段推出2022.02.0版。
   * Cloud Manager登錄頁體驗已刷新，可提供改進的導航、網格/平鋪視圖之間的輕鬆切換，以及彈出窗口，以快速獲得程式摘要。
   * 新的失敗閾值(`< D`)已添加到 [可靠性評定指標](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/test-results/code-quality-testing.html?lang=en#understanding-code-quality-rules)。

      * 存在嚴重質量問題且影響系統穩定性的客戶在這些問題得到解決之前無法部署。
   * UnpandedPath的嚴重性 [質量規則](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/test-results/code-quality-testing.html?lang=en#understanding-code-quality-rules) 已從阻止程式更改為關鍵。
   * 在配置Experience Manager環境之前，當需要管道環境更新時，管道嚮導通知用戶 [Web層配置管道](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/cicd-pipelines/introduction-ci-cd-pipelines.html?lang=en#web-tier-config-pipelines) 關聯。


### 社群

* **即將推出的Experience ManagerGEM網路研討會**

   * 主題： _集AEM成和CIF框架，構建豐富而逼真的電子商務體驗_
      * 日期：2022年4月27日星期三
      * 時間：上午8:00 PDT /下午5:00 CET / 8:30 PT
      * [按一下這裡報名](https://adobe.ly/3O0uXl5)
   * Adobe Summit2022 |完成會話清單和錄制 [此處](https://adobe.ly/3rti6gF)。

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 產品 |
| ------| ----- | ------ | ------ |-----|
| 2022 年 4 月 | [使用通信API生成文檔](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2022.3.formscs) | 課程 | 通過調用FormsCS的HTTP端點，將資料與xdp模板合併。 | AEM Forms |
| 2022 年 4 月 | [使用調用DDX操作裝配PDF](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-cs-assembler/introduction.html?lang=en) | 影片 | 儲存庫瀏覽器是一種功能強大的工具，可AEM以查看基礎資料儲存，從而輕鬆調試AEMas a Cloud Service環境。 儲存庫瀏覽器支援檢查生產、階段和開AEM發服務以及作者、發佈和預覽服務上的所有資源和屬性。 | AEM CS |
| 2022 年 4 月 | [實施解決方案以保存和檢索信件實例](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/store-retrieve-letters/introduction.html?lang=en) | 影片 | 瞭解如何使用SPI來保存和檢索互動式通信的字母實例。 | AEM Forms |
| 2022 年 4 月 | [建立和驗證PDF/A文檔](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/forms-cs-assembler/pdfa-utilities.html?lang=en) | 影片 | 瞭解如何建立和驗證PDF/A文檔。 PDF/A是ISO標準化的攜帶型文檔格式(PDF)版本，專門用於電子文檔的歸檔和長期保存。 | AEM Forms |
| 2022 年 4 月 | [將 AEM Forms與 [!DNL ServiceNow]](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/service-now.html?lang=en)整合 | 影片 | 使用AEM Forms的表單資料模型在ServiceNow中建立和顯示事件。 | AEM Forms |
| 2022 年 4 月 | [資產總覽](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/overview.html) | 教學課程 | Adobe Experience ManagerAEM( [!DNL Assets] 是一個位於平台上的數字資產管理工具AEM，允許用戶在基於Web的儲存庫中建立、管理和共用其數字資產（影像、視頻、文檔和音頻剪輯）。 This user guide contains videos and tutorials on the many features and capabilities of AEM Assets. | AEM Assets |
| 2022 年 4 月 | [Assets Essentials權限管理](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/permissions-management.html) | 影片 | 瞭解AEM Assets軟體包的權限管理如何使組織能夠控制對資產的訪問、保護其品牌並確保法規遵從性。 | AEM Assets |
| 2022 年 4 月 | [元資料Forms在Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/metadata-forms.html) | 影片 | 瞭解如何快速、輕鬆地配置Assets Essentials元資料Forms以定制資產。 | AEM Assets |
| 2022 年 4 月 | [在Adobe Experience ManagerHeadless中使用富文本](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/how-to/rich-text.html) | 影片 | 瞭解如何在Headless中使用富AEM文本。 「多行」文本欄位是「內容片段」的資料類型，它使您能夠建立富格文本內容。 | AEM Headless |
| 2022 年 4 月 | [使用儲存AEM庫瀏覽器調試as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/debugging/debugging-aem-as-a-cloud-service/repository-browser.html) | 影片 | 瞭解儲存庫瀏覽器，它是一種功能強大的工具，可AEM以查看基礎資料儲存，從而輕鬆調試AEMas a Cloud Service環境。 | CSAEM |
| 2022 年 4 月 | [專用出口IP地址](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/networking/dedicated-egress-ip-address.html) | 影片 | 瞭解如何設定和使用專用出口IP地址，該地址允許從專用IPAEM發出出站連接。 | CSAEM |

{style=&quot;table-layout:auto&quot;&quot;

### Experience Manager 版本資訊

所有 Experience Manager 的發行說明都會保留在以下頁面：

* [Experience Manager as a Cloud Service 發行說明](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hant)
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

* [Adobe Commerce 和 Magento Open Source 2.4.x 發行說明](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 發行說明](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的 Adobe Commerce 資源 {#new-commerce}

適用於 Experience League 上 Adobe Commerce 的新文件和教學課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 4 月 | [升級相容性工具概覽](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade/upgrade-compatibility-tool-overview.html) | 影片 | 瞭解升級相容性工具，以及它如何幫助您快速識別升級到新版Adobe Commerce所需的錯誤和修復。 |
| 2022 年 4 月 | [在 PhpStorm 上使用升級相容性工具](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade/uct-phpstorm.html) | 影片 | 升級相容性工具(UCT)是一個免費工具，可在幾分鐘內分析當前版本和目標升級版本之間的不相容情況。 Adobe提供了PhpStorm插件，使工具更易於使用。 |
| 2022 年 4 月 | [即時搜索指南](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/guide-overview.html) | 產品文件 | 來自Adobe Commerce的Live Search可提供超快、超相關和直觀的搜索體驗，並可免費為Adobe Commerce提供。 |
| 2022 年 4 月 | [產品Recommendations指南](https://experienceleague.adobe.com/docs/commerce-merchant-services/product-recommendations/guide-overview.html) | 產品文件 | This guide is intended for administrators of Adobe Commerce. It includes detailed information about installation and onboarding of Product Recommendations, as well as configuration and management of the services. |
| 2022 年 4 月 | [[!DNL Site-Wide Analysis Tool]](https://experienceleague.adobe.com/docs/commerce-operations/tools/site-wide-analysis-tool/intro.html?lang=en) | 文件 | 有關 [!DNL Site-Wide Analysis] 工具，包括其使用、安裝過程和訪問。 | Adobe Commerce |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新日期: **2022 年 3 月 21 日**

* 如需發行前版本資訊，請參閱 [Adobe Target 發行說明 (發行前)](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)。
* 如需目前版本資訊，請參閱 [Adobe Target 發行說明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hant)。

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新 Campaign 產品發行版

瞭解中有關最新功能、改進和修復的詳細資訊 [市場活動v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hant)。 [市場活動v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) 和 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hant) 發行說明。

### 新 [!DNL Campaign] 教學課程和其他課程 {#tutorials-campaign}

New video tutorials and courses published for Adobe Campaign.

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- | ----|
| 2022 年 4 月 | [利用Experience Manager內容增強您的電子郵件交付](https://experienceleague.adobe.com/?recommended=Campaign-A-1-2022.v8.aemcontent) | 課程 | Learn how to connect Adobe Campaign V8 with Adobe Experience Manager (AEM) to allow you to manage email delivery templates, assets, and forms in Experience Manager. | 第8版活AEM動 |
| 2022 年 4 月 | [稽核記錄](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/monitoring/audit-trail.html?lang=en) | 影片 | 瞭解如何存取稽核軌跡，以及可以設定哪些設定。 | Campaign v8 |

{style=&quot;table-layout:auto&quot;&quot;

### Campaign 說明資源

* Adobe Campaign v8：[文件](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hant) - [發行說明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hant)
* Adobe Campaign Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hant) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [做法影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hant)- [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hant) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hant) 做法影片

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

With Journey Optimizer, you can manage scheduled omnichannel campaigns and one-to-one moments for millions of customers from a single application--and the entire journey is optimized with intelligent decisioning and insights.

### 最新 Journey Optimizer 產品發行版

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hant)中最新功能、改良功能和修復。

### Journey Optimizer 教學課程和課程 {#tutorials-ajo}

最新的 Journey Optimizer 教學課程：

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 4 月 | [](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/message-designer-overview.html?lang=en) | 影片 |  |
| 2022 年 4 月 | [為開發人員提供的行動裝置功能](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/mobile-capabilities-for-developers.html) | 影片 | 瞭解 Adobe Journey Optimizer 為開發人員提供的行動裝置功能。 |
| 2022 年 4 月 | [Assets Essentials概述](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/assets-essentials-overview.html?lang=en) | 影片 | 概述Assets Essentials的功能及在Adobe Journey Optimizer的使用方式。 |
| 2022 年 4 月 | [歷程畫布概述](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/overview-over-the-journey-canvas.html?lang=en) | 影片 | 瞭解 Journey Canvas 的特性和功能。 |
| 2022 年 4 月 | [](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/profiles-segments-subscriptions/unified-profile-and-segmentation-overview.html?lang=en) | 影片 | 瞭解如何建立統一的配置檔案，然後根據配置檔案屬性構建段，以便個性化客戶歷程。 |
| 2022 年 4 月 | [為行銷人員提供的行動裝置功能](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/mobile-capabilities.html) | 影片 | 瞭解 Adobe Journey Optimizer 為行銷人員提供的行動裝置功能。 |
| 2022 年 4 月 | [建立個人化優惠方案](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/create-personalized-offers.html) | 影片 | 了解如何在 Offer Decisioning 中建立個人化優惠方案。個人化優惠具有與其相關的適用性規則，可協助您僅向相關客戶顯示。 |
| 2022 年 4 月 | [建立標籤](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/create-tags.html?lang=en) | 影片 | 了解如何在 Offer Decisioning 中建立標籤。標籤是優惠方案的選用基礎元件，可用來組織優惠方案，並在動態集合中將優惠方案分組。 |
| 2022 年 4 月 | [演示決策管理功能](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/demo-of-offer-decisioning.html?lang=en) | 影片 | 了解品牌如何使用決策管理功能來定義和管理他們的產品、套用即時客戶資料並提供客戶期望的正確體驗。 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Journey Optimizer] 的更多資源

* [Journey Optimizer 文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hant)
* [決策管理文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hant)

## ![圖示](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

運用 Experience Platform 聰明地即時預測每個人的需求，在不同體驗管道大規模地協調客戶歷程。

### 最新 [!DNL Journey Orchestration] 產品發行版

進一步了解 [[!DNL Journey Orchestration]  版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=zh-Hant)中最新功能、改良功能和修復。

#### [!DNL Journey Orchestration] 的更多資源

* [Journey Orchestration 文件](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [做法影片](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=zh-Hant)

## ![圖示](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] 是適用於潛在客戶管理以及想要透過參與複雜購買旅程的每個階段來轉換客戶體驗的 B2B 行銷人員的完整應用程式。

### Marketo Engage 核心更新

如需最新發行排程資訊和版本注意事項，請參閱「[!DNL Marketo Engage] [發行排程](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hant)」。

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

{style="table-layout:auto"}
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

<!--
{style="table-layout:auto"}
-->

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search}

上次更新日期：**2022 年 4 月 22 日** (4 月 23 日版本)

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 受眾] | (符合客戶比對資格的 [!DNL Microsoft Advertising] 資格的帳戶) 所有用戶現在都可以上傳附有電子郵件地址的 CSV 檔案來建立和管理客戶比對受眾。資料必須使用 SHA-256 演算法進行雜湊處理。 |
| [!UICONTROL 行銷活動] | 以下 Beta 版功能可供選擇加入的廣告商使用：<ul><li>([!DNL Microsoft Advertising] 帳戶) 為您在 [!DNL Microsoft Audience Network] 上的現有原生廣告宣傳動提供同步、唯讀可見度和報告 (包括瀏覽資料) 支援，其中也包括 [!DNL Microsoft Audience Ads]。</li><li>([!DNL Google Ads] 和 [!DNL Microsoft Advertising] 帳戶) 能夠從 Advertising Cloud Search 將您的[!DNL Google Ads] 行銷活動和行銷活動結構匯入 [!DNL Microsoft Advertising]。</li></ul>如果您有意願加入 Beta 版計劃，請連絡您的 Adobe 客戶經理。 |
| [!UICONTROL 行銷活動]<br><br>[!UICONTROL 組合] | ([!DNL Microsoft Advertising] 行銷活動) 支援適用於以下競標策略：<ul><li>(一般可用性) [!UICONTROL 盡量爭取轉換]、[!UICONTROL 目標 CPA] 和[!UICONTROL 目標廣告支出回報率]：這些策略現在可供所有人使用。您可以將具有這些競標策略的搜尋行銷活動新增到混合 (但不是標準) 組合中。</li><li>(Beta 版功能) [!UICONTROL 目標印象份額]：如果您正在參與混合最佳化 Beta 版，您可以使用此策略設定行銷活動，並可選擇設定目標印象份額、目標廣告位置和最高每次點按成本。警告：混合投資組合尚不支援此選項，因此無法將其新增到標準投資組合中。</li><li>(Beta 版功能) [!UICONTROL 最大化點按次數]：如果您正在參與混合最佳化 Beta 版，您可以使用此策略設定行銷活動，並可選擇設定目標最高每次點按成本。您可以在標準或混合投資組合中加入採用此策略的行銷活動。若要在混合組合中使用此策略，組合的目標必須僅包含 [!DNL Adobe] 屬性 (指標)，並且您必須啟用將 Advertising Cloud Search 目標上傳到 [!DNL Microsoft Ads]。</li></ul>如果您尚未參與混合最佳化 Beta 版並想加入，請連絡您的 [!DNL Adobe] 客戶經理。 |
| [!UICONTROL 廣告洞見] | 除了[!UICONTROL 查詢交叉比對]和[!UICONTROL 混合投資組合設定準備]之外的所有洞見，現在都已完成測試。 |
| [!UICONTROL 市場活動]<br><br>[!UICONTROL 廣告見解] | (4月11日； [!DNL Google Ads] 帳戶)Advertising Cloud Search已轉換舊版API調用 [!DNL Google AdWords API] 至 [!DNL Google Ads API]。 移到新 [!DNL Google Ads API] 確保現有功能的連續性並允許訪問 [!DNL Google’s] 最新 [!DNL Ads] 功能。<br><br>某些功能尚未更新到新API，暫時不可用：<ul><li>位置擴展：<ul>位置擴展在 [!UICONTROL 擴展] 的子菜單。</li><li>無法建立擴展。</li><li>對位置進行篩選不起作用。</li></li></ul><li>[!UICONTROL 廣告見解]:的 [!UICONTROL 《印象》] 和 [!UICONTROL 查詢交叉匹配Beta] 分析不可用。</li></ul>我們預計在4月底之前恢復位置擴展功能。 一旦我們確定受影響者 [!UICONTROL 廣告見解] 模組也可以恢復，我們將發送包含估計日期的更新。 |
| 與 Adobe Analytics 整合 | (4 月 7 日) 在 Advertising Cloud 傳送到 [!DNL Analytics] 的資料摘要中，[!DNL Google Ads] 和 [!DNL Microsoft Advertising] 回應式搜尋廣告 (RSA) 的資料在收到新點擊時被重新分類為[!UICONTROL 廣告類型]「[!UICONTROL 回應式搜尋廣告]」。以前，資料包含在[!UICONTROL 廣告類型]「[!UICONTROL 文字廣告]」中。非作用中行銷活動中的 RSA 不會被重新分類。<br><br>對於重新分類的 RSA，[!UICONTROL 回應式廣告標題]現在有第一個標題，[!UICONTROL 回應式廣告描述]現在有第一個描述。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

針對 Adobe Document Cloud 發佈的新教學課程和課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- | -----|
| 2022 年 4 月 | [Adobe Acrobat入門](https://experienceleague.adobe.com/?recommended=Acrobat-U-1-2021.1.acrobatgetstarted) | 課程 | 瞭解為什麼全球超過500萬家公司求助於Acrobat，建立無與倫比的數字文檔，推動業務向前發展。 發現自動化手動文檔工作流和創造令人滿意體驗的新方法。 | Adobe Acrobat |
| 2022 年 4 月 | [Adobe Acrobat高級任務](https://experienceleague.adobe.com/?recommended=Acrobat-U-1-2021.1.advancedtasks) | 課程 | 利用高級技術將您的Acrobat技能提升到新的水準，以編輯、處理表單、優化和自動化任務。 瞭解如何自動執行手動文檔工作流、保護敏感業務資訊，以及如何為您的PDF檔案提供卓越的體驗。 | Adobe Acrobat |
| 2022 年 4 月 | [發送後修改文檔](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/modify-in-flight.html?lang=en) | 影片 | 瞭解如何修改已發出以供簽名的文檔 — 如當錯誤地發出錯誤文檔時。 | Adobe Sign |
| 2022 年 4 月 | [設定簽名順序](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/setting-up-routing.html?lang=en) | 影片 | 瞭解如何為多個簽名者設定簽名順序。 按順序和/或並行方式發送文檔，或發送給特定的個人組。 | Adobe Sign |
| 2022 年 4 月 | [替換簽名者](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/replace-signer.html) | 影片 | 瞭解如何替換簽名者 — 例如在發送文檔進行簽名時使用了錯誤的電子郵件。 | Adobe Sign |
| 2022 年 4 月 | [加快銷售流程](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/acceleratesales.html) | 課程 | 瞭解Adobe文檔服務如何在整個過程中整合文檔體驗，以幫助加快銷售。 | Document Services |
| 2022 年 4 月 | [自動化法律工作流](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/automatelegalworkflows.html) | 文章 | 瞭解如何使用根據批准的語言更改的預定義模板來管理和安全地執行協定條款。 | 文檔服務 |
| 2022 年 4 月 | [員工入職現代化](https://experienceleague.adobe.com/docs/document-services/tutorials/usecases/employeeonboarding.html) | 影片 | 瞭解如何使用Adobe文檔服務API使員工入職現代化。 | 文檔服務 |

{style=&quot;table-layout:auto&quot;&quot;

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hant)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hant)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)

## ![圖示](/assets/creative-cloud-24.png) 適用於企業的 Adobe Creative Cloud {#creative-cloud}

如需了解最新教學課程，請參閱「[適用於企業的 Creative Cloud 教學課程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hant)」。

## ![圖示](/assets/experience-league.png) 客戶資料管理 - 對話 {#voices}

身為客戶資料管理技術和行銷實務主管和專家的您，[客戶資料管理對話](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=zh-Hant)是您的最終目的地。此教學課程集合是您聆聽同行的意見、獲取靈感並了解 MarTech 中發展的一站式中心。No registration required, simply click and watch.

## ![圖示](/assets/experience-league.png)數位體驗藍圖 {#blueprints}

[數位體驗藍圖](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=zh-Hant)是可重複的實施，可讓您處理策略，並快速解決既定的業務問題。每個藍圖都提供一系列成品，解釋高價值業務問題、架構、實施步驟、技術考量以及相關文件的連結。

[Top](#events)
