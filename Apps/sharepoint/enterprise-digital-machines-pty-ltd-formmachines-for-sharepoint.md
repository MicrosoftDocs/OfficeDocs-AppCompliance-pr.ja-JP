---
title: エンタープライズデジタルマシンPTY LTDによるSharePoint用フォームマシンのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: SharePoint用の FormMachines、データ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 4c423cac4f879ba4f73a9bba5f9004acb4cfa21a
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553548"
---
# <a name="formmachines-for-sharepoint"></a>SharePoint用フォームマシン

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年11月3日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200000357" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

エンタープライズ デジタル マシン PTY Ltd がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | SharePoint用フォームマシン |
| ID | WA200000357 |
| サポートされるクライアントOffice 365 | 2016年以降SharePoint |
| パートナー会社名 | エンタープライズデジタルマシンPTY株式会社 |
| パートナーウェブサイトのURL | [https://www.formmachines.com/](https://www.formmachines.com/) |
| プライバシーポリシーの URL | [https://www.formmachines.com/?dirKey=fm-privacy](https://www.formmachines.com/?dirKey=fm-privacy) |
| 利用規約の URL | [https://www.formmachines.com/?dirKey=fm-terms-of-use](https://www.formmachines.com/?dirKey=fm-terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが収集し、組織のデータを格納する方法と、アプリが収集するデータに対する組織の制御についてENTERPRISE DIGITAL MACHINES PTY LTDによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| User.Read | 委任 | (ログイン、電子メール、Azure GUID、表示名、first_login_date_time) | ユーザーがサインインし、アプリにUPNへのアクセスを与えてサイレントログインを可能にし、各ユーザーを一意に識別することができます | 8c87660f-d36f-41f6-b0ae-025253f380aa |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>. 私たちはエラーを記録するだけです。 エラー ログには、エラーに関連する情報のみがログに記録されます。 特定のエラーをトリガしたクライアントまたは顧客は収集されません。 サポート エンジニアだけがエラー ログにアクセスできます。 エラー ログはオンラインで表示され、ダウンロードおよび表示はされません。 エラー ログは 30 日後に自動的に削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>. データは Azure US ベースのデータ センター に格納されます。 テンプレートや提出物などのクライアントが提供するデータは、 DB で暗号化されます。 ファイルの添付ファイルはプライベート Azure BLOB コンテナーに格納され、ユーザーはアクセスする前に認証する必要があります。 当社の運用資産にアクセスできる管理者は最大 2 人で、トラブルシューティングと展開を行うことができます。 これら 2 つの管理者アカウントは、他のすべてのアカウントとは異なるパーティションに分割されます。 管理者アクセスの数が 2 を超えることはありません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36144" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

