---
title: 最新版本注意事項
description: 閱讀 Adobe  [!DNL Experience Cloud]  產品和服務的最新版本注意事項。了解有關 Experience League 即將舉辦的活動和新文件。探索  [!DNL Experience Cloud]  應用程式的最新教學課程和其他課程。
doc-type: release notes
last-update: March 2023
author: mfrei
mini-toc-levels: 2
exl-id: 091f0168-21b0-4f48-a02b-d70e96b84e27
source-git-commit: d340d4d039920764e3853f0f86e9049cf4b4ccfd
workflow-type: tm+mt
source-wordcount: '4620'
ht-degree: 45%

---

# Experience Cloud 發行說明

![橫幅](assets/release-notes-header.png)

## 2023 年 3 月

此頁面可幫助您隨時掌握 Experience League 的產品發行資訊、活動和學習機會。

>[!TIP]
>
>若要收到關於本頁更新的每月電子郵件通知，請訂閱 [Adobe 優先產品更新](https://www.adobe.com/tw/subscription/priority-product-update.html)。請經常回來查看，持續掌握 Adobe 企業應用程式的最新消息。

**需要協助嗎?**

您的成功之道始於 [ Experience League](https://experienceleague.adobe.com/?lang=en#home)。 瀏覽我們龐大的自助[產品文件](https://experienceleague.adobe.com/docs/?lang=zh-Hant)和引導式[教學課程影片](https://experienceleague.adobe.com/docs/home-tutorials.html?lang=en)。 尋找各種等級和角色的[課程](https://experienceleague.adobe.com/?lang=en#courses)，向我們同業的線上[社群](https://experienceleaguecommunities.adobe.com/?profile.language=en)提問，並在您需要時獲得專家[支援](https://experienceleague.adobe.com/?support-tab=home#support)。

## 產品版本更新和事件

上次更新日期：**2023 年 3 月 8 日**

* [[!DNL Experience League] 活動](#events)
* [[!DNL Adobe System Status]](#status)
* [[!DNL Experience Cloud] 介面與管理](#ecloud)
* [[!DNL Experience Platform]](#platform)
* [[!DNL Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)<!-- * [[!DNL Streaming Media Analytics]](#sma) -->
* [[!DNL Audience Manager]](#aam)
* [[!DNL Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Commerce]](#commerce)
* [[!DNL Target]](#target)
* [[!DNL Campaign]](#ac)
* [[!DNL Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Marketo Engage]](#marketo)
* [[!DNL Workfront]](#workfront)
* [[!DNL Advertising]](#advertising)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)<!-- * [Digital Experience Blueprints - tutorials](#blueprints) -->

## ![圖示](/assets/experience-league.png) [!DNL Experience League] 活動 {#events}

了解Experience League上發生了什麼。 活動是您在Adobe學習、互動及向產品專家取得答案的絕佳場所！

+++近期活動

* **[!DNL Analytics]** | _加速使用Adobe Analytics深入分析_ | **3月9日上午8點00分（下午）** |  [註冊](https://adobeanalyticsvirtualanalyst2023.experienceleague.adobeevents.com/)

* **[!DNL Marketo Engage]** | _Marketo和Mochas:傳遞能力（第1部分）_ | **3月9日@下午1:00** | [註冊](https://register.gotowebinar.com/register/6250682251177513567)

* **[!DNL Workfront]** | _連接：策略管理員聊天_ | **3月13日早7點手動** | [註冊](https://teams.microsoft.com/registration/Wht7-jR7h0OUrtLBeN7O4Q,mjTFCSLTbkuVKavNdopApA,dndSyq-qPkqd5A929WkXkw,lgDkllfW8EatH2CVDH9nVQ,JWCg6TzBMUS5dX7i0qHSsA,CjE7t_FXgEaepx27DZn_7g?mode=read&amp;tenantId=fa7b1b5a-7b34-4387-94ae-d2c178decee1)

* **[!DNL Workfront]** | _系統管理要點：使用介面設計改善使用者體驗_ | **3月15日早8點，品脫** | [註冊](https://event.on24.com/wcc/r/4123271/D486841B3D743479F12BAC0C583C10ED?partnerref=exl)

* **[!DNL Marketo Engage]** | _Marketo社區問答茶歇_ | **3月15日上午08點00分（品脫）** | [註冊](https://mecommunityqacoffeebreak0315.splashthat.com/?utm_source=email&amp;utm_medium=Outbound&amp;utm_campaign=coffee_talk_ME&amp;utm_content=230315)

* **[!DNL Adobe Summit]** |_終極體驗又回來了。 與我們一起到拉斯維加斯學習技能、向世界頂級品牌學習並獲得靈感_ | **3月19日上午09點00分（品脫）** | [註冊](https://summit.adobe.com/na/?promoid=2K4PC9V3&amp;mv=other)

請參閱 [Experience League事件](https://experienceleague.adobe.com/events/?lang=en) 以取得近期事件和隨選過去事件的完整排程。

+++

## ![圖示](/assets/system-status.png) [!DNL Adobe System Status] {#status}

了解 [!DNL Adobe System Status].

+++詳細資訊

[!DNL Adobe System Status] 提供有關Adobe產品和服務中斷、中斷和維護事件的詳細資訊、狀態更新和電子郵件通知。 請造訪 [status.adobe.com](https://status.adobe.com/) 來查看。

發行日期：**2023 年 2 月 15 日**

**新增功能**

* [!DNL Status] 已新增API支援，可讓您直接呼叫Adobe的伺服器，以查詢及檢視 [status.adobe.com](https://status.adobe.com/) UI。 您可以使用這些API將整合至您的監視系統或控制面板，從Adobe狀態檢視即時事件。 可以根據「產品」、「產品」、「地區」、「環境」（如果可用）、「地區」和「事件類型」篩選事件。

| 功能 | 說明 |
| ------- | -------|
| Adobe狀態API | <ul><li>Adobe狀態API提供有關Adobe雲產品和服務中斷、中斷和維護事件的詳細資訊和即時更新。</li><li>API需在 [Adobe Developer Console](https://developer.adobe.com/console) 才能使用。 貴組織必須擁有至少一項Adobe產品的權限，才能存取AdobeAPI。 需要具有正確權限的開發人員控制台帳戶。</li><li>請查看文檔 [此處](https://developer.adobe.com/adobe-status/) 並按照指南進行設定。</li><li>完成設定後，您可以使用 [API參考檔案](https://developer.adobe.com/adobe-status/api/) 檢視可用的API和要呼叫的簽名。</li></ul> |

{style="table-layout:auto"}

+++

## ![圖示](/assets/ec_appicon_24.png)Experience Cloud 介面與管理 {#ecloud}

尋找Experience Cloud介面首頁、管理（產品和使用者管理）、使用者設定檔設定、偏好設定、搜尋和Cookie的更新。

+++詳細資訊

_未於3月更新。_

如需協助，請參閱 [Experience Cloud介面和管理指南](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=zh-Hant) 包括 [!UICONTROL 客戶屬性] 和 [!UICONTROL 對象])。

+++

## ![圖示](/assets/experience_platform_appicon_24.png) [!DNL Experience Platform] {#platform}

尋找適用於 [!DNL Experience Platform] 和 [!UICONTROL 行動SDK]. 檢視最新教學課程和知識庫文章，了解Experience League。

+++詳細資訊

* [Experience Platform發行說明](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html)  — 計畫發行 —  **2032年3月29日**

### 新 [!DNL Experience Platform] 教學課程和其他課程

針對 Adobe Experience Platform 所發佈的新影片、教學課程或其他課程。

| 類型 | 產品功能 | 說明 | 應用程式 |
| -----------| ---------- |---------- |---------- |
| 2023 年 3 月 | [使用Adobe Analytics來源連接器擷取資料](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-adobe-analytics.html?lang=zh-Hant) | 已更新的影片 | 從Adobe Analytics串流、對應及篩選資料，並匯入Adobe Experience Platform的「即時客戶個人檔案」和「體驗」資料湖。 | 資料擷取 |

{style="table-layout:auto"}

### [!DNL Experience Platform] 支援知識庫

[!DNL Experience Platform] 的新文章和現有文章的更新。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2023 年 2 月 | [沒有對象大小 [!DNL Microsoft Bing] AEP目的地](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21544.html?lang=zh-Hant) | 新文章 | 了解原因 [!DNL Bing] 不會顯示傳送至AEP之AEP區段的對象大小 [!DNL Bing] 目的地。 |
| 2023 年 2 月 | [RTCDP授權隨附的環境（開發、測試、生產）數量為何？](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21590.html?lang=zh-Hant) | 新文章 | 進一步了解RTCDP授權隨附的環境和沙箱數量。 |
| 2023 年 2 月 | [是否 _套用轉換_ 在雜湊處理前目標啟動標準化（例如小寫）的選項？](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21591.html?lang=zh-Hant) | 新文章 | 進一步了解一般資料標準化及其因應措施。 |

{style="table-layout:auto"}

### [!DNL Mobile] SDK

已更新： **2022年11月11日**  — 請參閱 [發行說明和變更記錄](https://aep-sdks.gitbook.io/docs/release-notes) 針對 [!DNL Adobe Experience Platform] [!DNL Mobile SDKs].

+++

## ![圖示](/assets/analytics.png) [!DNL Analytics] {#analytics}

尋找的最新發行資訊 [!DNL Adobe Analytics] 和 [!DNL AppMeasurement]. 檢視最新的教學課程和Experience League課程。

+++詳細資訊

發行日期：**2023 年 3 月 8 日**

* [!DNL Analytics] [版本注意事項](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=zh-Hant)
* [!DNL Analytics] [產品文件與教學課程](https://experienceleague.adobe.com/docs/analytics.html)

### AppMeasurement {#appm}

發行版本：**2.23.0**

* [JavaScript 適用的 AppMeasurement 版本注意事項](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=zh-Hant)

### 新 [!DNL Analytics] 教學課程和其他課程 {#tutorials-analytics}

專為 Adobe Analytics 發佈的新影片教學課程、文章和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2023 年 3 月 | [Analysis Workspace 中的 RTF 編輯器](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/visualizations/rich-text-editor-in-analysis-workspace.html?lang=en) | 已更新的影片 | 了解可讓分析師和行銷人員在 Analysis Workspace 中套用編輯到文字視覺效果 (或說明) 的功能：粗體、斜體、標題、超連結等等。 |

{style="table-layout:auto"}

+++

## ![圖示](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

尋找的最新發行資訊 [!DNL Customer Journey Analytics]. 檢視最新的教學課程和Experience League課程。

+++詳細資訊

下一版： **2023年3月8日**

* Customer Journey Analytics [版本注意事項](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=zh-Hant)
* Customer Journey Analytics [產品文件與教學課程](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=zh-Hant)

### 新的 Customer Journey Analytics 教學課程和其他課程 {#tutorials-cja}

針對 CJA 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2023 年 3 月 | [將 Customer Journey Analytics 連線至 Experience Platform 資料來源](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/connecting-customer-journey-analytics-to-data-sources-in-platform.html?lang=en) | 影片 | Customer Journey Analytics使用擷取至Adobe Experience Platform的資料集。 在 Workspace 中開始資料分析之前，您需要建立一個連線。 |

{style="table-layout:auto"}

+++

<!-- ## ![Icon](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Latest release: **September 22, 2022**

* [!DNL Streaming Media Analytics] [release notes](https://experienceleague.adobe.com/docs/media-analytics/using/release-notes/release-notes.html?lang=en)
* [!DNL Streaming Media Analytics] [product documentation and tutorials](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=en)

## ![Icon](/assets/audience-manager.png) Audience Manager {#aam}

Updates and new content for [!DNL Audience Manager]. -->

<!--### [!DNL Audience Manager] support knowledge base

New articles and updates to existing articles for [!DNL Adobe Audience Manager]

For self-help resources, see [Audience Manager documentation and tutorials](https://experienceleague.adobe.com/docs/audience-manager.html?lang=en) on Experience League.-->

## ![圖示](/assets/aem.png) Adobe Experience Manager {#aem}

了解Experience Manager中的新功能、修正和更新。 檢視有關Experience League的最新教學課程和知識庫文章。

+++詳細資訊

### [!DNL Experience Manager] 路線圖和發行影片

Adobe 建議您瀏覽以下資源以隨時掌握發行版本資訊：

* [Experience Manager 版本更新和藍圖](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) - 了解 Experience Manager 版本藍圖、之前的版本更新及文件更新。
* [Experience Manager as a Cloud Service 版本更新](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/overview.html?lang=zh-Hant) - 觀看目前和過去版本的[!DNL Experience Manager as a Cloud Service]專題影片概述。
* [Adobe Experience Manager as a Cloud Service 目前版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current.html?lang=zh-Hant) - 閱讀 [!DNL Experience Manager as a Cloud Service]最新版本注意事項。

### 最新版本概觀影片

觀看 [2023 年 1 月版本總覽影片](https://video.tv.adobe.com/v/3413479/?quality=12)，了解 2023.01.0 (2023 年 1 月) 版本新增功能摘要。

### [!DNL Experience Manager Sites] as a [!DNL Cloud Service]

_新功能_

* 此 [!DNL Experience Manager] GraphQL內容傳送API現已支援GraphQL [分頁](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/headless/graphql-api/content-fragments.html?lang=en#paging) 和 [排序](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/headless/graphql-api/content-fragments.html?lang=en#sorting)，讓擷取和轉譯大型內容集更有效率。 GraphQL分頁透過一次在子集中傳回結果而非全部，來改善查詢回應時間。 GraphQL排序功能可讓您以所需順序放置內容集，讓用戶端應用程式更輕鬆處理內容。 在 [!DNL Experience Manager] GraphQL引擎。 現在會從JCR讀取與查詢篩選器對應之較小集的內容。

### [!DNL Experience Manager Assets] as a [!DNL Cloud Service]

_新功能_

* 「資產報表」現在包含管理員 [產生資產下載報表](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/asset-reports.html?lang=en) 從 [!DNL Experience Manager Assets] as a [!DNL Cloud Service] 部署。 此資料可讓管理員從關鍵成功量度中獲得深入分析，以衡量企業內和客戶對資產的採用程度。
* [!DNL Experience Manager Assets]除了在連接到 Azure Blob 儲存體資料來源以使用大量匯入工具擷取資產時支援用於驗證的存取金鑰之外， 現在還[支援 SAS 權杖](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/add-assets.html?lang=zh-Hant#asset-bulk-ingestor)。
* 改善Asset compute中CMYK影像的管理，讓您為CMYK影像產生智慧型裁切和智慧標籤。

_發行前管道中可用的新功能_

* [!DNL Experience Manager Assets] 現在支援 [從Google雲端平台大規模擷取資產](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/add-assets.html?lang=zh-Hant#asset-bulk-ingestor) 使用「批量導入」工具。

### [!DNL Experience Manager Forms] as a [!DNL Cloud Service]

_新功能_

* **[生成非互動式PDF文檔和可打印輸出的工作流步驟](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/create-form-centric-workflows/aem-forms-workflow-step-reference.html?lang=en)**  — 自動建立非互動式PDF文檔，並可打印輸出，以便您的業務流程 [!DNL Experience Manager] 工作流程步驟，簡化檔案產生程式並節省時間。
* **[使用腳注在適用性Forms中提供引證或額外資訊](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/add-components-to-an-adaptive-form/footnotes-richtextsupport.html?lang=en)**  — 在最適化表單中使用腳注，以顯示如何完成或使用表單的資訊。 您也可以用它來提供括弧資訊、版權權限和其他實用資訊。


_發行前管道中可用的新功能_

* [使用資料擷取核心元件來建立最適化Forms](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/adaptive-forms/introduction.html?lang=en) - [使用適用性Forms編輯器](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/creating-adaptive-form-core-components.html?lang=en) 根據標準化資料擷取元件（核心元件）建立表單。 這些元件為您的數位註冊體驗提供自訂功能、縮短開發時間並降低維護成本。
* [基於樣式核心元件的前端管道支援自適應Forms](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/using-themes-in-core-components.html?lang=en)  — 使用可輕鬆自訂的BEM型主題，搭配前端部署管道部署核心元件的適用性Forms，以增強表單的外觀和風格。
* [產生核心元件適用性Forms的記錄檔案](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-core-components/create-an-adaptive-form-on-forms-cs/generate-document-of-record-core-components.html?lang=en)  — 在提交以進行長期存檔、打印或文檔格式時，為基於核心元件的適用性表單建立記錄。
* [將適用性Forms提交至Microsoft® SharePoint和Microsoft® OneDrive](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/configure-submit-actions-and-metadata-submission/configuring-submit-actions.html?lang=en)  — 透過直接將適用性表單資料傳送至Microsoft® SharePoint和Microsoft® OneDrive的能力，簡化資料提交。 您可以提交結構型和無結構型資料。 這些提交操作除了現有的提交操作之外。
* [以「儲存最適化表單為範本」功能有效建立表單](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/create-an-adaptive-form-on-forms-cs/template-editor.html?lang=en#save-an-adaptive-form-as-template-saving-adaptive-form-as-template)  — 將最適化表單儲存為範本，並重複使用下一個最適化表單的範本，以簡化您的表單建立流程。
* [Connect [!DNL Experience Manager Forms] 到JDBC支援的資料庫](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/integrate/use-form-data-model/configure-data-sources.html?lang=en#configure-relational-database-configure-relational-database)  — 輕鬆連接 [!DNL Experience Manager Forms] 資料模型到支援JDBC的資料庫，使您能夠無縫地讀寫資料。
* [使用Open API 3.0與REST端點整合](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/integrate/use-form-data-model/configure-data-sources.html?lang=en#configure-restful-services-open-api-specification-version-20-configure-restful-services-swagger-version30)  — 連接 [!DNL Experience Manager Forms] as a [!DNL Cloud Service] 表單資料模型至支援Open API規格3.0版的REST端點，讓您輕鬆傳送和接收資料。
* [共用最適化表單以供審核](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/adaptive-forms-authoring/authoring-adaptive-forms-foundation-components/create-reviews-forms.html?lang=en)  — 使用適用性Forms審核機制，讓一或多人審核表單。

### CIF 附加元件

_新功能_

* 作者可以使用體驗片段以動態的方式豐富產品清單 (例如：在產品列表之間放置橫幅)。
* 清單元件現在支援相關聯產品/類別頁面以動態顯示相關頁面。
* 已新增 Peregrine 12.5 元件的支援。
* 已新增對產品預告和輪播中用戶端價格載入的支援。

### [!DNL Experience Manager as a Cloud Service] Foundation

_新功能_

* [快速開發環境](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/rapid-development-environments.html?lang=en) - RDE可讓開發人員快速疑難排解問題，並在 [!DNL Experience Manager] as a [!DNL Cloud Service].

   快速開發環境是新類型的雲端環境，旨在以快速、一致且可擴充的方式驗證本機運作的程式碼，且可在雲端中正常運作。 使用命令列工具，將內容套件、套件組合、內容檔案、OSGI設定或Dispatcher設定快速「同步」至RDE。

   成功驗證RDE中的程式碼後，建議您將其部署至雲端開發環境。 在環境中，您可以先行使Cloud Manager品質閘門，再透過生產管道部署至預備和生產環境。

   每個程式都包括一個RDE，並可選擇地許可更多。

   >[!NOTE]
   >
   >計畫在未來幾週逐步推出RDE。 您可以傳送電子郵件至 [aemcs-rde-support@adobe.com](mailto:aemcs-rde-support@adobe.com) 跳到前線。

* [延伸支援伺服器端API存取權杖](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/generating-access-tokens-for-server-side-apis.html?lang=zh-Hant)  — 您現在可以產生多個憑證，這對API具有不同特性的情況非常有用。 現在也可以以自助方式撤銷證書。

### [!DNL Cloud Manager]

_新功能_

* 使用者可下載 [自訂UI測試](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/test-results/ui-testing.html?lang=en) 結果。
* [快速開發環境](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/developing/rapid-development-environments.html?lang=en) (RDE)是新類型的雲端環境，旨在以快速、一致且可擴充的方式驗證本機運作的程式碼在雲端中也能如預期般運作。
   * RDE可讓開發人員快速疑難排解問題，並在 [!DNL Experience Manager] as a [!DNL Cloud Service].
   * 開發人員可使用命令列工具，快速將內容套件、套件組合、內容檔案、OSGi設定或Dispatcher設定同步至RDE。

_API變更_

* 已變更API以支援 [RDE](https://developer.adobe.com/experience-cloud/cloud-manager/reference/api/#tag/Rapid-Development-Environments).
* API現在允許擷取 [執行成品](https://developer.adobe.com/experience-cloud/cloud-manager/reference/api/#tag/Execution-Artifacts).

### Experience Manager 版本資訊

全部 [!DNL Experience Manager] 發行資訊位於：

* [Experience Manager as a Cloud Service 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hant)
* [Experience Manager as a Cloud Service 版本更新](https://experienceleague.adobe.com/docs/experience-manager-release-overview-events/aemcsupdates/overview.html?lang=zh-Hant)
* [Adobe Experience Manager as a Cloud Service 最新版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/release-notes/release-notes-current.html?lang=zh-Hant)
* [Experience Manager as a Cloud Service 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=zh-Hant)
* [Experience Manager Cloud Manager 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=zh-Hant)
* [Automated Forms Conversion Service 版本注意事項](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=zh-Hant)
* [Experience Manager 6.5 Service Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=zh-Hant)
* [Experience Manager 6.4 Cumulative Fix Pack 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=zh-Hant)
* [Experience Manager Assets Dynamic Media 版本注意事項](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=zh-Hant)
* [Experience Manager Brand Portal 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=zh-Hant)
* [Experience Manager 桌面應用程式版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=zh-Hant)
* [Experience Manager Dispatcher 版本注意事項](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=zh-Hant)
* [Adobe Primetime 版本注意事項](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html)
* [Livefyre 發行說明](https://experienceleague.adobe.com/docs/discontinued/using/livefyre.html)

### 最新 Experience Manager 課程與教學課程 {#tutorials-aem}

過去一個月內發佈的新影片、教學課程和其他課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- | ------|
| 2023 年 3 月 | [快速開發環境](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/developing/rde/overview.html) | 影片 | 了解快速開發環境(RDE)、如何設定和使用RDE，並了解使用RDE的開發生命週期。 | AEM CS |
| 2023 年 3 月 | [Asset Share Commons Asset Kit](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/sharing/assets-share/asset-share-commons-asset-kits.html) | 影片 | 了解如何使用Asset Share Common的資產套件功能，產生自訂、可共用的網頁，以列出AEM Assets資料夾或集合中的資產。 | AEM Assets |

{style="table-layout:auto"}

### [!DNL Experience Manager] 支援知識庫

[!DNL Adobe Experience Manager] 的新文章和現有文章的更新。

| 已發佈 | 名稱 | 類型 | 說明 |
|---------|--------|---------|---------|
| 2023 年 2 月 | [如何允許非管理員使用者存取Web主控台？](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21527.html?lang=zh-Hant) | 新文章 | 了解如何允許非管理員使用者存取Web主控台（OSGi主控台）。 |
| 2023 年 2 月 | [如何使用cURL下載資產？](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21528.html?lang=zh-Hant) | 新文章 | 了解如何使用cURL下載資產。 |
| 2023 年 2 月 | [錯誤：BUILD_MAVEN_PACKAGE_ERROR，在 [!DNL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21577.html?lang=zh-Hant) | 新文章 | 了解如何解決錯誤 —  `Build_Maven_Package_Error` in [!DNL Cloud Manager]. |
| 2023 年 2 月 | [管道部署在建置步驟期間失敗](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21419.html?lang=zh-Hant) | 新文章 | 找出解決方案，解決由於 `ui.frontend` 程式碼。 |
| 2023 年 2 月 | [不支援封裝式權杖的權杖重新整理](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21491.html?lang=zh-Hant) | 新文章 | 了解封裝Token不支援重新整理Token的問題。 |

{style="table-layout:auto"}

### 適用於 Experience Manager 的其他說明資源

* [Experience Manager as a Cloud Service 指南](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=zh-Hant)
* [Cloud Manager 使用手冊](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=zh-Hant)
* [Experience Manager 6.5 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=zh-Hant)
* [Experience Manager 6.4 學習與支援首頁](https://experienceleague.adobe.com/docs/experience-manager-64.html)
* [舊版 Experience Manager 文件](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=zh-Hant#previous-updates)
* [Dynamic Media Classic 說明首頁](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=zh-Hant)
* [Experience Manager 文件：最近更新](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=zh-Hant#aem-as-a-cloud-service)

+++

<!-- ## ![Icon](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] is an application deployed onto AEM. It is a powerful, enterprise-grade component content management solution (CCMS) which enables native DITA support in Adobe Experience Manager, empowering AEM to handle DITA-based content creation and delivery.

Learn more about [[!DNL Experience Manager Guides]](https://business.adobe.com/products/experience-manager/guides/features.html).

### Additional resources

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=en) - tutorials on Experience League
* [[!DNL Experience Manager Guides] Learn & Support](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html) - product documentation -->

## ![圖示](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

存取發行說明、最新教學課程和知識庫文章，適用於 [!DNL Adobe Commerce] Experience League。

+++詳細資訊

* 請參閱[Adobe Commerce 和 Magento Open Source 版本注意事項](https://experienceleague.adobe.com/docs/commerce-operations/release/notes/overview.html)以取得最新資訊。

>[!NOTE]
>
>[!DNL Adobe Search&Promote] 服務終止時間為 **2022 年 9 月 1 日**。 對於產品和商業搜尋，[Live Search ](https://experienceleague.adobe.com/docs/commerce-merchant-services/live-search/overview.html?lang=zh-Hant)是 Adobe 的搜尋應用程式。如需了解詳細資訊，請參閱[產品壽命結束公告](https://experienceleague.adobe.com/docs/discontinued/using/search-promote.html?lang=zh-Hant)。

### 適用於 [!DNL Adobe Commerce] 的新教學課程與文件 {#tutorials-commerce}

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2023 年 3 月 | [設定Adobe Commerce](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/adobe-developer-app-builder/io-events/configure-commerce.html) | 影片 | 了解如何設定Adobe Commerce以公開事件。 |
| 2023 年 3 月 | [開始使用API Mesh](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/adobe-developer-app-builder/api-mesh/getting-started-api-mesh.html?lang=en) | 影片 | 了解如何在 Adobe Commerce 和 Adobe App Builder 上使用 API Mesh。了解如何安裝Adobe應用程式產生器、處理專案、建立圖形反向Proxy等。 |
| 2023 年 3 月 | [適用於Adobe Commerce的I/O事件](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/adobe-developer-app-builder/io-events/2-4-5-installation.html?lang=en) | 影片 (多個) | 了解如何使用2.4.5版、2.4.6版等版本的撰寫器，在Adobe Commerce中安裝數個新模組。 這會設定要在Adobe Commerce應用程式中使用的必要模組。 |

{style="table-layout:auto"}

### [!DNL Commerce] 支援知識庫

Adobe Commerce 的新文章和現有文章的更新。

| 已發佈 | 名稱 | 類型 | 說明 |
|---------|--------|---------|---------|
| 2023 年 2 月 | [品質修補工具 (QPT)](https://experienceleague.adobe.com/docs/commerce-knowledge-base/kb/support-tools/patches/patches-available-in-qpt-tool-overview.html) | 新文章 | 關於如何套用 QPT 1.1.26 和 QPT 1.1.27 中可用的修補程式的新文章已發佈，並且可以在其各自區段中找到。 |

{style="table-layout:auto"}

+++

## ![圖示](/assets/target.png) [!DNL Target] {#target}

存取搶鮮版說明、最新發行說明和Adobe Target的全新教學課程。

+++詳細資訊

* 如需搶鮮版資訊，請參閱 [[!DNL Adobe Target]  搶鮮版](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=zh-Hant)
* 如需目前版本資訊，請參閱 [[!DNL Adobe Target]  發行說明](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=zh-Hant)

+++

## ![圖示](/assets/campaign.png) [!DNL Campaign] {#ac}

取得 [!DNL Adobe Campaign]. 尋找有關Experience League的最新教學課程、課程和知識庫支援文章。

+++詳細資訊

### 最新 Campaign 產品版本

請前往這裡，了解中的最新功能、改善項目和修正項目 [!DNL Adobe Campaign]:

在 [Campaign v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html)、[Campaign v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/releases/release-notes.html?lang=zh-Hant) 和 [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) 版本注意事項中進一步了解最新功能、改進與修正。

### 新 [!DNL Campaign] 教學課程和其他課程 {#tutorials-campaign}

針對 Adobe Campaign 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2023 年 2 月 | _Adobe Campaign 成功行銷的十大最佳實務_ | 文章 | 了解十大最佳實務，協助 Adobe Campaign 從業人員充分發揮並加速消費者數位轉型，並向客戶提供更佳體驗。 | 請參閱： <ul><li>[Campaign v8](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/strategy/10-best-practices-for-marketers.html)<li>[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/strategy/10-best-practices-for-marketers.html)</li><li>[Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/strategy/10-best-practices-for-marketers.html?lang=en) |

{style="table-layout:auto"}

### [!DNL Campaign] 支援知識庫

[!DNL Adobe Campaign] 的新文章和現有文章的更新。

| 已發佈 | 名稱 | 類型 | 說明 |
|---------|----|----|-----------|
| 2023 年 2 月 | [是否支援TLS 1.3?](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21516.html?lang=zh-Hant) | 新文章 | 了解TLS 1.3的支援狀態。 |
| 2023 年 2 月 | [未顯示設定檔和服務的 API 更新](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21517.html?lang=zh-Hant) | 新文章 | 了解在最新版ACS中將自訂資源變更發佈至長文字屬性時，API未更新的問題。 |

{style="table-layout:auto"}

### [!DNL Campaign] 說明資源

* [!DNL Campaign] v8：[文件](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html) - [發行說明](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [實作指南](https://experienceleague.adobe.com/docs/campaign/campaign-v8/config/implement/implement.html)
* [!DNL Campaign] Standard：[Campaign Standard 文件](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html) - [發行規劃](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html)
* [!DNL Campaign] Classic：[Campaign Classic v7 文件](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [操作說明影片](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html) - [最新文件更新](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html)
* [!DNL Campaign]控制面板：[文件](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html) - [發行說明](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=zh-Hant) - [操作方法影片](https://experienceleague.adobe.com/docs/control-panel-learn/tutorials/control-panel-overview.html?lang=zh-Hant) 的操作方法影片

+++

## ![圖示](/assets/experience_platform_appicon_24.png) [!DNL Journey Optimizer] {#journey-opt}

了解 [!DNL Journey Optimizer]. 檢視有關Experience League的最新教學課程和知識庫支援文章。

+++詳細資訊

### 最新 [!DNL Journey Optimizer] 產品版本

進一步了解 [Journey Optimizer 版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)中最新功能、改進功能和修正。

### 新 [!DNL Journey Optimizer] 教學課程和其他課程 {#tutorials-ajo}

針對 Adobe [!DNL Journey Optimizer] 發佈的新影片、教學課程或課程。

| 已發佈 | 名稱 | 類型 | 說明 |
| -----------| ---------- | ---------- | ---------- |
| 2023 年 3 月 | [設定訓練沙箱](https://experienceleague.adobe.com/docs/journey-optimizer-learn/configure-a-training-sandbox/introduction-and-prerequisites.html?lang=en) | 教學課程 | 了解如何設定沙箱以供訓練之用。 逐一完成設定結構、擷取範例資料和建立事件所需的步驟。 |
| 2023 年 3 月 | [Journey Optimizer挑戰](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/introduction-and-prerequisites.html?lang=en) | 挑戰 | 挑戰提供了實施您所學知識所需的情境和要求。 每個挑戰都解決您所實作的不重複使用案例。 <p>新挑戰：<ul><li>[建立夏季系列發佈](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/summer-collection-announcement-challenge.html?lang=en)</li><li>[  建立訂單確認](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/order-confirmation-challenge.html?lang=en)  </li><li>[建立產品補充通知](https://experienceleague.adobe.com/docs/journey-optimizer-learn/challenges/product-replenishment-challenge.html?lang=en)</li></ul> |

{style="table-layout:auto"}

### [!DNL Journey Optimizer] 支援知識庫

[!DNL Adobe Journey Optimizer] 的新文章和現有文章的更新。

| 已發佈 | 名稱 | 類型 | 說明 |
|---------|-------|--------|---------|
| 2023 年 2 月 | [登錄頁面上沒有選擇加入](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21416.html?lang=zh-Hant) | 新文章 | 了解登錄頁面上未選擇加入的問題的解決方案。 |
| 2023 年 2 月 | [缺少資料流通知](https://experienceleague.adobe.com/docs/experience-cloud-kcs/kbarticles/KA-21415.html?lang=zh-Hant) | 新文章 | 了解您未收到資料流通知的問題解決方案。 |

{style="table-layout:auto"}

### [!DNL Journey Optimizer] 的更多資源

* [Journey Optimizer 文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html)
* [決策管理文件](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioning/get-started-decision/starting-offer-decisioning.html) - [版本注意事項](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [操作說明影片](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html) - [最新文件更新](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

+++

## ![圖示](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

存取最新發行說明，以Journey OrchestrationExperience League。

+++詳細資訊

### 最新 [!DNL Journey Orchestration] 產品版本

進一步了解 [[!DNL Journey Orchestration]  版本注意事項](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html)中最新功能、改進功能和修正。

#### [!DNL Journey Orchestration] 的更多資源

* [Journey Orchestration檔案](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html)

* [發行說明](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html)

* [作法影片](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

* [最新文件更新](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html)

+++

## ![圖示](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

了解的最新發行說明和發行排程 [!DNL Marketo Engage].

+++詳細資訊

### Marketo Engage 核心更新

* 請參閱 [2023年3月 — 最新發行說明](https://experienceleague.adobe.com/docs/marketo/using/release-notes/current.html?lang=zh-Hant) 以了解最新資訊
* 如需最新發行排程資訊和版本注意事項，請參閱[!DNL Marketo Engage] [發行排程](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=zh-Hant)。

<!-- ### New Marketo tutorials and courses {#tutorials-marketo}

New videos, tutorials, or courses published for Adobe Marketo.

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|August 2022 |[Marketo Engage tutorials](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en)|Videos |Visit the [Marketo Engage tutorial home](https://experienceleague.adobe.com/docs/marketo-learn/tutorials/overview.html?lang=en) on Experience League for all past and new tutorials for Marketo Engage.|

{style="table-layout:auto"} -->

如需最新的產品文件，請參閱 [Marketo 產品文件](https://experienceleague.adobe.com/docs/marketo/using/home.html?lang=zh-Hant)首頁

+++

## ![圖示](/assets/workfront.png) [!DNL Workfront] {#workfront}

了解 [!DNL Adobe Workfront]. 尋找有關Experience League的全新教學課程。

+++詳細資訊

<!-- ### New Adobe [!DNL Workfront] courses and tutorials {#tutorials-workfront}

New [!DNL Workfront] course and collections of tutorials on Experience League.

**Note:** Translation on Experience League for all [[!DNL Workfront]](https://experienceleague.adobe.com/docs/workfront.html?lang=en) tutorials and product documentation is coming soon!

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|February 2023|[Take charge of an existing Adobe Workfront instance](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/system-perfomance-and-maintenance/take-charge-of-an-existing-workfront-instance.html?lang=en)|Video |Learn the key phases to evaluate, understand, and optimize your instance of [!DNL Workfront] as a new system or group administrator.|
|February 2023|[Customize project headers with layout templates](https://experienceleague.adobe.com/docs/workfront-learn/tutorials-workfront/administration-and-setup/layout-templates/customize-project-headers-with-layout-templates.html)|Video |Learn how to add and remove fields from project headers through layout templates.|

{style="table-layout:auto"} -->

請參閱[[!DNL Workfront] 產品版本](https://experienceleague.adobe.com/docs/workfront/using/product-announcements/product-releases/product-releases.html)頁面，以取得所有產品的最新資訊匯總。

+++

## ![圖示](/assets/advertising-cloud.png) Adobe Advertising {#advertising}

[!DNL Adobe Advertising] 版本注意事項。

+++詳細資訊

<!-- * [New features across [!DNL Advertising]](#advertising-all) -->
* [ [!DNL Advertising DSP] 中的新功能](#advertising-dsp)
* [ [!DNL Advertising Search] 中的新功能](#advertising-search)
<!-- * [New [!DNL Advertising] tutorials](#tutorials-advertising) -->

<!--
### New features across [!DNL Advertising] {#advertising-all}

Last updated: **August 9, 2022**

| Feature | Description |
| ------- | ----------- |
| Integration with [!DNL Adobe Analytics] | (August 6 release) Improvements to the data feed that Advertising sends to [!DNL Analytics] result in fewer mismatches between click/cost/impression data from the search engines and related conversion data in [!DNL Analytics]. |

{style="table-layout:auto"}

-->

### [!DNL Advertising DSP] 中的新功能 {#advertising-dsp}

了解Adobe廣告的最新功能。

上次更新： **2023年3月2日**

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 行銷活動] | （2月15日發行版本）您現在可以以圖表形式檢視變更記錄，也可以為任何項目新增附註。 |

{style="table-layout:auto"}

### [!DNL Advertising Search] 中的新功能 {#advertising-search}

上次更新： **2023年3月2日**

| 功能 | 說明 |
| ------- | ----------- |
| [!UICONTROL 行銷活動] | (Google Ads帳戶；開放測試版功能；2月23日發行)的唯讀同步支援 [!DNL Google Ads] discovery行銷活動處於測試模式，所有廣告商皆適用。 Discovery促銷活動 [!UICONTROL 促銷活動類型] &quot;[!UICONTROL 探索],&quot; [!UICONTROL 廣告群組類型] &quot;[!UICONTROL 探索], 」和 [!UICONTROL 創作類型] &quot;[!UICONTROL 發現廣告]&quot;（適用於單一影像廣告）或&quot;[!UICONTROL 探索輪播廣告]&quot;（適用於多影像輪播廣告）。 您可以在標準和混合專案組合中包含探索行銷活動。<br><br>報告中提供探索行銷活動的廣告層級資料。對於具有 Adobe Analytics 整合的廣告商，廣告層級資料在 [!DNL Analytics] 報告中提供。 同樣地，[!DNL Analytics] 資料在 [!DNL Search] 中可用；該資料是使用升級後的 `s_kwcid` 追蹤參數傳送的，無論您通常為帳戶使用的 `s_kwcid` 格式為何。如果您通常使用舊版本的 `s_kwcid`，那麼您的點擊次數/成本資料和收入資料會使用不同的 `s_kwcids` 進行追蹤，但兩組資料會完全分類並彙總在相同的行銷活動和帳戶下。 |
|  | ([!DNL Google Ads] 賬戶；2月11日發行)支援「[!UICONTROL 目標曝光共用]「競標策略現在僅適用於搜尋網路上的促銷活動。 對於這個競標策略， [!DNL Google Ads] （否） [!DNL Search])會最佳化出價，以達到目標曝光比重和廣告位置。 您可以選擇輸入 [!UICONTROL 目標曝光共用] 作為百分比， [!UICONTROL 目標廣告位置]和 [!UICONTROL 最大CPC] （每次點按成本）。 混合產品組合尚未支援此選項。 |
| [!UICONTROL Bulksheets] | ([!DNL Microsoft] 行銷活動；2月11日發行)大量表單現在包含「[!UICONTROL 行動要求]&quot;和&quot;[!UICONTROL 動作語言呼叫]「多媒體廣告欄（回應式廣告格式），其使用「[!UICONTROL 創意（RSA除外）]」行。 |
| Google Manager帳戶 | （2月23日發行）新 [!UICONTROL 管理] > [!UICONTROL 管理員帳戶] 功能可讓您為 [!DNL Google Ads] 管理帳戶 [!DNL Search] 會上傳跨帳戶轉換。 如果您想要上傳，請使用此功能 [!DNL Adobe] — 追蹤的跨帳戶轉換量度， [!DNL Google Ads] 管理員帳戶或b)上傳包含跨帳戶轉換的產品組合目標至 [!DNL Google Ads] 混合優化。<br><br>添加管理員帳戶的憑據後，可選的[!UICONTROL 跨帳戶轉換的經理帳戶]」欄 [!UICONTROL 行銷活動] > [!UICONTROL 帳戶] 「視圖」指示每個子帳戶的manager帳戶ID，當manager帳戶未驗證時，該列顯示錯誤。 |

{style="table-layout:auto"}

+++

## ![圖示](/assets/document-cloud-24.png) [!DNL Document Cloud] {#doc-cloud}

專為 [!DNL Document Cloud] 發佈的新教學課程和課程，包括 [!DNL Document Services] 和 [!DNL Acrobat Sign]。

+++詳細資訊

| 已發佈 | 名稱 | 類型 | 說明 | 應用程式 |
| -----------| ---------- | ---------- | ---------- |---------- |
| 2023 年 3 月 | [送證](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/notarize/send-document-notarize.html?lang=en) | 影片 | 了解如何傳送公證檔案、檢視簽署者的體驗，以及接收結果。 | Acrobat Sign |

{style="table-layout:auto"}

如需 [!DNL Document Cloud] 說明，請參閱：

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud 學習與支援](https://helpx.adobe.com/tw/support/document-cloud.html)

+++

<!-- ## ![Icon](/assets/creative-cloud-24.png) [!DNL Creative Cloud] for enterprise {#creative-cloud}

New videos, tutorials, or courses published for [!DNL Creative Cloud] for enterprise.

+++Details

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|January 2023|[Professional motion graphics templates](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/videooverview/videotutorials/motion-graphics-templates.html?lang=en)|PDF tutorial|Using the Essential Graphics workflow in Adobe After Effects and Adobe Premiere Pro, editors can import MOGRTs and set properties. Properties include text, fonts, color, size, speed, or layout editable, while maintaining the sequence's consistent look and design.|
|January 2023|[Collaboration: The Future of Creativity](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/collaboration-the-future-of-creativity.html?lang=en)|PDF tutorial |Get free access to more than 20,000 professionally designed and curated fonts from Adobe Fonts. Originally known as Typekit, Adobe Fonts are available through a single licensing agreement that gives designers unlimited creative use for personal or commercial projects.|
|January 2023|[3D design and rendering](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/3doverview/3dtutorials/substance-3d-stager.html?lang=en)|PDF tutorial |Import content, arrange your scene, apply materials and textures, adjust image-based and physical lighting, save cameras with different resolutions, and render photorealistic imagery - all in Adobe Substance 3D Stager.|
|January 2023|[Adobe Express: Content that stands out](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/cceoverview/ccetutorials/adobe-express-content-that-stands-out.html?lang=en)|PDF tutorial |Create beautiful graphics, web pages, and video stories in minutes with Adobe Express (formerly known as Adobe Spark). Working from thousands of professionally designed templates, make social posts and stories, flyers, logos, booklets, posters, and more. Start for free, and make content that always stands out.|

{style="table-layout:auto"} 

See [Creative Cloud for enterprise tutorials](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) for the latest tutorials.

+++
-->

<!-- ## ![Icon](/assets/experience-league.png) Customer Data Management - Voices {#voices}

[Customer Data Management Voices](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) is your destination as a customer data management technical and marketing practice leader and specialist. This collection of tutorials is your one-stop-shop to hear from your peers, get inspired, and learn about developments in MarTech. No registration required, simply click and watch.

## ![Icon](/assets/experience-league.png) Digital Experience Blueprints {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=en) are repeatable implementations that let you address strategy and quickly solve established business problems. Each Blueprint provides a series of artifacts that explain the high-value business problem, architectures, implementation steps, technical considerations, and links to the relevant documentation.

### New Digital Experience Blueprints tutorials

|Published|Name|Type|Description |
| -----------| ---------- | ---------- | ---------- |
|January 2023|[Customer Journeys - AEP + Apps & AJO Architecture](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=en)|Diagram updates|Deliver individual, just-in-time customer experiences across screens.| 
-->

