---
title: 最新發行說明
description: 了解  [!DNL Experience Cloud]  產品和服務的最新版本注意事項、新功能和新文件。尋找有關 [!DNL Experience Cloud]、 [!DNL Creative Cloud for enterprise] 和 [!DNL Document Cloud] 最新的說明與教學課程
doc-type: release notes
last-update: March 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: eb5f320b029eb30f548c2016ac51e52c14de8199
workflow-type: tm+mt
source-wordcount: '5696'
ht-degree: 49%

---

# Adobe Experience Cloud 發行說明 - 2022 年 3 月

![橫幅](assets/experience-cloud-banner-3.png)

身為 Experience Maker，您的成功之道始於 [Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home)。尋找廣大的操作說明文件庫、自我引導式教學課程、操作說明影片、所有等級和角色適用的課程、線上同業社群，以及需要時的專家支援。

準備好開始使用了嗎？[進行 5 分鐘測驗並獲勝](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)！

>[!NOTE]
>
>若要收到關於本頁更新的每月電子郵件通知，請訂閱 [Adobe 優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)。 請經常回來查看，持續了解 Experience League 最新消息。

上次更新日期：**2022 年 3 月 21 日**

* [[!DNL Experience League]events](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud — 中央介面元件和管理](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
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

## ![表徵圖](/assets/experience-league.png) [!DNL Experience League] 事件 {#events}

Experience League活動是學習、互動和從Adobe產品專家那裡獲得答案的絕佳場所！

| 事件 | 類型 | 說明 |
| -----------|---------- | ----|
| [Experience League LIVE](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) | 即時和按需視頻 | 由Experience League隊製作的直播節目。 您可以藉此機會與 Adobe 產品專家交流。了解可以透過 Adobe Experience Cloud 應用程式應用可落實的秘訣、技巧和策略。<br> [詳細資訊和過去事件](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) |
| [AEM Gems](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/aem-gems-build-sites-faster-with-aem-headless-and-app-builder/m-p/440205#M31629) | Adobe Live網路研討會 | 使用Adobe快速Bootstrap和部署單頁應SPA用() [!UICONTROL 應用程式生成器] 工作流和工具，而不需要傳統的Experience Manager技能，如Java™和Sling。 使用Experience Manager無頭產品，營銷人員和開發人員可以各自擁有自己領域的專業知識 — 開發人員控制整個應用程式框架、樣式和路由，而營銷人員則決定內容及其顯示方式。<br>**日期：** 3月23日星期三 —  [詳細資訊和註冊](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/aem-gems-build-sites-faster-with-aem-headless-and-app-builder/m-p/440205#M31629) |
| [Adobe Analytics:用資料講述影響力的故事](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b%E2%80%A6%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) | Adobe Live網路研討會 | 當資料是藝術和科學的平衡時，資料講故事是很好的。 那麼，為什麼過度設計它呢？ Adobe Analytics冠軍艾米·阿德討論了三個部分：<ul><li>確定機會或問題</li><li>通過資料進行說明</li><li>提供解決方案</li></ul>**日期：** 3月31日星期四 —  [詳細資訊和註冊](https://engage.adobe.com/adobe-analytics-telling-impactful-stories.html?s_rtid=7015Y0%5b...%5d15Y000003A5SbQAK&amp;sfid=&amp;acctid=&amp;ecp=&amp;sdid=JCNCWJFP&amp;mv=display) |
| [經驗創造者 — Adobe Workfront的技能交流](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) | Adobe Live網路研討會 | 我們非常激動地宣佈了第一版體驗創造者 — Adobe Workfront技能交流將於4月13日舉行。 這個免費的3小時數字學習活動完全集中在Workfront，客戶有機會現場向最瞭解工作管理的專家和同行提問。 不管你是Workfront的新人，還是老練的專家，我們都為大家做點事。 <br>**日期：** 4月13日星期三 —  [詳細資訊和註冊](https://events.bizzabo.com/385867?promo=CustomerM&amp;tr=true) |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=zh-Hant) | 影片 | [!DNL Developers Live] 會展示最新的技術進展和開發人員工具，藉以促進各產業的設計、內容創作工作流程、文件服務和客戶體驗管理。檢視專題演講、了解 Analytics API、客戶資料層、Adobe I/O 開放原始碼專案等等。 |

{style=&quot;table-layout:auto&quot;}

## ![圖示](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status]會提供有關 Adobe 產品及服務中斷、作業中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。 請造訪 [status.adobe.com](https://status.adobe.com/) 來查看。

有關最新版本的資訊，請參閱Adobe系統狀態 [發行說明](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=en#status)。

## ![表徵圖](/assets/ec_appicon_24.png) Experience Cloud — 中央介面元件和管理 {#ecloud}

Experience Cloud [中央UI元件](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hant) 包括首頁和永久產品標題上提供的功能。 這些功能包括用戶配置檔案設定、首選項和搜索。 您還可以找到有關用戶和產品管理、客戶屬性和Experience Cloud受眾的幫助。

| 功能 | 說明 |
| ------- |-------|
| 訪問 _[!UICONTROL 朗瑟]_ 跨越Experience Platform和Journey Optimizer [!UICONTROL 統一搜索] | 您可以通過以下方式訪問最近訪問的對象：Experience Platform和Journey Optimizer的每個頁面 [!UICONTROL 統一搜索] 的子菜單。<br>請參閱 [統一搜索對象和實體](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en) 的子菜單。 |

{style=&quot;table-layout:auto&quot;&quot;

**更多有關 [!DNL Experience Cloud Central UI Components] 與管理的說明資源**

* Experience Cloud Central UI Components [發行說明](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en)
* Experience Cloud (管理) [使用者和產品管理](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en)
* Places Service [發行說明](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=zh-Hant)
* [People - 客戶屬性和對象庫](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)產品文件
* [整合式搜尋，用來搜尋物件和實體](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en)

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Experience Platform 和 [!UICONTROL Mobile SDK] 的最新版本資訊和新文件：

發行日期：**2022 年 3 月 7 日**

* [Experience Platform 發行說明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=zh-Hant)

### 最新 Experience Platform 教學課程與其他課程 {#tutorials-platform}

針對 Experience Platform 所發佈的新影片、教學課程或其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [在移動應用教程中實施Adobe Experience Cloud](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/overview.html) | 課程 | 瞭解如何使用Adobe Experience PlatformAdobe Experience CloudSDK在您的移動應用中實施Mobile應用程式。 |
| 2022 年 3 月 | [生成第一方設備ID](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/generate-first-party-device-ids.html) | 影片 | 瞭解如何生成第一方設備ID及其工作方式。 |
| 2022 年 3 月 | [設定資料串流](https://experienceleague.adobe.com/docs/platform-learn/data-collection/edge-network/configure-datastreams.html) | 影片 | 瞭解如何為Web和MobileSDK實現建立和配置資料流。 |

{style=&quot;table-layout:auto&quot;&quot;

### Adobe Mobile SDK

如需了解 Adobe Experience Platform Mobile SDK，請參閱[版本注意事項和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes)。

## ![圖示](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

發行日期：**2022 年 3 月 23 日**

* Adobe Analytics [發行說明](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hant) (**新位置**)
* Adobe Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html?lang=zh-Hant)

### AppMeasurement {#appm}

發行版本：**2.22.4**

* [JavaScript 適用的 AppMeasurement 發行說明](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)

### 最新 Analytics 教學課程與其他課程 {#tutorials-analytics}

針對 Adobe Analytics 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [有關如何簡化和花費更少時間培訓用戶的技巧和技巧](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/simplify-training-users.html?lang=en) | 影片和文章 | 瞭解訓練有素的Adobe Analytics組織在您的業務中對成功的重要性。 |
| 2022 年 3 月 | [打造賦權社群](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/key-admin-skills/empowered-community.html) | 影片和文章 | 瞭解增強分析社區的價值以及如何建立和支援社區。 |
| 2022 年 3 月 | [建立市場營銷渠道處理規則](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/create-marketing-channel-processing-rules.html?lang=en) | 影片 | 瞭解如何配置 [!UICONTROL 處理規則] 為 [!UICONTROL 營銷渠道]。 |
| 2022 年 3 月 | [在報表套件中設定市場營銷渠道](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/set-up-marketing-channels.html) | 影片 | 在此視頻中，瞭解如何在分析報告套件中配置市場營銷渠道報告。 |
| 2022 年 3 月 | [從Adobe Analytics過渡到Google Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/intro-to-analytics/transitioning-from-other-platforms/transition-from-google-analytics.html?lang=en) | 影片 | 用於過渡到 [!DNL Adobe Analytics] 從 [!DNL Google Analytics]。 |
| 2022 年 3 月 | [配置層次結構變數](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-hierarchy-variables.html?lang=en) | 影片 | 瞭解如何以及何時設定和配置站點的層次結構變數。 此功能可用於顯示站點上頁面的分層視圖，以及每個節點的通信量。 |
| 2022 年 3 月 | [在Analysis Workspace建立和共用](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/curation-and-sharing-in-analysis-workspace.html?lang=en) | 影片 | 學習如何在Analysis Workspace處理課程和共用項目。 |
| 2022 年 3 月 | [直接連結到Analysis Workspace的項目](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/direct-link-to-a-project.html?lang=en) | 影片 | 瞭解如何通過建立縮短連結來將同事直接帶到您的Analysis Workspace項目，從而更好地實現分析民主化。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

發行日期：**2022 年 3 月 23 日**

* Customer Journey Analytics [發行說明](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hant) (**新位置**)
* Customer Journey Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hant)

## ![圖示](/assets/audience-manager.png) Audience Manager {#aam}

修復和改進Audience Manager:

| 改善 | 說明 |
| -----------| ---------- |  
| 屬於其他公司的目標資料源的驗證程式 | Audience Manager對 [批處理資料登錄](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=en)。 為防止意外檔案和資料登入其他合作夥伴擁有的目標資料源，Audience Manager在合作夥伴ID(PID)和其他合作夥伴擁有的資料源(DPID)之間添加了映射要求。 <ul><li>另請參見__DPID_TARGET_DATA_OWNER_ 欄位 [Amazon入站資料檔案的S3名稱和檔案大小要求](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=en#name-elements)。</li><li>Adobe內部顧問和客戶服務應改為 [管理對第二方資料的登機訪問](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=en) 有關新映射的資訊需要改進以及如何請求新映射</li><li>是 _不_ 請求現有資料共用關係的映射。 映射也 _不_ 將資料載入到屬於您的PID的目標資料源時需要。</li></ul> |

{style=&quot;table-layout:auto&quot;&quot;

如需自助資源，請參閱 Experience League 上的 [Audience Manager 文件與教學課程.](https://experienceleague.adobe.com/docs/audience-manager.html?lang=zh-Hant)

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

Adobe 建議您造訪 [Experience Manager 版本更新與藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=zh-Hant)頁面，以掌握最新的版本資訊。

### Experience Manager 產品更新

* **Experience Manager6.5, Service Pack 12(6.5.12.0)**

   Adobe Experience Manager6.5.12.0包括自2019年4月6.5版發佈以來發佈的新功能、客戶要求的關鍵增強功能以及效能、穩定性和安全性改進。 Service Pack安裝在Adobe Experience Manager6.5上。

   查看 [發行說明](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=zh-Hant)。

### Experience Manager 產品發行

* **Experience Manager as a Cloud Service**

   * [2022年1月發佈概述視頻](https://video.tv.adobe.com/v/340120) 功能。
   * [2021 年 12 月版本新功能的總覽影片](https://video.tv.adobe.com/v/339278)。
   * [](https://video.tv.adobe.com/v/338253)2021 年 10 月版本總覽 新功能影片。
   * [](https://video.tv.adobe.com/v/337381)2021 年 9 月版本總覽 新功能影片。

   * **Experience Manager Assets as a Cloud Service**

      _Experience Manager Assets 新功能_

      * Dynamic Media - 您現在可以使用 Experience Manager - Dynamic Media 介面進行設定，包括[一般設定](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html?lang=zh-Hant)和[發佈設定](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html?lang=zh-Hant)，而不必透過 Dynamic Media Classic 桌面應用程式來進行。
      * Dynamic Media 現在支援 MXF 影片的攝取、預覽、播放和發佈。 尚不支援 MXF 影片的附註和可訂購影片。
      * 在設定遠端 DAM 和 Sites 部署之間的連接後，遠端 DAM 上的資產可在 Sites 部署中使用。 您現在可以在遠端 DAM 資產或檔案夾上執行[更新、刪除、更名和移動操作](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=zh-Hant)。這些更新在 Sites 部署中可自動使用，但有一些延遲。

      _Experience Manager Assets 發行前管道中的新功能_

      * Dynamic Media 現在可讓您彈性地在使用者介面中[設定一個公司別名帳戶](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=zh-Hant)，以確保更新開箱即用的 Dynamic Media URL 和 Viewer Embed 程式碼。此舉對 SEO 產生了積極影響，可反映對企業內容所做的更新，例如品牌重塑。
      * 現在可以使用 Experience Manager Assets 使用者介面以便：

         * 設定存放庫中重複資產的偵測。
         * 設定影像中新增數位浮水印。
      * 管理員現在可以設定電子郵件服務以進行大量下載。它可讓使用者從 Experience Manager Assets 介面[啟用大量下載的電子郵件通知](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=zh-Hant#enable-email-notifications-for-large-downloads)。使用者在完成下載後會收到電子郵件通知，其中包含封存 zip 檔案夾的下載連結。
      * [管理發佈](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hant)功能有改進的使用者介面。使用者可以將內容發佈或取消發佈到選定目標，並從 DAM 存放庫[新增內容](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hant#add-content)到發佈清單。此外也可以[包含檔案夾設定](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hant#include-folder-settings)以發佈所選檔案夾的內容並套用篩選器，以及[排程發佈](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=zh-Hant#publish-assets-later)到更晚的日期或時間。

      _錯誤修正_

      * 沒有原始轉譯的未處理資產會傳送到 Asset Compute 進行處理，同時將資產從 Experience Manager 內部部署移轉到 Cloud Service。
   * **Experience Manager Forms as a Cloud Service**

      _Forms 的新增功能_

      * **Experience Manager Forms as a Cloud Service - 通訊** - [Communications API](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=zh-Hant) 可幫助您合併範本和 XML 資料，以產生多種格式的列印文件。此服務可讓您以同步和批次模式產生文件。這類 API 可協助您建立具有以下功能的應用程式：

         * 使用 XML 資料填寫範本檔案來產生文件。
         * 產生多種格式的表單，包括非互動式 PDF 列印資料流。
         * 從 XFA 表單 PDF 產生列印 PDF。
         * 透過將多組資料與來源範本合併，大量產生 PDF、PostScript、PCL 和 ZPL 文件。
      * **記錄文件和使用 Communications API 建立的 PDF 文件適用的自訂字體** – 現在，您可以在使用 Communications API 產生的 PDF 文件中使用品牌核准的字體，以符合組織要求。

      _Forms 發行前管道的新增功能_

      * [Assembler API](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/) – Assembler API，用於組合、重新排列、增大 PDF 文件和取得相關資訊。
   * **Cloud Manager**

      _發行日期_

      Experience Manager as a Cloud Service 2022.01.0 中的 Cloud Manager 發行日期是 2022 年 1 月 20 日。
下一版計畫於2022年3月31日發行。

      _新功能_

      * Cloud Manager [在偵測到多個全堆疊管道執行中使用了相同的 git 認可時，會避免重建程式碼基底](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=zh-Hant#build-artifact-reuse)。
      * 現在存取 Experience Manager 環境記錄檔需要 **[!UICONTROL Deployment Manager]** 產品設定檔。沒有此設定檔的使用者將在使用者介面中看到停用按鈕。
      * 用戶介面不允許為未將站點作為解決方案啟用的程式配置前端管道。
      * 在產生 Git 密碼時，將顯示到期日期。








### 社群

* **Experience Manager GEM 網路研討會：_使用 Experience Manager Headless 和 App Builder 更快建立網站_**

   * 你錯過了2022年Adobe Summit的開場主旨演講嗎？ 監視 [讓數字經濟成為個人經濟](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2022-opening-keynote-make-the-digital-economy/td-p/444612)。
   * Adobe Summit2022 | [完成Experience Manager會話清單](https://adobe.ly/3rti6gF)。
   * Experience Manager寶石。 |網路研討會 | 2022年3月23日星期三
      * 主題： *使用無Experience Manager頭和App Builder更快地構建站點*
      * [按一下這裡報名](https://adobe.ly/3oCkEsh)
      * [問答](https://adobe.ly/3LkSWdm)

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2022 年 3 月 | [開始使用無AEM頭](https://experienceleague.adobe.com/landing/experience-manager/headless/developer.html?lang=zh-Hant) | 課程 | 創AEM建無頭登錄頁，將ExL上無頭上的所有AEM內容匯集在一起。 | 無AEM頭 |
| 2022 年 3 月 | [在Adobe Experience Manager as a Cloud Service建立第一個網站](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.1.aemcs.website) | 課程 | 使用預定義的站點模板快速生成Experience Manager中的新網站。 | AEM Sites |
| 2022 年 3 月 | [從提交的資料xml中提取節點](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/extract-xml-node.html?lang=en) | 影片 | 瞭解此自定義流程步驟，通過從另一個XML文檔中提取節點來建立XML文檔。 當要將提交的資料與XDP模板合併以生成PDF時，請使用此流程。 | AEM Forms |
| 2022 年 3 月 | [將文檔寫入檔案系統](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/custom-workflow-steps/write-payload-document.html?lang=en) | 影片 | 瞭解如何將工作流中生成的文檔寫入檔案系統。 | AEM Forms |
| 2022 年 3 月 | [自定義函式](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/custom-functions-aem-forms.html?lang=en) | 影片 | AEM Forms6.5引入了定義JavaScript函式的功能，這些函式可用於使用規則編輯器定義複雜業務規則。 | AEM Forms |
| 2022 年 3 月 | [WorkfrontExperience Manager增強連接器專家系列](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/overview.html?lang=en) | 影片 | 與Adobe的Workfront和Experience Manager Assets專家一起參加這四個部分的視頻系列，展示和討論Workfront的Experience Manager增強連接器的進出點。 | AEM Assets,Workfront |
| 2022 年 3 月 | [級聯下拉清單](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/some-useful-integrations/geonames-org.html?lang=en) | 影片 | 一個教程，其中包含示例資產，用於建立具有級聯下拉清單的表單。 | AEM Forms |
| 2022 年 3 月 | [初始設定和配置](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/setup.html?lang=en) | 影片 | 瞭解如何設定和配置Workfront以Experience Manager增強型連接器，從而釋放AEM Assets和Workfront的聯合電源。 | AEM Assets,Workfront |
| 2022 年 3 月 | [Workfront自定義表單和元資料映射](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/custom-forms.html?lang=en) | 影片 | 瞭解如何配置Workfront和AEM Assets，以使用Workfront自定義表單和元資料架構管理和同AEM步資產元資料。 | AEM Assets,Workfront |
| 2022 年 3 月 | [標AEM記、項目連結資料夾和資料夾元資料](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/aem-tags-project-linked-folders-and-folder-metadata.html?lang=en) | 影片 | 瞭解如何通過AEMWorkfront資料、設定和使用項目連結的資料夾以及Workfront資料驅動資產上的標籤使AEM用的資產資料夾元資料架構。 | AEM Assets,Workfront |
| 2022 年 3 月 | [高級設定和工作流](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/workfront/enhanced-connector/aem-experts-series/advanced-settings-and-workflows.html?lang=en) | 影片 | 瞭解Workfront的高級設定，以AEM及如何在中配置高級工作流和啟動程式，以管AEM理資料在與AEMWorkfront之間的同步。 | AEM Assets,Workfront |
| 2022 年 3 月 | [建立和配置Dynamics帳戶](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/formscs-dynamics-crm/create-dynamics-account.html?lang=en) | 影片 | 瞭解在Azure Active Directory中註冊Microsoft® Dynamics的步驟。 | AEM CS |
| 2022 年 3 月 | [公共連結共用](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/link-sharing.html) | 影片 | 瞭解Assets Essentials的共用連結如何允許用戶與內部和外部利益相關方共用資產，同時最大限度地降低共用錯誤資產或資訊的風險。 | AEM Assets |

{style=&quot;table-layout:auto&quot;&quot;

### Experience Manager 版本資訊

所有 Experience Manager 的發行說明都會保留在以下頁面：

* [Experience Manager as a Cloud Service 發行說明](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hant)
* [Experience Manager Cloud Manager 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=zh-Hant)
* [Automated Forms Conversion Service 版本注意事項](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hant)
* [Experience Manager 6.5 Service Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
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

### 新教程 [!DNL XML Documentation for Adobe Experience Manager] {#tutorials-xml-doc}

為發佈的新視頻、教程或課程 [!DNL XML Documentation for Adobe Experience Manager]。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [使用XML文檔生成輸出](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2022.2.xmldocs) | 課程 | 瞭解如何使用 [!DNL XML Documentation for Adobe Experience Manager]。 瞭解可用於生成輸出的各種功能，包括報告、基線、條件、故障排除、批量發佈和激活。 |

{style=&quot;table-layout:auto&quot;&quot;

### 其他資源

* [適用於 Adobe Experience Manager 的 XML 文件](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=zh-Hant) - Experience League 上的教學課程。
* [適用於 Adobe Experience Manager 的 XML 文件學習與支援](https://helpx.adobe.com/tw/support/xml-documentation-for-experience-manager.html) - 產品文件

## ![圖示](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

請參閱以下 Adobe Commerce 版本注意事項連結：

* [Adobe Commerce 和 Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite for Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### 新Adobe Commerce資源 {#new-commerce}

Adobe Commerce關於Experience League的新文檔和教程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [支付服務指南](https://experienceleague.adobe.com/docs/commerce-merchant-services/payment-services/guide-overview.html) | 指南 | 為Adobe Commerce和Magento Open Source的管理員準備的指南。 它包括有關支付服務安裝和登入以及服務配置和管理的詳細資訊。 它假定對核心Commerce配置和功能有基本的瞭解。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/target.png) [!DNL Adobe Target] {#target}

上次更新時間： **2022年3月21日**

* 如需發行前版本資訊，請參閱 [Adobe Target 發行說明 (發行前)](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)。
* 如需目前版本資訊，請參閱 [Adobe Target 發行說明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hant)。

## ![圖示](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign 可以在線上和離線行銷管道以直觀的自動化方法提供一對一訊息。您現在可以使用客戶習慣和偏好判斷其體驗，預測他們想要的東西。

### 最新 Campaign 產品發行版

進一步了解已發行的最新功能、改良與修正：

* [Campaign Classic v7.2.2](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=zh-Hant)

### 新 [!DNL Campaign] 教學課程和其他課程 {#tutorials-campaign}

為Adobe Campaign出版的新教程和課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| ------| ----- | -----| ------ | --- |
| 2022 年 3 月 | [整合 Experience Manager — 概覽](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=zh-Hant) | 影片 | 連結 Adobe Campaign 與 Adobe Experience Manager，以便能夠管理 Experience Manager 的電子郵件傳遞範本、資產和表單。 | AEM，第8版活動 |
| 2022 年 3 月 | [設定 Campaign 來整合 Experience Manager](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/configure-campaign-for-aem-integration.html?lang=en) | 影片 | 瞭解如何設定Experience Manager與活動之間的整合，包括要查找的重要設定和要避免的潛在「陷阱」。 | AEM，第8版活動 |
| 2022 年 3 月 | [核准 Experience Manager 頁面並發佈到 Campaign](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/approve-and-publish-aem-content-to-campaign.html?lang=en) | 影片 | 瞭解如何建立 Experience Manager 電子報，以及如何核准並發佈到 Campaign。 | AEM，第8版活動 |
| 2022 年 3 月 | [在市場活動中同步和發送Experience Manager電子郵件傳遞](https://experienceleague.adobe.com/docs/campaign-learn/integrate-with-experience-manager/create-a-campaign-delivery-with-content-from-experience-manager/synchronize-and-send-an-aem-delivery-in-campaign.html?lang=en) | 影片 | 瞭解如何使用以Experience Manager建立的新聞稿test和從Adobe Campaign發送電子郵件。 | AEM，第8版活動 |
| 2022 年 3 月 | [與Adobe Target整合](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/connect/target-integration.html) | 影片 | 瞭解如何通過Adobe Target提供的動態內容個性化交付。 | Adobe Target，第8版戰役 |

{style=&quot;table-layout:auto&quot;&quot;

### Campaign 說明資源

* Adobe Campaign v8：[文件](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=zh-Hant) - [發行說明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=zh-Hant)
* Adobe Campaign Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=zh-Hant) - [做法影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=zh-Hant) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [做法影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=zh-Hant) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=zh-Hant)
* Adobe Campaign 控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant) - [版本注意事項](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=zh-Hant)- [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=zh-Hant) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=zh-Hant) 做法影片

## ![圖示](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

有了 Journey Optimizer，您就可以從單一應用程式為幾百萬名客戶管理排程的全通道行銷活動及一對一時刻，還有智慧型決策和見解讓整個旅程最佳化。

### 最新 Journey Optimizer 產品發行版

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=zh-Hant)中最新功能、改良功能和修復。

### Journey Optimizer 教學課程和課程 {#tutorials-ajo}

最新的 Journey Optimizer 教學課程：

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [使用和管理個性化庫中保存的表達式](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/personalize-content/use-and-manage-saved-expressions-in-personalization-library.html?lang=en) | 影片 | 瞭解如何在郵件中使用保存的個性化庫項目，以及如何建立和管理個性化庫項目。 |

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

### Marketo新教程和課程 {#tutorials-marketo}

為AdobeMarketo出版的新教程和課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [建立和管理個性化對話框](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/dialogue-management.html?lang=en) | 影片 | 瞭解如何建立和管理 _[!UICONTROL 對話框]_。 設計有針對性的個性化對話是為每位Web訪問者創造良好對話體驗的關鍵。 |
| 2022 年 3 月 | [安裝並安裝聊天機](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/setup.html?lang=en) | 影片 | 幫助您將JavaScript安裝到網站或登錄頁上並自定義外觀以與品牌相匹配的指南。 |
| 2022 年 3 月 | [允許人員預訂與銷售團隊的會議](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/meeting-booking.html?lang=en) | 影片 | 使用 [!UICONTROL 動態聊天] 加快目標客戶銷售線索與銷售的連接。 |
| 2022 年 3 月 | [激活您的Marketo整合 [!UICONTROL 動態聊天]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/marketo-integration.html?lang=en) | 影片 | [!UICONTROL 動態聊天] 本機整合到Marketo Engage中，使您能夠使用聊天機對話中的上下文來重新確定目標或為潛在客戶打分。 |
| 2022 年 3 月 | [管理用戶 [!UICONTROL 動態聊天]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/user-management.html?lang=en) | 影片 | 管理 [!UICONTROL 動態聊天] 用戶通過Adobe Admin Console。 |
| 2022 年 3 月 | [產品導覽 [!UICONTROL 動態聊天]](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/dynamic-chat/product-tour.html?lang=en) | 影片 | [!UICONTROL 動態聊天] 是為營銷和銷售而構建的新Chatbot解決方案。 它與Marketo Engage本機整合，使您能夠將動態聊天用作跨渠道營銷中的新渠道。 本發明使用簡單，安裝方便。 |

## ![圖示](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] 是統一的工作管理應用程式，用於共用構想、建立內容、管理複雜的流程並執行其最佳工作。

請參閱 [[!DNL Workfront]  發行版本](https://one.workfront.com/s/product-releases)頁面，以取得所有產品的最新資訊匯總。

## ![圖示](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

[!DNL Adobe Advertising Cloud] 版本注意事項。

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
<!-- * [New features in [!DNL Advertising Cloud DSP]](#adcloud-dsp) -->
* [ [!DNL Advertising Cloud Search] 中的新功能](#adcloud-search)
* [新  [!DNL Advertising Cloud] 教學課程](#tutorials-ad-cloud)

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

上次更新時間： **2022年3月14日** 為3月12日發行

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 產品組合] | 預設情況下，混合優化在市場活動級別可用。 現在，您可以選擇在優化功能集的ad組級別啟用混合優化 [!DNL Google] CPA或ROAS目標為廣告組級別，以更精確地控制表現。<br>對於任何產品組合，在啟動產品組合之前必須允許一段學習期，以確保其具有足夠的模型覆蓋範圍。 同樣，如果將混合產品組合從市場活動級別更改為廣告組級別優化，則將組合設定為活動狀態大約兩週。 這確保優化功能有時間瞭解包含的廣告組並生成目標。<br>為支援廣告組級優化，定制模擬現在可以按廣告組包括結果。 在啟動具有廣告組級優化的混合產品組合之前，使用廣告組級結果運行自定義模擬。 |
| [!UICONTROL 產品組合] <br> [!UICONTROL 行銷活動] | (Beta功能， [!DNL Microsoft® Advertising] 市場活動) — 您現在可以配置搜索市場活動以使用 [!UICONTROL 最大化轉換] 投標策略，並可選地設定每次按一下的最大成本。<br>如果您已參與其它自動投標策略的混合優化測試，則您將自動擁有 [!UICONTROL 最大化轉換] 策略，您可以將市場活動 [!UICONTROL 最大化轉換] 混合投資組合策略。 要在混合產品組合中使用此策略，必須啟用將Advertising Cloud Search目標上載到 [!DNL Microsoft® Ads]。 如果您尚未參與測試並想加入，請與 [!DNL Adobe] 客戶經理。 |
| 活動 [!UICONTROL 觀眾]<br><br>活動 [!UICONTROL 布爾克謝特] | ([!DNL Microsoft® Advertising] 市場活動) — 您現在可以使用 [!DNL Microsoft® Advertising] 除市場受眾之外的受眾是競選級別的目標或 [!UICONTROL 組]-level目標。 以前，您只能將它們用作 [!UICONTROL 組]-level目標。 |
| 活動 [!UICONTROL 觀眾] | (Beta功能， [!DNL Microsoft® Advertising] 符合條件的帳戶 [!UICONTROL 客戶匹配])現在，您可以通過上傳包含電子郵件地址的CSV檔案來建立和管理客戶匹配的受眾。 必須使用SHA-256算法對資料進行散列。 |

{style=&quot;table-layout:auto&quot;&quot;

### 新 Advertising Cloud 教學課程 {#tutorials-ad-cloud}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [如何建立標準顯示放置](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/placement-create.html) | 影片 | 瞭解如何為Advertising Cloud DSP市場活動建立標準顯示位置。 |

{style=&quot;table-layout:auto&quot;&quot;

## ![圖示](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

為Adobe Document Cloud出版的新教程和課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 3 月 | [自定義命令和工具](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/custom.html?lang=en) | 影片 | 瞭解如何使用自定義命令和工具提高文檔工作流的工作效率。 然後，與同事共用您的新命令和工具，以幫助提高組織效率。 |
| 2022 年 3 月 | [添加書籤和超連結](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/bookmarks.html?lang=en) | 影片 | 瞭解如何添加書籤和超連結，以便更好地導航和與PDF檔案交互。 |
| 2022 年 3 月 | [優化掃描的文檔](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizescan.html) | 影片 | 無論您的文檔來自攝像頭還是掃描器，請瞭解如何在Acrobat增強結果，以獲得更好的PDF查看和搜索體驗。 |
| 2022 年 3 月 | [將Word轉換為包括表單域的PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/wordform.html?lang=en) | 影片 | 在本60秒的視頻教程中，瞭解如何將Word檔案和表單轉換為PDF並自動生成表單域。 |
| 2022 年 3 月 | [高級表單域](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/advancedforms.html?lang=en) | 影片 | 在本實踐教程中，瞭解如何設定計算、建立電子郵件提交按鈕以及快速更新表單頁面，而無需重建所有現有表單域。 |
| 2022 年 3 月 | [在快照中建立更高效的PDF檔案](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/optimize.html?lang=en) | 影片 | 在此60秒視頻教程中，瞭解如何使用Optimize PDF工具顯著減小PDF檔案的大小。 |
| 2022 年 3 月 | [識別掃描的PDF檔案中的文本](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/textrecognition.html?lang=en) | 影片 | 在本60秒視頻教程中，瞭解如何轉換掃描的PDF，以便您可以在PDF中搜索文本。 |
| 2022 年 3 月 | [讓Acrobat幫助您使易於訪問的PDF](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/accessible.html?lang=en) | 影片 | 在此60秒視頻教程中，瞭解如何檢查PDF是否可訪問。 |
| 2022 年 3 月 | [Export PDF到Word](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/exportwordphone.html?lang=en) | 影片 | 在此60秒視頻教程中，瞭解如何使用Acrobat移動應用將PDF檔案轉換為完全可編輯的Microsoft® Word文檔。 |
| 2022 年 3 月 | [Protect你的PDF檔案](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/protect.html?lang=en) | 影片 | 在本60秒的視頻教程中，瞭解如何保護PDF，以便開啟或編輯PDF時需要密碼。 |

{style=&quot;table-layout:auto&quot;&quot;

如需 Document Cloud 說明，請參閱：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=zh-Hant)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=zh-Hant)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)

## ![圖示](/assets/creative-cloud-24.png) 適用於企業的 Adobe Creative Cloud {#creative-cloud}

如需了解最新教學課程，請參閱「[適用於企業的 Creative Cloud 教學課程](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=zh-Hant)」。

## ![表徵圖](/assets/experience-league.png) 客戶資料管理 — 語音 {#voices}

[客戶資料管理聲明](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) 是您作為客戶資料管理技術和營銷業務領導者和專家的目標。 本教程集是您的一站式服務，可從同行那裡聽取資訊、獲得靈感並瞭解MarTech的發展。 無需註冊，請按一下並觀看。

## ![圖示](/assets/experience-league.png)數位體驗藍圖 {#blueprints}

[數位體驗藍圖](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=zh-Hant)是可重複的實施，可讓您處理策略，並快速解決既定的業務問題。每個藍圖都提供一系列成品，解釋高價值業務問題、架構、實施步驟、技術考量以及相關文件的連結。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2022 年 2 月 | [客戶歷程](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=zh-Hant) | 影片 | 客戶歷程處理品牌如何透過電子郵件、簡訊和行動提醒等管道，主動與客戶互動及溝通的能力。 |
| 2022 年 2 月 | [Campaign v7 藍圖](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=zh-Hant) | 影片 | Adobe Campaign v7 是為了電子郵件和直接郵件等傳統行銷管道而建立的行銷活動工具。它提供強大的 ETL 和資料管理功能，幫助制定和組織完美的行銷活動。 |

{style=&quot;table-layout:auto&quot;&quot;
