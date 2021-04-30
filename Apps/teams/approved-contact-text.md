---
title: 承認済み連絡先によるテキストのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
description: テキスト、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 234dd55134c0d3d54c4911f4ba82340475ef969c
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095578"
---
# <a name="text"></a>テキスト

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://teams.microsoft.com/l/app/a622ceb4-b6e2-4557-8218-e22e80975ba4" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000383" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Microsoft への承認済み連絡先によって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | テキスト |
| ID | WA200000383 |
| 機能 | ボット、タブ |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | 承認済みの連絡先 |
| パートナー Web サイトの URL | [https://sales.approvedcontact.com/syniverse-microsoft-teams...](https://sales.approvedcontact.com/syniverse-microsoft-teams-text/) |
| プライバシー ポリシーの URL | [https://sales.approvedcontact.com/wp-content/uploads/text-p...](https://sales.approvedcontact.com/wp-content/uploads/text-privacy-policy.pdf) |
| 利用規約の URL | [https://sales.approvedcontact.com/wp-content/uploads/text-t...](https://sales.approvedcontact.com/wp-content/uploads/text-terms-of-use.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する承認済み連絡先によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 委任 | Text BOT では、受信テキスト メッセージの将来のチャネルを作成するためのチーム識別子をキャプチャします。 | ユーザー向けチャネルTeams作成できます。 | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| メール | 委任 |  | ユーザーの連絡先情報の取得。 | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| offline_access | 委任 | 更新トークンはデータベースに格納されます。 | 更新トークンが存在しない場合にユーザーの予定表を同期するためにデータベースに更新トークンを保持するために使用されます。 | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| openid | 委任 |  | ユーザーがログインできます。 | a622ceb4-b6e2-4557-8218-e22e80975ba4 |
>| profile | 委任 |  |  | a622ceb4-b6e2-4557-8218-e22e80975ba4 |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| この名簿を使用して、チーム内のすべてのユーザーの空き時間を比較して、開いている時間に会議をスケジュールします。 | メール アドレスを保存して、空き時間を比較できます。 |  |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>はい、ライセンス購入を商用 Appsource に接続するための電子メール アドレスをログに記録します。 ログからこの情報を削除する機能を提供します。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>開発者だけがログにアクセスできます。 すべての開発プラットフォームへのアクセスに 2FA を適用します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35752' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35752" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

