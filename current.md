---
title: 最新版本注意事項
description: 了解  [!DNL Experience Cloud]  產品和服務的最新版本注意事項、新功能和新文件。尋找有關  [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和  [!DNL Document Cloud] 最新的說明與教學課程。
doc-type: release notes
last-update: July 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: 91b0d04c0a8b481e29a6c678ba9afc0484795433
workflow-type: tm+mt
source-wordcount: '5678'
ht-degree: 95%

---

# Adobe Experience Cloud 版本注意事項 - 2022 年 7 月

![橫幅](assets/experience-cloud-banner-3.png)

身為 Experience Maker，您的成功之道始於 [ Experience League](https://experienceleague.adobe.com/?lang=zh-Hant#home)。尋找廣大的操作說明文件庫、自我引導式教學課程、操作說明影片、所有等級和角色適用的課程、線上同業社群，以及需要時的專家支援。

>[!NOTE]
>
>若要收到關於本頁更新的每月電子郵件通知，請訂閱 [Adobe 優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)。請經常回來查看，持續了解 Experience League 最新消息。

最近更新日期：**2022 年 7 月 27 日**

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

若要向 Adobe 產品專家學習、與之互動或獲得解答，Experience League 活動是您絕佳的選擇！請查看 Experience League 上的[活動](https://experienceleague.adobe.com/events/?lang=en)，以掌握 2022 年 7 月活動的最新消息。

更新日期：**2022 年 7 月 17 日**

| 活動 | 類型 | 說明 |
| -----------|---------- | ----|
| [詢問專家：資料串流和資料準備](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=zh-Hant) | Experience League LIVE | 在關於 Adobe Experience Cloud 資料收集的三場會議的最後一場中，我們的專家將深入探討 Adobe 的進階資料收集功能，包括資料收集的資料準備等功能。在這場會議結束時，與會者將對從數位體驗中收集資料的最新和最強大功能充滿信心&#x200B;<br>**日期：** 7 月 21 日上午 9 點 (太平洋標準時間) - [詳細資料](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) |

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
>請檢視下列有關 Experience Cloud 佈建的通知。

Adobe 正在更新其佈建，以便讓所有 Experience Cloud 客戶都能存取基礎功能，從而提升某些 Experience Cloud 產品之間的互通性。使用者會將 Adobe Experience Platform 作為新權益新增到其 Experience Cloud 組織，而 [!UICONTROL Data Collection] 作為附帶服務。

Adobe Experience Platform [!UICONTROL Data Collection] 包括用於簡化通用標記管理的[標記](https://experienceleague.adobe.com/docs/tags.html?lang=zh-Hant)，並提供可信、強固且完整的串流資料基礎架構。標記簡化了客戶體驗資料收集和體驗交付流程。

**Admin Console 中的變更**

管理員可以查看對 Admin Console 的變更或增加內容，如下所示：

* Admin Console 中的 Adobe Experience Platform 產品卡將包含：

   * 地點
   * 保證
   * 身分識別命名空間
   * 沙箱
   * 體驗資料模型
   * 結構描述
   * 資料串流
   * 訪客 ID

   對於目前未使用 Experience Platform 的組織，您現在將在 Admin Console 中看到 _Adobe Experience Platform_ 產品，包括上方所列的功能。

   對於目前使用 Experience Platform 的組織，_地點_&#x200B;現在將合併到 Experience Platform 卡中。

* Adobe Experience Platform Data Collection (以前稱為 Launch) 和 Privacy 將繼續顯示為與其他 Experience Platform 功能分開的產品卡。

如需有關新功能的更多詳細資訊，請造訪它們在 Experience League 上的相應頁面：

* [資料收集](https://experienceleague.adobe.com/docs/analytics/analyze/reports-analytics/reporting-interface/overview-data-collection.html?lang=zh-Hant)
* [地點](https://experienceleague.adobe.com/docs/places/using/home.html?lang=zh-Hant)
* [保證](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/app-implementation/assurance.html?lang=zh-Hant)
* [身分識別命名空間](https://experienceleague.adobe.com/docs/experience-platform/identity/home.html?lang=zh-Hant)
* [沙箱](https://experienceleague.adobe.com/docs/experience-platform/sandbox/home.html?lang=zh-Hant)
* [體驗資料模型](https://experienceleague.adobe.com/docs/experience-platform/xdm/home.html?lang=zh-Hant)
* [結構描述](https://experienceleague.adobe.com/docs/experience-platform/xdm/schema/composition.html?lang=zh-Hant)
* [資料串流](https://experienceleague.adobe.com/docs/experience-platform/edge/datastreams/overview.html?lang=zh-Hant)
* [訪客 ID](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services.html?lang=zh-Hant#section_3C9F6DF37C654D939625BB4D485E4354)
* [隱私](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html?lang=zh-Hant)

### 功能更新

功能發行日期：**2022 年 7 月 11 日**

| 功能 | 說明 |
| ------- | ------- |
| 整合首頁 - 快速存取 Widget | **更快速瀏覽：**&#x200B;現在，您可以進一步個人化首頁體驗，並決定哪些應用程式是觸手可及的。使用新的釘選功能來選取哪些應用程式出現在[!UICONTROL 快速存取]工具中。<br>**透過智慧釘選保持資訊靈通：**&#x200B;您的新應用程式現在更容易找到。新指派的應用程式顯示&#x200B;_新_&#x200B;徽章，並自動釘選到[!UICONTROL 快速存取]。 |

{style=&quot;table-layout:auto&quot;&quot;

**更多有關 [!DNL Experience Cloud Central UI Components] 與管理的說明資源**

* Experience Cloud 中央 UI 元件[版本注意事項](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=zh-Hant)
* Experience Cloud 的[使用者和產品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) (管理)
* Places Service [版本注意事項](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hant)
* [People - 客戶屬性和對象庫](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=zh-Hant)產品文件
* [整合式搜尋物件和實體](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=zh-Hant)

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

[!DNL Experience Platform] 和 [!UICONTROL Mobile SDK] 的最新版本資訊和新文件：

預計發行日期：**2022 年 7 月 27 日**

* [Experience Platform 版本注意事項](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant)

### 新 [!DNL Experience Platform] 教學課程和其他課程 {#tutorials-platform}

專為 [!DNL Experience Platform] 發佈的新影片教學課程、文章和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [監視事件轉送](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/monitor.html?lang=zh-Hant) | 影片 | 了解如何在資料收集介面中監視事件轉送。 | 資料收集 |
| 2022 年 7 月 | [監視資料內嵌](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-dashboard.html?lang=zh-Hant) | 影片 | 了解如何使用監視儀表板來監視和追蹤內嵌到 Adobe Experience Platform 中的資料。 | 資料收集 |
| 2022 年 7 月 | [將範例資料匯入 Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/import-sample-data.html?lang=zh-Hant) | 文章 | 了解如何設定包含範例資料的 Experience Platform 沙箱環境。您可以使用 Postman 集合來建立欄位群組、結構描述、資料集，然後將範例資料匯入 Experience Platform。 | Experience Platform |
| 2022 年 7 月 | [區段比對接收資料](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-receiving-data.html?lang=zh-Hant) | 影片 | 透過區段比對，您的策略合作夥伴就可以將資料分享給您。在此影片中，了解如何核准及接收資料，以及在何處可查看資料並將其新增到您自己的區段中。 | Experience Platform - 區段 |
| 2022 年 7 月 | [詢問專家：Real-Time CDP Connections](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-06-23-22.html?lang=zh-Hant) | Experience League LIVE 影片 | 在關於資料收集的三場直播會議的第二場中，我們喜愛的專家將全面審視 Adobe RTCDP [!UICONTROL Connections]，客戶可以在其中使用伺服器端標記管理系統將事件轉送到非 Adobe 目的地。 | 資料收集 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Adobe Mobile] SDK

如需了解 Adobe Experience Platform Mobile SDK，請參閱[版本注意事項和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

下次發行日期：**2022 年 7 月 20 日**

上次更新日期：**2022 年 7 月 13 日**

* Adobe Analytics [版本注意事項](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hant)
* Adobe Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)

### AppMeasurement {#appm}

發行版本：**2.22.4**

* [JavaScript 適用的 AppMeasurement 版本注意事項](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)

### 新 [!DNL Analytics] 教學課程和其他課程 {#tutorials-analytics}

專為 Adobe Analytics 發佈的新影片教學課程、文章和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [2022 流量改善](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-improvements.html?lang=zh-Hant) | 影片 | 了解[!UICONTROL 流量]視覺效果的一些重要改善。改善包括可設定您感興趣的開始路徑或結束路徑，可篩選欄以包含或排除特定項目，以及可預先設定的進階設定。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

最近更新日期：**2022 年 7 月 12 日**

* Customer Journey Analytics [版本注意事項](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hant)
* Customer Journey Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hant)

### 新的 Customer Journey Analytics 教學課程和其他課程 {#tutorials-cja}

針對 CJA 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [設定下一個和上一個項目面板](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/panels/configure-next-previous-item-panel.html?lang=zh-Hant) | 影片 | 了解如何在 [!DNL Customer Journey Analytics] 設定下一個和上一個項目面板。 此面板會產生表格和視覺化效果以識別特定維度值的下一個或上一個項目。 |
| 2022 年 7 月 | [建立附註](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/annotations/create-an-annotation.html?lang=zh-Hant) | 影片 | 了解如何在事件 (行銷活動啟動、資料問題和假期等) 發生時，在您的 [!DNL Customer Journey Analytics] 專案中建立附註。此功能會通知您的使用者這些日期或日期範圍上的量度變動。 |
| 2022 年 7 月 | [建立快速篩選](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter.html?lang=zh-Hant) | 影片 | 直接在您的 [!DNL Customer Journey Analytics] 專案中建立快速篩選，略過完整篩選產生器的複雜性。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

上次更新：**2022 年 3 月 23 日**

* [!DNL Streaming Media Analytics] [版本注意事項](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=zh-Hant)
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

### 產品更新影片

* [2022 年 6 月版總覽影片](https://video.tv.adobe.com/v/344308/?quality=12)，了解 2022.6 版的摘要。

較舊產品更新影片：

* [2022 年 5 月版總覽影片](https://video.tv.adobe.com/v/343321/?quality=12)，了解 2022.5.0 (2022 年 5 月) 版中新增功能的摘要。
* [2022 年 4 月版總覽影片](https://video.tv.adobe.com/v/342612?quality=12)
* [2022 年 3 月版總覽影片](https://video.tv.adobe.com/v/341465)
* [2022 年 1 月版總覽影片](https://video.tv.adobe.com/v/340120)
* [2021 年 12 月版總覽影片](https://video.tv.adobe.com/v/339278)
* [2021 年 10 月版總覽影片](https://video.tv.adobe.com/v/338253)
* [2021 年 9 月版總覽影片](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Sites] as a [!DNL Cloud Service]

[!DNL Sites] 中的新功能：

* 現在，內容管理員和內容作者可以使用[新的使用者介面](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=zh-Hant)來有效地管理 (執行發佈、取消發佈、複製和移動等動作)、搜尋/篩選，以及為無頭式使用案例建立內容片段。

* 新的[目錄元件](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/tableofcontents.html?lang=zh-Hant)不僅適用於[!UICONTROL 核心元件]，也適用於所有元件，可自動在內容頁面上呈現目錄。而且，由於它是在伺服器端呈現並由 Dispatcher 完全快取，因此載入也相當有效率。

### Experience Manager [!DNL Assets] 作為 [!DNL Cloud Service]

[!DNL Assets] 中的新功能：

* Experience Manager [!DNL Assets] 現在會使用 Adobe Sensei AI 功能來[區分影像中的顏色，並在內嵌時自動將這些差異套用為標記](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=zh-Hant)。這些標記會根據影像顏色組合來增強搜尋體驗。您可以設定標記到影像的顏色數量 (範圍在 1 到 40 之間)，以便日後可以根據這些顏色搜尋影像。

### Experience Manager Forms as a Cloud Service

[!DNL Forms] 中的新功能：

* [整合[!UICONTROL 最適化表單]與 Microsoft® Power Automate](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/forms-microsoft-power-automate-integration.html?lang=zh-Hant)：您現在可以設定自適應表單，在提交時執行 Microsoft® Power Automate Cloud Flow。設定的最適化表單會將擷取的資料、附件和記錄文件傳送到 Power Automate Cloud Flow 進行處理。它有助於建立自訂資料擷取體驗，同時利用 Microsoft® Power Automate 的強大功能，圍繞擷取的資料建立商業邏輯，並自動化客戶工作流程。

**用於建立最適化表單的精靈**：您可以使用業務使用者友善的精靈來快速編寫[!UICONTROL 最適化表單]。精靈提供快速的標籤導覽，以便輕鬆選取用於建立最適化表單的預先設定範本、樣式、欄位和提交選項。

### Experience Manager as a Cloud Service 基礎

新增功能：

如 5 月 (2022.5.0) 版本注意事項中所述，複寫代理程式管理畫面的「分配」標籤下的「新增樹狀結構」選項已遭到移除。應改用「管理發佈」或「發佈內容樹狀結構」工作流程，來複寫具有樹狀階層內容的套件。

### [!DNL Cloud Manager]

新增功能：

* [!DNL Cloud Manager] 使用者現在隨時可以從登陸頁面上的「[!UICONTROL 歡迎]」卡中，存取實用的影片教學課程。

* 環境詳細資料頁面的「[復原內容](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=zh-Hant)」標籤上的彈出視窗，現在會顯示一個方便的 git 命令清單，讓使用者可以在本機檢視變更。

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [充分利用企業工作流程管理](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/workflow.html?lang=zh-Hant) | 影片 | 了解使用工作流程進行資產管理的好處，以及如何快速建立它們。 | AEM - 體驗工作流程管理 |
| 2022 年 7 月 | [使用 Adobe Experience Manager 提供無頭式體驗](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=zh-Hant) | 影片 | 了解使用最新 Experience Manager [!UICONTROL 內容片段]增強功能的無頭式體驗管理，以及用於無頭式內容提供的新 GraphQL API。 | Experience Manager [!DNL Sites] |
| 2022 年 7 月 | [在 Adobe Experience Manager Assets 中讓中繼資料可供您的企業使用](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/metadata.html?lang=zh-Hant) | 影片 | 了解如何透過減少標記資產的工作量以及使您的資產更易於搜尋，以充分利用 AEM Assets 的中繼資料。 | Experience Manager [!DNL Assets] |
| 2022 年 7 月 | [iOS 應用程式](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/ios-swiftui-app.html?lang=zh-Hant) | 影片 | 範例應用程式是探索 Adobe Experience Manager 無頭式功能的絕佳方法。此 iOS 應用程式示範了如何使用 AEM 的 [!UICONTROL GraphQL API] 透過持久查詢來查詢內容。 | Experience Manager [!DNL Assets]、[!DNL Sites] |
| 2022 年 7 月 | [Android™ 應用程式](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/android-app.html?lang=zh-Hant) | 影片 | 此 Android™ 應用程式示範了如何使用 AEM 的 [!UICONTROL GraphQL API] 來查詢內容。 | Experience Manager [!DNL Assets]、[!DNL Sites] |
| 2022 年 7 月 | [設定 Adobe Experience Manager as a Cloud Service 的 OSGi](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/deploying/configuring-osgi.html?lang=zh-Hant) | 影片 | 了解如何設定 AEM CS 的 OSGI。例如，了解 OSGi 套件組合的管理，以及透過 AEM 程式碼專案一部分的設定檔案來管理 OSGi 元件的組態設定。 | AEM as a Cloud Service |
| 2022 年 7 月 | [覆寫表單資料模型屬性](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/override-fdm-values.html?lang=zh-Hant) | 影片 | 了解如何覆寫表單資料模型屬性，以便更輕鬆地針對不同端點測試一個表單資料模型。 | AEM [!DNL Forms] |

{style=&quot;table-layout:auto&quot;&quot;

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

### 新的 Adobe Commerce 教學課程和文件 {#tutorials-commerce}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [Adobe Commerce 快速入門手冊](https://experienceleague.adobe.com/docs/commerce-admin/start/guide-overview.html?lang=zh-Hant) | 產品文件 | 專為不熟悉 Adobe Commerce 和 Magento Open Source 的商家和系統管理員提供的手冊。從他們的角度了解平台的概況，以及有關啟用機能商店的基本功能的一些詳細資訊。 |
| 2022 年 7 月 | [頁面產生器使用手冊](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/guide-overview.html?lang=zh-Hant) | 產品文件 | 了解頁面產生器功能，包括用於建立基本內容元件的三部分逐步解說。本手冊適用於管理員。它假定您對核心 Adobe Commerce 設定和功能有基本的了解。 |
| 2022 年 7 月 | [Adobe Commerce 的 B2B 指南](https://experienceleague.adobe.com/docs/commerce-admin/b2b/guide-overview.html?lang=zh-Hant) | 管理指南 | 取得有關安裝和啟用此模組的詳細資訊，包括其功能的設定和管理。 |
| 2022 年 7 月 | [Adobe Commerce 的 B2B - 教學課程](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/b2b/company-accounts.html?lang=zh-Hant) | 影片 (多個) | 了解 Adobe Commerce 中的「[!UICONTROL 公司]」頁面。您可以管理您的公司帳戶，任何待核准的請求都會顯示在清單的頂端。 |
| 2022 年 7 月 | [使用品質修補工具](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/quality-patch-tool.html?lang=zh-Hant) | 影片 | 了解[!UICONTROL 品質修補工具]，這是一個命令列工具，可為 Adobe Commerce 和 Magento Open Source 提供高品質的修補程式。 |
| 2022 年 7 月 | [全網站分析工具儀表板](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/site-wide-analysis-tool.html?lang=zh-Hant) | 影片 | 了解全網站分析工具。此功能是主動式自助服務工具和中央存放庫，其中包含詳細的系統分析和建議，以確保您的 Adobe Commerce 安裝的安全性和可操作性。 |
| 2022 年 7 月 | [使用支付服務](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/payment-services.html?lang=zh-Hant) | 影片 | 了解如何使用[!UICONTROL 支付服務]來減少營運開銷並增加收入。 |
| 2022 年 7 月 | [管理訂單狀態](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/orders/order-status.html?lang=zh-Hant) | 影片 | 了解如何檢查訂單狀態及其詳細資料，以及如何根據需要變更訂單的狀態。 |
| 2022 年 7 月 | [行銷工具](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/marketing/catalog-price-rules.html?lang=zh-Hant) | 影片 (多個) | 了解有關建立目錄價格規則、購物車價格規則、管理相關產品規則、即時搜尋等的資訊。 |
| 2022 年 7 月 | [提供商業價值的內容個人化創新](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/content-perosonalization.html?lang=zh-Hant) | 影片 | 檢視 Skill Builder 簡報，並了解 Adobe 內容解決方案的最新創新，協助您實現內容製作的大眾化、使全管道交付變得輕而易舉，並擴大個人化規模。 |
| 2022 年 7 月 | [目錄管理](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/catalog/seo-url-rewrites.html?lang=zh-Hant) | 影片 | 了解 Adobe Commerce 中的目錄管理。建立類別、管理類別中的產品、管理詳細目錄等。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新日期：**2022 年 6 月 30 日**

* 如需搶鮮版資訊，請參閱 [Adobe Target 搶鮮版](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)。
* 如需目前版本資訊，請參閱 [Adobe Target 版本注意事項](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hant)。

### 新的 Adobe Target 課程與教學課程 {#tutorials-target}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [建立對象](https://experienceleague.adobe.com/docs/target-learn/tutorials/audiences/create-audiences.html?lang=zh-Hant) | 影片 | 了解在 [!DNL Target] 中建立和儲存自訂對象，以便在您的活動中使用。 |
| 2022 年 7 月 | [使用 Adobe Target 實現個人化和自動化](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/data-and-insights/2022/personalize.html?lang=zh-Hant) | 影片 | 了解使用 [!UICONTROL Auto Target] 和 [!UICONTROL Auto Personalization] 自動化和最佳化 Adobe Target 功能的核心概念。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新 Campaign 產品版本

* [Campaign v7.3 版](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hant)
* [控制面板 6 月版](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=zh-Hant)
* Experience League 上的[教學課程與其他課程](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=zh-Hant#tutorials-campaign)

### 新 [!DNL Campaign] 教學課程和其他課程 {#tutorials-campaign}

針對 Adobe Campaign 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [混合託管模型的控制面板](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html?lang=zh-Hant) | 影片 | 了解如何為 Adobe Campaign 混合託管模型啟用控制面板、存取控制面板，並解鎖主要功能。 | 控制面板 |
| 2022 年 7 月 | [監視輸送量和延遲](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html?lang=zh-Hant) | 影片 | 了解如何監視您的行銷活動執行個體的傳遞輸送量和異動訊息延遲。 | 控制面板 |
| 2022 年 7 月 | [監視工作流程以最佳化資源使用](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html?lang=zh-Hant) | 影片 | 了解如何監視工作流程的臨時儲存使用情況，以及設定工作流程設定的位置，以避免執行個體上出現資料庫或工作流程問題。 | 控制面板 |
| 2022 年 7 月 | [在 Adobe Campaign Classic 中開發和自訂資料模型](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=zh-Hant) | 影片 (Skill Builder 活動) | 與我們的 Campaign 培訓師一起參加此會議，了解如何在 Campaign Classic 中的資料模型內開發資料結構描述。 | Campaign Classic v7 |
| 2022 年 7 月 | [推動成果的可交付性最佳實務和策略](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html?lang=zh-Hant) | 影片 | 了解如何最大限度地減少您的電子郵件行銷活動的規劃和製作所花費的無數時間。 | Campaign ClassicV7 |
| 2022 年 7 月 | [使用 Adobe Campaign Classic 提升您的跨管道行銷](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=zh-Hant) | 影片 | 觀看這個深入探討 Adobe Campaign Classic 客戶的工作流程、自動化、個人化和衡量的網路研討會。 | Campaign ClassicV7 |
| 2022 年 7 月 | [專業人士的省時祕訣！](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=zh-Hant) | 影片 | 透過 Adobe Campaign 專業人士的提示和祕訣，開始新的一年！了解如何更高效地建立和啟動行銷活動，以及如何提供更有意義和量身定制的跨管道體驗。 | Campaign ClassicV7 |
| 2022 年 7 月 | [Adobe Campaign 與行銷生態系統的整合](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=zh-Hant) | 影片 | 了解 Adobe Campaign 與行銷生態系統的整合。Adobe Campaign 等跨管道行銷解決方案不應與其他技術或團隊區隔開來。不要讓不同的系統阻礙對客戶的全面了解，並破壞跨管道策略。 | Campaign ClassicV7 |
| 2022 年 7 月 | [Adobe Campaign Standard 客戶焦點 - Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=zh-Hant) | 影片 | 聽聽 Microsoft® 行銷團隊分享他們如何使用 Adobe Campaign Standard、他們的架構和指導原則，以及最佳實務。 | Campaign Standard |
| 2022 年 7 月 | [Adobe Campaign 客戶焦點 - Center Parcs](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=zh-Hant) | 影片 | 聽聽 Adobe Campaign 客戶分享他們如何克服挑戰、適應新常態、提高行銷活動管理效率，以及透過 Adobe Campaign 推動有意義的價值。 | Campaign ClassicV7 |
| 2022 年 7 月 | [Adobe Campaign Classic V7 與 V8](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=zh-Hant) | 影片 | 從我們的產品經理那裡了解最新的產品更新，並了解 V7 和 V8 之間的差異。 | Campaign Classic v7、Campaign v8 |
| 2022 年 7 月 | [主題演講 - 跨 B2B 和 B2C 的客戶歷程趨勢和創新](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=zh-Hant) | 影片 | 了解跨 B2B 和 B2C 的客戶歷程管理的最新趨勢。查看關鍵歷程應用程式和更廣泛的 Adobe Experience Cloud 和平台的最新創新。 | Marketo、Campaign Classic v7、Campaign v8 |
| 2022 年 7 月 | [Adobe Campaign Standard 的重要提示和祕訣](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=zh-Hant) | 影片 | 開始了解您的 Adobe Campaign Standard 執行個體，並探索有關目標定位、個人化和行銷疲勞的最佳實務，以更有效地使用 ACS。 | Campaign Standard |
| 2022 年 7 月 | [支援跨管道行銷所需的團隊、技能和組織設計](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html?lang=zh-Hant) | 影片 | 了解如何能夠隨時隨地以您想要的方式參與。了解擁有一個支援規劃、執行和衡量的行銷組織的重要性。 | Campaign Classic v7、Campaign v8、Campaign Standard |

{style=&quot;table-layout:auto&quot;&quot;

### Campaign 說明資源

* Adobe Campaign v8：[文件](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html?lang=zh-Hant) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hant)
* Adobe Campaign Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hant) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hant) - [操作說明影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en)- [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hant) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hant) 操作說明影片

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

有了 Journey Optimizer，您就可以從單一應用程式為幾百萬名客戶管理排程的全通路行銷活動及一對一時刻，還有智慧型決策和見解讓整個旅程最佳化。

### 最新 Journey Optimizer 產品版本

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hant?lang=en)中最新功能、改進功能和修正。

### 全新的 Journey Optimizer 教學課程和其他課程 {#tutorials-ajo}

針對 Adobe Journey Optimizer 發佈的新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 7 月 | [設定訊息頻率規則](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html?lang=zh-Hant) | 影片 | 瞭解如何建立、啟動、測試並報告頻率規則。 瞭解如何確定訊息繼承的頻率規則。 |
| 2022 年 7 月 | [設定、編寫及傳遞簡訊](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html?lang=zh-Hant) | 影片 | 了解如何設定、編寫並將簡訊納入您的客戶歷程中。 |
| 2022 年 7 月 | [簡訊的傳入關鍵字支援](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html?lang=zh-Hant) | 影片 | 了解原生簡訊的傳入關鍵字支援 (啟動、停止、取消停止) 的工作原理。 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Journey Optimizer] 的更多資源

* [Journey Optimizer 文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=zh-Hant)
* [決策管理文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=zh-Hant)

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
| 2022 年 7 月 | [Marketo Engage 和 Adobe Experience Cloud 的 B2B 體驗](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-experiences.html?lang=zh-Hant) | 影片 | 取得 Marketo Engage 和 Adobe Experience Cloud 應用程式之間整合的逐步解說，以及將解決哪些痛點。 | Marketo Engage |
| 2022 年 7 月 | [最佳拍檔 - Adobe Marketo Engage 和 Real-Time CDP](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-campaigns.html?lang=zh-Hant) | 影片 | 了解如何使用 Marketo Engage 和 RT-CDP (B2B 版本) 來編排 B2B 行消活動，以及解鎖的主要使用案例和優勢有哪些。 | Marketo、Real-time Customer Data Platform |

{style=&quot;table-layout:auto&quot;&quot;

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

上次更新日期：**2022 年 7 月 27 日**

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 詳細目錄] | （7月27日發佈） [!UICONTROL 拍賣真知灼見] 是一種新的故障排除工具，允許您分析有保證和無保證的私有交易的交易組成。 使用資料可視化，此工具顯示在特定時間段內為關鍵拍賣屬性接收的值的趨勢和相對比例。 |

{style=&quot;table-layout:auto&quot;&quot;

### [!DNL Advertising Cloud Search] 中的新功能 {#adcloud-search}

上次更新日期：**2022 年 7 月 27 日**

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 行銷活動] | (所有廣告商的選擇性試用版功能；7月16日發佈)您現在可以建立和管理 [!DNL Google Ads] 績效最大市場活動，包括人工建立資產組和上載資產。 指向 [!DNL Google Merchant Center] 不支援產品源。<br><br>一旦您選擇試用版，您就可以使用 [!UICONTROL 市場活動類型] &quot;[!UICONTROL 效能最大值]」並在市場活動設定中設定資產組。 您還可以使用表格和趨勢圖格式查看現有績效最大市場活動 [!UICONTROL 市場活動] 的子菜單。 在報告和Adobe Analytics(對於具有 [!DNL Analytics] 整合)。<br><br>要選擇試用版，請與 [!DNL Adobe] 客戶團隊。 |
|  | [!DNL Google Ads] 不再為標準購物活動、動態搜索廣告或定位提供廣告級效能資料。 |
| [!UICONTROL 市場活動]。 [!DNL Advanced Campaign Management]。 [!UICONTROL 報告] | （7月16日發佈）([!DNL Google Ads] 和 [!DNL Microsoft Advertising] 市場活動)現在可以提供以下支援，用於響應性搜索廣告：<ul><li>的 [!UICONTROL 廣告] 「視圖」(View)現在顯示響應性搜索廣告的預覽。</li><li> （自6月20日起）現在，您可以根據清單的內容使用特定於搜索引擎的廣告模板建立動態響應的搜索和變體 [!UICONTROL 市場活動] > [!UICONTROL 高級(ACM)]。</li><li>的 [!UICONTROL 廣告變體報告] 包括兩個新的自定義列：&quot;[!UICONTROL 創意標題]，是廣告標題行的逗號分隔清單，[!UICONTROL 說明]，是廣告說明行的逗號分隔清單。</li></ul> |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

專為 Adobe Document Cloud 發佈的新教學課程和課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2022 年 7 月 | [使用核准者角色](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/add-an-approver.html?lang=zh-Hant) | 影片 (已更新) | 了解如何透過審核流程傳送文件。 | Adobe Sign |
| 2022 年 7 月 | [設定網頁表單](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/webform.html?lang=zh-Hant) | 影片 (已更新) | 了解如何建立可直接在您的網站上以電子方式簽署的文件。 | Adobe Sign |
| 2022 年 7 月 | [使用委派者角色](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=zh-Hant) | 影片 (已更新) | 說明 | Adobe Sign |
| 2022 年 7 月 | [以電子方式簽署文件](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/electronically-sign-a-document.html?lang=zh-Hant) | 影片 (已更新) | 了解使用 Acrobat Sign 對傳送給您的文件進行簽署有多麼簡單。 | Adobe Sign |
| 2022 年 7 月 | [協助 Acrobat Sign 管理員快速上手並執行](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/up-and-running-admin.html?lang=zh-Hant) | 影片 (已更新) | 了解管理員應該關注的七個關鍵領域，以便在 Acrobat Sign 中快速上手並執行。 | Adobe Sign |
| 2022 年 7 月 | [在 Outlook 中傳送以索取簽名](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/send-for-signature-with-outlook.html?lang=zh-Hant#) | 影片 (已更新) | 了解如何透過直接在 Microsoft® Outlook 中傳送文件以索取簽名，簡化文件工作流程。 | Adobe Sign |
| 2022 年 7 月 | [在 Outlook 中填寫和簽署](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/fill-and-sign-doc-microsoft-outlook.html?lang=zh-Hant) | 影片 (已更新) | 了解如何透過直接在 Microsoft Outlook 中填寫和簽署表格，簡化文件工作流程。 | Adobe Sign |
| 2022 年 7 月 | [建立和管理群組](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-and-manage-groups.html?lang=zh-Hant) | 影片 (已更新) | 了解如何建立群組、將使用者新增至群組，以及編輯群組設定。 | Adobe Sign |
| 2022 年 7 月 | [將簽署委派給其他人](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/delegate-signing.html?lang=zh-Hant) | 影片 (已更新) | 了解如何將文件的簽署委派給其他人。 | Adobe Sign |

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
