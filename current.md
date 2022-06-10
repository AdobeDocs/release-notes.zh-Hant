---
title: 最新版本注意事項
description: 了解  [!DNL Experience Cloud]  產品和服務的最新版本注意事項、新功能和新文件。尋找有關  [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和  [!DNL Document Cloud] 最新的說明與教學課程。
doc-type: release notes
last-update: June 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 8c5b3c3246a9f14e48d77c294143464b1c9e72c0
workflow-type: tm+mt
source-wordcount: '4708'
ht-degree: 54%

---

# Adobe Experience Cloud 發行說明 - 2022 年 6 月

![橫幅](assets/experience-cloud-banner-3.png)

身為 Experience Maker，您的成功之道始於 [ Experience League](https://experienceleague.adobe.com/?lang=zh-Hant#home)。尋找廣大的操作說明文件庫、自我引導式教學課程、操作說明影片、所有等級和角色適用的課程、線上同業社群，以及需要時的專家支援。

>[!NOTE]
>
>若要收到關於本頁更新的每月電子郵件通知，請訂閱 [Adobe 優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)。請經常回來查看，持續了解 Experience League 最新消息。

最近更新：**2022 年 6 月 10 日**

* [[!DNL Experience League] 活動](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - 中央介面元件和管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
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

若想學習、互動和了解 Adobe 產品專家的答案，Experience League 活動會是個好選擇！

更新日期：**2022 年 6 月 10 日**

| 活動 | 類型 | 說明 |
| -----------|---------- | ----|
| Adobe Campaign,Journey Optimizer [跨渠道挑戰：按比例個性化](https://adobe-campaign-cross-channel.dxfieldmarketing.adobeevents.com/) | 虛擬事件 | 請聽Director研究部451 Research的謝樂爾金斯通的講話，內容涉及跟上變革的步伐，將營銷技術作為關鍵的推動因素，以及更多的資料驅動。 我們還將重溫2022年Adobe Summit期間共用的重要會議和技巧，在2022年，您將從專家那裡聽到如何跨渠道大規模推動個性化。<br>**日期：** 6月14日 —  [詳細資訊和註冊](https://adobe-campaign-cross-channel.dxfieldmarketing.adobeevents.com/) |
| [正在查找引擎蓋 — Cloud Manager 2022](https://aem-augs.adobe.com/events/details/adobe-experience-manager-aem-learning-chapter-presents-aem-gems-looking-under-the-hood-cloud-manager-2022/) | Gems AEM — 虛擬事件 | 瞭解去年發佈的新功能、幕後開發的最新情況，並展望2022年的剩餘時間。 <br>**日期：** 6月15日 — [詳細資訊和註冊](https://aem-augs.adobe.com/events/details/adobe-experience-manager-aem-learning-chapter-presents-aem-gems-looking-under-the-hood-cloud-manager-2022/) |
| [如何構建信任並傳播影響以擴展您的數字戰略](https://mastersroundtablemay2022.experienceleague.adobeevents.com/) | 大師圓桌會議 | 與我們一起進行獨家而親密的對話，我們將討論如何有效地傳達您的數字戰略的影響。 <br>**日期：** 6月21日 —  [詳細資訊和註冊](https://mastersroundtablemay2022.experienceleague.adobeevents.com/) |
| [體驗創造者活](https://business.adobe.com/events/experience-makers-live/experience-makers-award-winners.html?sdid=JQVGW4SX&amp;mv=email&amp;mv2=sponsored) | 視頻和虛擬事件 | 2022年Adobe體驗製作商獎所慶祝的，是改變遊戲的客戶體驗和令人瞠目結舌的數字轉型。 <br>加入美洲、日本、印度、澳大利亞和紐西蘭 **6月22日**<br>&#x200B;加入歐洲、中東和非洲的盛會 **6月23日** <br> [詳細資訊和報名](https://business.adobe.com/events/experience-makers-live/experience-makers-award-winners.html?sdid=JQVGW4SX&amp;mv=email&amp;mv2=sponsored) |
| [詢問專家 — Real-Time CDP](https://www.youtube.com/watch?v=hVwtxDYvzw4) | Experience League LIVE | 我們最喜愛的Adobe專家將全面瞭解Adobe的Real-Time CDP連接產品，客戶可以通過伺服器端標籤管理系統將事件轉發到任何目標。<br>**日期：** 6月23日上午9點- [詳細資訊](https://www.youtube.com/watch?v=hVwtxDYvzw4) |
| [詢問專家：Web SDK 基礎知識](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-05-26-22.html) | Experience LeagueLIVE | 了解並使用資料彙集最佳實務。<br>[時間表和過往活動](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=zh-Hant) |
| [技能交流](https://experienceleague.adobe.com/docs/skill-exchange-events/events/overview.html?lang=en) | 錄製的研討會 | 訪問Skill Exchange查看我們的全球系列虛擬客戶學習活動，重點是深入瞭解Adobe Experience Cloud解決方案。 |
| [Experience Makers Government Forum](https://adobegovforum.govexec.com/agenda/) | 隨選影片 | 第 13 屆年度 AEMGF 已於 5 月 10 日成功落幕，不僅有線上與會者，也有與會者親自蒞臨。主場和分組會議聚焦於「_以人為本的數位體驗_」的主題。熱門會議包含「_追緝：我們如何逮到 Pablo Escobar_」、「_CX 的未來_」和「_創意和現代工作場所的黃金時代_」。 |
| [Adobe [!DNL Developers Live]: Commerce](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2022/feb2022/overview.html?lang=tw) | 隨選影片 | _Adobe Developers Live: Commerce 2022_ 匯集多元背景的開發人員和有經驗的建置者，其目的只有一個，就是創造令人驚艷的端對端體驗。此單日虛擬會議提供重要的 Commerce 和 Open Source 開發人員更新、技術研討會、社群交流機會等。 |
| [Marketo 技能交流](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=tw) | 隨選影片 | 了解 Marketo 藍圖的重要性以及如何避免規劃不周。在 2021 年 8 月 [!DNL Marketo] Marketo 技能交流 (現已上線到 Experience League 平台)，取得有關釋放方案會員自訂欄位潛力的建議、Marketo Engage 提示和技巧，以及更多。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] 會提供有關 Adobe 產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。請造訪 [status.adobe.com](https://status.adobe.com/) 來查看。

如需最新版本資訊，請參閱 Adobe 系統狀態[版本注意事項](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=zh-Hant#status)。

## ![圖示](/assets/ec_appicon_24.png) Experience Cloud - 中央介面元件和管理 {#ecloud}

Experience Cloud [中央介面元件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hant)包含首頁上可用的功能和永續性產品標題。這些功能包含使用者基本資料設定、偏好設定和搜尋。您也可以找到使用者和產品管理、客戶屬性以及 Experience Cloud Audiences 的說明。

計畫發行： **2022年7月11日**

| 功能 | 說明 |
| ------- | ------- |
| 統一首頁 — 快速訪問小部件 | **快速導航：** 現在，您可以進一步個性化您的家庭體驗，並決定您只需輕觸哪些應用程式。 使用新的釘扎功能選擇哪些應用程式出現在您的 [!UICONTROL 快速訪問]。 <br>**通過智慧釘扎保持資訊通知：** 您的新應用程式現在更容易找到。 新分配的應用程式顯示 _新建_ 徽章和自動固定 [!UICONTROL 快速訪問]。 |

{style=&quot;table-layout:auto&quot;&quot;

**更多有關 [!DNL Experience Cloud Central UI Components] 與管理的說明資源**

* Experience Cloud 中央 UI 元件[版本注意事項](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=zh-Hant)
* Experience Cloud 的[使用者和產品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) (管理)
* Places Service [版本注意事項](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hant)
* [People - 客戶屬性和對象庫](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hant)產品文件
* [整合式搜尋物件和實體](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=zh-Hant)

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 和 [!UICONTROL Mobile SDK] 的最新版本資訊和新文件：

計畫發行： **2022年6月22日**

* [Experience Platform 版本注意事項](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant)

### 新 [!DNL Experience Platform] 教學課程和其他課程 {#tutorials-platform}

專為 [!DNL Experience Platform] 發佈的新影片教學課程、文章和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 6 月 | [為管理員開始即時CDP](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2022.1.rtcdp) | 課程 | 瞭解啟動和運行所需的管理任務簡介 [!DNL Real-time Customer Data Platform]。 瞭解用戶管理以及如何與其他合作夥伴和系統建立連接。 | [!DNL Real-time CDP] |
| 2022 年 6 月 | [監視段激活的成功](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-the-success-of-segment-activation.html?lang=en) | 影片 | 瞭解監控資料段流向目標的兩種主要方法。 在向激活合作夥伴發送段配置檔案時，必須查看有關此資料傳輸成功的資訊，特別是這樣您才能解決問題。 | [!DNL Real-time CDP] |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Adobe Mobile] SDK

如需了解 Adobe Experience Platform Mobile SDK，請參閱[版本注意事項和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

下一版： **2022年6月15日**

最近更新：**2022 年 6 月 8 日**

* Adobe Analytics [版本注意事項](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hant)
* Adobe Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)

### AppMeasurement {#appm}

發行版本：**2.22.4**

* [JavaScript 適用的 AppMeasurement 版本注意事項](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)

### 新 [!DNL Analytics] 教學課程和其他課程 {#tutorials-analytics}

專為 Adobe Analytics 發佈的新影片教學課程、文章和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 6 月 | [出口和民主化Adobe Analytics資料](https://experienceleague.adobe.com/docs/courses/using/analytics-a-1-2022-1-democratizing.html?lang=en) | 課程 | 瞭解Adobe Analytics支援您實現數字資料民主化的功能。 資料民主化是消除瓶頸並使組織中的關鍵人員能夠輕鬆處理資料以便他們能夠根據資料做出決策的過程。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

上次更新：**2022 年 5 月 19 日**

* Customer Journey Analytics [版本注意事項](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hant)
* Customer Journey Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hant)

### 新的 Customer Journey Analytics 教學課程和其他課程 {#tutorials-cja}

為CJA發佈的新視頻、教程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 6 月 | [在資料檢視中繫結維度](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/binding-dimensions-in-data-views.html?lang=en) | 影片 | 關於綁定尺寸的精益。 此功能使您能夠獲取一個維並將其連接到另一個維，以便更精細地分配持久性。 |
| 2022 年 6 月 | [Customer Journey Analytics 登陸頁面](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/cja-basics/customer-journey-analytics-landing-page.html) | 影片 | Customer Journey Analytics 登陸頁面包含您的專案和行動計分卡的預設檢視，以及可幫助您更有效地開始體驗的學習區段。 |
| 2022 年 6 月 | [擷取、對應及轉換 Adobe Analytics 資料](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-prep/ingest-map-and-transform-adobe-analytics-data.html) | 影片 | 瞭解如何使用資料準備功能 [!DNL Analytics] 資料，包括資料處理功能。 例如，可以將分析變數映射到新的自定義欄位，並執行轉換和計算。 |
| 2022 年 6 月 | [配置子字串元件設定](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configure-substring-component-settings.html) | 影片 | 瞭解如何使用字串操作方法在Customer Journey Analytics報告中獲取所需的維值部分。 應用後，資料轉換將立即進行追溯。 |
| 2022 年 6 月 | [建立行動計分卡](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/create-scorecard.html) | 影片 | 瞭解如何為執行用戶配置和顯示儀表板。 |
| 2022 年 6 月 | [連線的建立和編輯體驗](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/cja-connections-creation-and-edit-experience.html) | 影片 | 瞭解如何啟用滾動資料保留窗口、啟用並請求基於事件時間戳的回填資料，以及按資料集導入現有資料。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

上次更新：**2022 年 3 月 23 日**

* [!DNL Streaming Media Analytics] [發行說明](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=zh-Hant)
* [!DNL Streaming Media Analytics] [產品文件與教學課程](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=zh-Hant)

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

### Experience Manager 產品更新

* **Experience Manager as a Cloud Service**

   觀看 [2022年5月發佈概述視頻](https://video.tv.adobe.com/v/343321/?quality=12) 2022.5.0（2022年5月）版中添加的功能摘要。 <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [2022年4月發佈概述視頻](https://video.tv.adobe.com/v/342612?quality=12)
   * [2022 年 3 月版本總覽影片](https://video.tv.adobe.com/v/341465)。
   * [2022 年 1 月版本總覽影片](https://video.tv.adobe.com/v/340120)。
   * [2021 年 12 月版本總覽影片](https://video.tv.adobe.com/v/339278)。
   * [2021 年 10 月版本總覽影片](https://video.tv.adobe.com/v/338253)。
   * [2021 年 9 月版本總覽影片](https://video.tv.adobe.com/v/337381)。

* **Experience Manager Sites as a Cloud Service**

   _搶鮮版通道的新功能_

   * 各種GraphQL功能。
   * A [新控制台](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/headless/content-fragments/content-fragment-console.html?lang=en) 針對無頭使用內容片段而優化。

* **Experience Manager Assets as a Cloud Service**

   _新功能_

   * [Dynamic Media智慧成像現在支援AVIF檔案格式](https://medium.com/adobetech/one-solution-fits-all-smart-imaging-with-aem-dynamic-media-be690b62df9f)  — 進一步改進Google核心網關重要性（最大內容塗料）,AVIF比WebP提供20%的額外尺寸縮減。 總的來說，AVIF比JPEG（在某些影像中甚至高達76%）提供了41%的平均尺寸縮減率。
   * Experience Manager Assets·Brand Portal現在每12小時運行一次自動作業，以刪除發佈給Experience Manager的所有Brand Portal資產。 因此，您不需要手動刪除「貢獻」資料夾中的資產，以使資料夾大小低於閾值限制。 請參閱 [Experience Manager Assets·Brand Portal有什麼新聞嗎](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/whats-new.html?lang=zh-Hant)。

      _搶鮮版通道的新功能_

   * Experience Manager Assets目前使用Adobe SenseiAI功能 [區分影像中的顏色，並在攝取時自動將差異作為標籤應用](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=en)。 這些標籤基於影像顏色合成，支援增強的搜索體驗。 您可以配置標籤到影像的顏色數量（範圍在1到40之間），以便以後可以根據這些顏色搜索影像。

* **Experience Manager Forms as a Cloud Service**

   _預發行渠道中的新功能_

   * **通信 — Formsas a Cloud ServiceSDK中的文檔操作API支援** -

   * **將自適應Forms與Microsoft® Power Automate整合**  — 您現在可以配置自適應表單，在提交時運行Microsoft® Power自動化雲流。 配置的自適應表單將捕獲的資料、附件和記錄文檔發送到Power Automate Cloud Flow進行處理。 它幫助您構建自定義資料捕獲體驗，同時利用Microsoft® Power Automate的強大功能，圍繞捕獲的資料構建業務邏輯並自動化客戶工作流。
   * **用於建立自適應表單的嚮導**  — 您可以使用業務用戶友好嚮導快速編寫AdaptiveForms。 該嚮導提供快速頁籤導航，以便輕鬆選擇預先配置的模板、樣式、欄位和提交選項以建立自適應表單。

* **Experience Manager as a Cloud Service 基礎**

   _新功能_

   * 的 **[!UICONTROL 添加樹]** 的子菜單。 **[!UICONTROL 分發]** 頁籤，此前已宣佈為棄用，將於2022年6月20日或之後不久刪除。 應使用樹層次結構複製內容的包 [管理發布](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#manage-publication) 或 [發佈內容樹工作流](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#publish-content-tree-workflow)。
   * 不建議使用複製代理管理螢幕或複製API來分發大於10 MB（具有屬性的節點，不包括二進位檔案）的內容包，並將在2022年9月12日或之後立即實施。 相反， [管理發布](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#manage-publication) 或 [發佈內容樹工作流](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#publish-content-tree-workflow) 必須用於複製這些大型內容包。 在2022年7月，複製代理管理螢幕的 **[!UICONTROL 分發]** 頁籤。 如果您嘗試複製這些大型內容包，並且當使用複製API複製這些大型內容包時，還會顯示在Experience Manager錯誤日誌中。 9月，警告將替換為錯誤。 Adobe建議您相應調整流程。

   _搶鮮版通道的新功能_

   * Experience Manageras a Cloud Service現在與Unified Shell整合，以改進用戶體驗並將其與所有其他Experience Cloud應用程式統一。 請參閱 [Experience Manageras a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/overview/aem-cloud-service-on-unified-shell.html?lang=en) 的子菜單。


* **Experience Manageras a Cloud Service基礎安全**

   * **TLS 1.0和TLS 1.1的棄用**  — 從2022年6月30日起，Experience Manageras a Cloud Service將要求與用戶系統進行更安全的網路通信和資料交換。 Experience Manager將只使用TLS（傳輸層安全性）1.2協定。 不建議使用TLS 1.0和1.1。

      如果繼續使用TLS 1.0或TLS 1.1，則可能無法訪問Experience Manageras a Cloud Service。

### 社群

* 播放 [Experience Manageras a Cloud Service2022.5.0版更新視頻](https://adobe.ly/3NDPR8Y) 就是那些被釋放的東西。 (10 分鐘)
* 創業板網路研討會 —  _看著引擎蓋：Cloud Manager 2022_
   * 2022 年 6 月 15 日，星期三
   * 太平洋時間08:00;中歐時間17點；印度標準時間20時30分
   * [按一下這裡報名](https://adobe.ly/3t4jfgp).
   * [討論線程](https://adobe.ly/3O0rdzd)。

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022 年 6 月 | [[!DNL Forms] 門戶元件](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/forms-portal-components.html?lang=en) | 影片 | 瞭解如何啟用 [!DNL AEM Forms] [!UICONTROL 門戶] 在FormsCloud Service。 | AEM Forms CS |
| 2022 年 6 月 | [集AEM成和CIF框架，構建豐富而逼真的電子商務體驗](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/gems2022/aem-and-cif-framework-integration.html?lang=en) | 影片 | 瞭解如何使用Adobe的CIF框架來構建一致且內容豐富且身臨其境的商務體驗。 | AEM &amp; CIF 框架 |
| 2022 年 6 月 | [SAML 2.0身份驗證](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/authentication/saml-2-0.html) | 影片 | 瞭解如何設定最終用戶（而非作者）並AEM驗證其是否與您選擇的SAML 2.0相容的IDP。 | AEM CS |
| 2022 年 6 月 | [上下文感知雲配置](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/context-aware-fdm.html?lang=en) | 影片 | 瞭解如何在AEM FormsCloud Service上定義上下文感知的雲配置。 | AEM Forms |

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

## ![圖示](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] (以前 [!DNL XML Documentation for Experience Manager])是部署到的應AEM用程式 這是一個功能強大、企業級元件內容管理解決方案 (CCMS)；此解決方案啟用 Adobe Experience Manager 的原生 DITA 支援、使 AEM 能夠處理以 DITA 為主的內容建立和傳遞。

瞭解有關 [[!DNL Experience Manager Guides]](https://www.adobe.com/tw/products/xml-documentation-for-experience-manager/features.html)。

### 其他資源

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=zh-Hant) -Experience League教程
* [[!DNL Experience Manager Guides] 學習和支援](https://helpx.adobe.com/tw/support/xml-documentation-for-experience-manager.html)  — 產品文檔

## ![圖示](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

請參閱以下 Adobe Commerce 版本注意事項連結：

* [Adobe Commerce 和 Magento Open Source 2.4.x 版本注意事項](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite 版本注意事項](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新的Adobe Commerce教程和文檔 {#tutorials-commerce}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 6 月 | [MBI入門](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/getting-started.html?lang=en) | 影片 | 通過深入瞭解預配置的儀表板和可用的自定義選項，直接從Commerce Product團隊瞭解MBI的核心功能。 |
| 2022 年 6 月 | [在MBI中管理資料集](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/manage-data-sets.html?lang=en) | 影片 | 直接從Adobe Commerce產品團隊瞭解MBIData Warehouse管理器的一些強大功能。 超越基本報告構建，瞭解如何利用您的資料做更多工作。 |
| 2022 年 6 月 | [優化MBIData Warehouse](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/optimize-data-warehouse.html?lang=en) | 影片 | 瞭解如何管理表和列同步設定、深入到表的架構並建立要在報告中使用的計算列。 |
| 2022 年 6 月 | [帶MBI的假日準備](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/holiday-readiness.html?lang=en) | 影片 | 瞭解常見的季節性分析使用案例和方法，以使用關鍵MBI功能解決這些問題。 |
| 2022 年 6 月 | [MBI — 請咨詢專家](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/ask-expert.html?lang=en) | 影片 | 在本兩部分網路研討會中，瞭解客戶對Business Intelligence的看法。 通過Business Intelligence瞭解業務轉換，使用通用表表達式進行SQL優化，等等。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新時間： **2022年6月7日**

* 如需搶鮮版資訊，請參閱 [Adobe Target 搶鮮版](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)。
* 如需目前版本資訊，請參閱 [Adobe Target 版本注意事項](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hant)。

### 最新 Adobe Target 課程與教學課程 {#tutorials-target}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 6 月 | [連結文本](https://experienceleague.adobe.com/?recommended=Target-D-1-2021.1) | 課程 | 瞭解如何在您的網站上實施Adobe Target。 從管理主題開始，包括要求和用戶權限，然後介紹實施方法、注意事項和最佳做法。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新 Campaign 產品版本

**最新版本：** [Campaign Standard 版本 22.2](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/e-release-notes.html) (2022 年 6 月)

在 [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hant)、[Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) 和 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hant) 發行說明中進一步了解最新功能、改進與修正。

### 新 [!DNL Campaign] 教學課程和其他課程 {#tutorials-campaign}

針對 Adobe Campaign 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 6 月 | [設定傳遞範本](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/using-delivery-templates/configure-a-delivery-template.html) | 影片 | 瞭解如何設定隨選傳遞的範本。 | Campaign v8 |
| 2022 年 6 月 | [建立定期和連續的電子郵件遞送](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/recurring-deliveries.html) | 影片 | 瞭解如何配置循環傳遞和計畫程式活動。 | 市場活動v8 |
| 2022 年 6 月 | [設定擴充活動](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/enrichment-activity.html) | 影片 | 瞭解如何根據傳遞歷史記錄資訊設定擴充活動。 | 市場活動v8 |
| 2022 年 6 月 | [簡訊簡介](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/introduction-to-sms.html) | 影片 | 瞭解SMS是什麼、SMS服務提供商的角色、Adobe Campaign如何連接到服務提供商。 瞭解通過服務提供商傳遞的資訊以及哪些技術說明可用。 | 市場活動v8,Campaign Standard,Campaign Classicv7 |
| 2022 年 6 月 | [為標準SMPP提供程式設定SMS帳戶](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/set-up-account-for-standard-smpp-provider.html?lang=en) | 影片 | 瞭解如何與Adobe Campaign建立SMPP帳戶、如何分析SMS交付結果以及根據您的SMPP提供商的規格自定義SR處理。 | 市場活動v8,Campaign Classicv7 |
| 2022 年 6 月 | [將SMS連接器適用於您的SMPP提供商](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/adapt-sms-connector-to-smpp-provider.html) | 影片 | 瞭解如何將SMS連接器適應您的SMPP提供商。 微調SMS設定以處理連接限制、設定最大吞吐量、發送窗口和使用TLS的加密。 | 市場活動v8、Campaign Classicv7、Campaign Standard |

{style=&quot;table-layout:auto&quot;&quot;

### Campaign 說明資源

* Adobe Campaign v8：[文件](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hant)
* Adobe Campaign Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hant) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [操作說明影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hant)- [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hant) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hant) 操作說明影片

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

有了 Journey Optimizer，您就可以從單一應用程式為幾百萬名客戶管理排程的全通路行銷活動及一對一時刻，還有智慧型決策和見解讓整個旅程最佳化。

### 最新 Journey Optimizer 產品版本

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hant)中最新功能、改進功能和修正。

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

### Marketo Engage 核心更新

如需最新發行排程資訊和版本注意事項，請參閱[!DNL Marketo Engage] [發行排程](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hant)。

## ![圖示](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] 是統一的工作管理應用程式，用於共用構想、建立內容、管理複雜的流程並執行其最佳工作。

請參閱 [[!DNL Workfront]  發行版本](https://one.workfront.com/s/product-releases)頁面，以取得所有產品的最新資訊匯總。

## ![圖示](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 版本注意事項。

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
* [ [!DNL Advertising Cloud DSP] 中的新功能](#adcloud-dsp)
* [ [!DNL Advertising Cloud Search] 中的新功能](#adcloud-search)
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

### [!DNL Advertising Cloud DSP] 中的新功能 {#adcloud-dsp}

上次更新時間： **2022年6月8日** 為5月31日的發行

| 功能 | 說明 |
| ------- | ----------- |
| 自訂報告 | （Beta功能）Advertising Cloud DSP公司現在可以接收由在客戶資料平台(CDP)內構建的經過驗證的信號組成的第一方資料段。 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search}

上次更新日期：**** 2022 年 6 月 8 日 (6 月 11 日版本)

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 洞察力] | 「印象共用丟失」分析現在再次作為測試版功能提供。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

專為 Adobe Document Cloud 發佈的新教學課程和課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 6 月 | [使用委託者角色](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=en) | 影片 | 瞭解如何使用委託者角色將文檔發送給中間人，中間人隨後可以將文檔路由以進行簽名。 |
| 2022 年 6 月 | [配置事件和警報的通知](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/set-up-shared-events-and-alert.html?lang=en) | 影片 | 瞭解可在Acrobat Sign配置的共用事件和警報設定。 警報是在特定時間範圍內未發生的操作，事件是已發生的操作。 |
| 2022 年 6 月 | [高級帳戶共用](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/advanced-account-sharing.html?lang=en) | 影片 | 瞭解如何設定高級帳戶共用 — 允許管理員和用戶委託其發送、修改和查看權限。 |

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
