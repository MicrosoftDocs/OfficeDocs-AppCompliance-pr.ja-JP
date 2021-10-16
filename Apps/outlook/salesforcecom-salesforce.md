---
title: Salesforce のアプリケーション情報 :salesforce.com
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Salesforce で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 749e4cf95c8eefb650f6fd0f8ceb59721d7efcc8
ms.sourcegitcommit: 9dab9c9dacb9c6daaa6b0041ccc8a49bafdad331
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/16/2021
ms.locfileid: "60413529"
---
# <a name="salesforce"></a>Salesforce

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2021 年 8 月 24 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379334" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Microsoft に提供される salesforce.com 情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Salesforce |
| ID | WA104379334 |
| Office 365サポートされているクライアント | Outlook 2013 以降の Mac Windows、Outlook 2016以降の場合は、Outlook on the web |
| パートナー会社名 | salesforce.com |
| パートナー Web サイトの URL | [https://www.salesforce.com](https://www.salesforce.com) |
| プライバシー ポリシーの URL | [https://www.salesforce.com/company/privacy/](https://www.salesforce.com/company/privacy/) |
| 利用規約の URL | [https://www.salesforce.com/content/dam/web/en_us/www/docume...](https://www.salesforce.com/content/dam/web/en_us/www/documents/legal/Agreements/software-order-form-supplements/Salesforce_Outlook_TOU_Order_Form_Addendum.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリ salesforce.com 収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールに関する情報を提供しています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:--------|:-----------------------|:----------------------------|:--------------------------------------|:-------------------|:-----------------------------------|
>| JavaScript API for Office | はい | このアドインは、Office.js および EWS の関数を使用して、ユーザーが Salesforce にログインすることを決定した電子メールに関するOutlook添付ファイルをコピーします。 予定表側でも同様の機能を使用して、予定を Salesforce に記録します。 | このアドインは、Office.js および EWS の関数を使用して、ユーザーが Salesforce にログインすることを決定した電子メールに関するOutlook添付ファイルをコピーします。 予定表側でも同様の機能を使用して、予定を Salesforce に記録します。 | アドインは getUserIdentityTokenAsync のような関数を使用して、現在のユーザー id をOutlook取得します。 GetItem (.js と EWS) を使用して、Salesforce レコードに保存する際の AdditionalProperties と現在の電子メール メッセージの内容を設定し、getAttachment (EWS) を使用して Exchange から添付ファイルを取得し、ペアの Salesforce メール、UpdateItem (.js)、GetFolder (.js) に追加して下書きフォルダーを取得します。 下書き.js作成に使用される CreateItem (.js)。 | アドインは getUserIdentityTokenAsync のような関数を使用して、現在のユーザー id をOutlook取得します。 GetItem (.js と EWS) を使用して、Salesforce レコードに保存する際の AdditionalProperties と現在の電子メール メッセージの内容を設定し、getAttachment (EWS) を使用して Exchange から添付ファイルを取得し、ペアの Salesforce メール、UpdateItem (.js)、GetFolder (.js) に追加して下書きフォルダーを取得します。 下書き.js作成に使用される CreateItem (.js)。 |
>| Exchange Web サービス (EWS) | はい | このアドインは、Office.js および EWS の関数を使用して、ユーザーが Salesforce にログインすることを決定した電子メールに関するOutlook添付ファイルをコピーします。 予定表側でも同様の機能を使用して、予定を Salesforce に記録します。 | このアドインは、Office.js および EWS の関数を使用して、ユーザーが Salesforce にログインすることを決定した電子メールに関するOutlook添付ファイルをコピーします。 予定表側でも同様の機能を使用して、予定を Salesforce に記録します。 | アドインは getUserIdentityTokenAsync のような関数を使用して、現在のユーザー id をOutlook取得します。 GetItem (.js と EWS) を使用して、Salesforce レコードに保存する際の AdditionalProperties と現在の電子メール メッセージの内容を設定し、getAttachment (EWS) を使用して Exchange から添付ファイルを取得し、ペアの Salesforce メール、UpdateItem (.js)、GetFolder (.js) に追加して下書きフォルダーを取得します。 下書き.js作成に使用される CreateItem (.js)。 | アドインは getUserIdentityTokenAsync のような関数を使用して、現在のユーザー id をOutlook取得します。 GetItem (.js と EWS) を使用して、Salesforce レコードに保存する際の AdditionalProperties と現在の電子メール メッセージの内容を設定し、getAttachment (EWS) を使用して Exchange から添付ファイルを取得し、ペアの Salesforce メール、UpdateItem (.js)、GetFolder (.js) に追加して下書きフォルダーを取得します。 下書き.js作成に使用される CreateItem (.js)。 |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>不要

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Salesforce ストレージについては、「セキュリティ ガイド」で説明されています。 https://resources.docs.salesforce.com/222/latest/en-us/sfdc/pdf/salesforce_security_impl_guide.pdf

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリ salesforce.com 認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について説明しています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

