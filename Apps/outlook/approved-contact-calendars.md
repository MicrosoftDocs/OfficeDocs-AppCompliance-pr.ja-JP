---
title: 承認済み連絡先別の承認済み連絡先カレンダーの申請情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: 承認済み連絡先カレンダーの利用可能なセキュリティ情報およびコンプライアンス情報、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 57dd499fe648ed9a9b481d4175056977a0d6fa61
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52552558"
---
# <a name="approved-contact-calendars"></a>承認済みの連絡先カレンダー

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380294" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトへの承認された連絡先によって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | 承認済みの連絡先カレンダー |
| ID | WA104380294 |
| サポートされるクライアントOffice 365 | 2013 年以降Outlook、Windows、Outlook 2016 以降、Mac 上で、ウェブ上でOutlook |
| パートナー会社名 | 承認済みの連絡先 |
| パートナーウェブサイトのURL | [https://approvedcontact.com/](https://approvedcontact.com/) |
| プライバシーポリシーの URL | [https://approvedcontact.com/Privacy%20Policy.pdf](https://approvedcontact.com/Privacy%20Policy.pdf) |
| 利用規約の URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;オンクト=エン・US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織の制御について、承認済み連絡先によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 委任 | カレンダーBOTのために我々は複数の人のための空き時間を見つけるためにユーザーの空き時間を保存しています。  | 空き時間とスケジュールの会議を読み、比較します。 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| Contacts.Read | 委任 | はい、連絡先情報を保存します。 | 連絡先のインポートと同期 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.Read | 委任 | はい | 基本プロファイル情報。 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| User.ReadBasic.All | 委任 | いいえ | 同僚のプロファイルの表示、自由時間の比較、会議室のスケジューリングに使用されます。 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| offline_access | 委任 | はい、オフライン ユーザーの空き時間情報です。 | ユーザーが当社のサイトを積極的に使用していない場合は、Graphを呼び出します。 | adef9811-448f-4dd5-88d9-68734050fe58 |
>| openid | 委任 | いいえ | Office 365SSO. | adef9811-448f-4dd5-88d9-68734050fe58 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>はい、ライセンス購入を商用Appsourceに接続するためのメールアドレスを記録します。 ログからこの情報を削除する機能を提供します。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>開発者だけがログにアクセスできます。 すべての開発プラットフォームへのアクセスに対して 2FA を適用します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/20445" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

