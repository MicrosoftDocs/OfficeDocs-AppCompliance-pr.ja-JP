---
title: AtSpoke by Townsend Street Labs, Inc. のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: atSpoke で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 9a159ce3ac976eb1916cd94b3eb1cf002f8e13c1
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52551197"
---
# <a name="atspoke"></a>atSpoke

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 6 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Townsend Street Labs, Inc. から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | atSpoke |
| ID | WA200001454 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Townsend Street Labs, Inc. |
| パートナー Web サイトの URL | [https://www.atspoke.com](https://www.atspoke.com) |
| プライバシー ポリシーの URL | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| 利用規約の URL | [https://www.atspoke.com/terms-of-service](https://www.atspoke.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Townsend Street Labs, Inc. から、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 委任 | atSpoke は Microsoft グループ ID を格納します。 | atSpoke と Microsoft Teams の間でグループ情報の読み取りおよびMicrosoft Teams。  | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| User.ReadWrite.All | 委任 | atSpoke は、ユーザーの電子メールとユーザー ID を格納します。 | atSpoke と Microsoft Teams の間でユーザー情報の読み取りおよびMicrosoft Teams。 | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| offline_access | 委任 | atSpoke はこのためのデータを格納していない。 | これは、バックグラウンド同期に使用されます。 | dfaf15dc-4e94-4484-a25d-79358fe70d8b |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| はい、運用効率を高めるサードパーティのサービスを使用しています。 Google, Inc.: 論理ボリュームに保存されたデータ、ネイティブの Google クラウド ネットワーク内のストレージ バックアップ、サービスログと API ログ、またはアプリケーション ログ。 ログに記録されたトランザクション イベントには、ユーザー識別子、連絡先情報、顧客コンテンツが含まれる場合があります。 MongoDB, Inc.: クラウドベースのデータベース コレクションに格納されているデータ。 - ユーザーがファイルした要求、ユーザーが追加した要求への応答、ユーザーが追加したナレッジ記事を含む顧客コンテンツ。 - ユーザー識別子 (スポーク ユーザー アカウントの作成に使用される名前、電子メール、アバター、電話番号)。 Mailgun Technologies, Inc.: 電子メール通信を送信するユーザー識別子と連絡先情報 (名前と電子メール)。 Twilio, Inc.: ユーザーの電話番号と顧客コンテンツ: Twilio&#8217;s Services を使用して交換されるコンテンツ (テキスト、メッセージ本文、音声およびビデオ メディア、画像、サウンドなど)。 Mixpanel, Inc.: 転送される個人データには、名前、電子メール、IP アドレス、およびメッセージ コンテンツに含まれる個人データが含まれます。 Cloudinary, Inc.: エンドユーザーが提出したファイルベースの顧客コンテンツ。 Elasticsearch, Inc.: ログに記録されたアプリケーショントランザクション イベントには、顧客コンテンツから切り捨てられたテキストが含まれている場合があります。 Stitch, Inc.: 連絡先情報、利用状況情報、購読者の承認済みユーザーの非従来の識別子、およびサブスクライバーまたは認定ユーザーがプラットフォームに提出するその他の個人データ。 Mode Analytics, Inc.: ユーザーごとの分析を提供するユーザー識別子の情報。 DataDog: ログに記録されたアプリケーショントランザクション イベントには、顧客コンテンツから切り捨てられたテキストが含まれる場合があります。ログの保持期間は 14 日です。 Fullstory, Inc.: Web ユーザー インターフェイスで実行されたアクションの記録。識別の目的でスポークのユーザー アカウントが含まれます。 |  | ボット フレームワーク REST API を使用しています。 この API を使用して、askSpoke ボット サービスにメッセージを送受信します。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| atSpoke では、ユーザーをユーザーから同期Microsoft Teams作成し、アクセス許可を定義できます。 | atSpoke は電子メールのみを保存Microsoft Teamsユーザーが有効なユーザーとして atSpoke にログインできます。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーション ログには、ユーザーの名と名、ユーザーの電子メール アドレス、およびユーザーとグループの Azure 割り当てられたオブジェクト ID があります。 ログは自動的に期限切れになる時点で 14 日間だけ保持されます。 ログ アクセスは改ざんから保護され、特定のスタッフだけがログを表示できます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>アプリケーション データは、マネージ MongoDB インスタンスに格納されます。 管理サービス Atlas MongoDB データベースへのアクセスは、承認を必要とする標準化されたユーザー アクセス要求プロセスを通じてプロビジョニングされます。 定期的なユーザー アクセス レビューは、管理サインオフを使用して実行されます。 機密性の高い顧客データにアクセスできるスタッフの数を制限し、コンピューターからのデータを直接変更することはできません。&#8232; このデータベースへのリモート アクセスには多要素認証が必要です。 データベースとすべてのバックアップは、AES-256 ビット暗号化を使用して保存時に暗号化されます。


#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

