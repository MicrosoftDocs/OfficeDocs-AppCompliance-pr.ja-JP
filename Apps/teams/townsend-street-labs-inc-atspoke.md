---
title: タウンゼント・ストリート・ラボ株式会社によるatSpokeのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 06/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: atSpoke、データ処理ポリシー、Microsoft Cloud App Securityアプリカタログ情報、CSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
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
<p>開発者による最終更新日: 2020年6月3日</p>

* <a href="https://teams.microsoft.com/l/app/dfaf15dc-4e94-4484-a25d-79358fe70d8b" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001454" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

タウンゼント・ストリート・ラボ社がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | atSpoke |
| ID | WA200001454 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Townsend Street Labs, Inc. |
| パートナーウェブサイトのURL | [https://www.atspoke.com](https://www.atspoke.com) |
| プライバシーポリシーの URL | [https://www.atspoke.com/privacy-policy/](https://www.atspoke.com/privacy-policy/) |
| 利用規約の URL | [https://www.atspoke.com/terms-of-service](https://www.atspoke.com/terms-of-service) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールについて、タウンゼントストリートラボ社によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 委任 | atSpoke はマイクロソフト グループ ID を格納します。 | atSpoke と Microsoft Teams の間でグループ情報を読み書きできます。  | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| User.ReadWrite.All | 委任 | atSpoke は、ユーザーの電子メールとユーザー ID を格納します。 | atSpoke と Microsoft Teamsの間でユーザー情報を読み書きできます。 | dfaf15dc-4e94-4484-a25d-79358fe70d8b |
>| offline_access | 委任 | atSpoke は、このデータを格納していません。 | これはバックグラウンド同期に使用されます。 | dfaf15dc-4e94-4484-a25d-79358fe70d8b |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| はい、運用効率のためにサードパーティのサービスを使用しています。 Google, Inc.: 論理ボリュームに保存されたデータ、ネイティブの Google Cloud ネットワークでのストレージバックアップ、サービスおよび API ログ、またはアプリケーションログ。 ログに記録されたトランザクション イベントには、ユーザー識別子、連絡先情報、および顧客のコンテンツが含まれる場合があります。 MongoDB, Inc. : クラウドベースのデータベースコレクションに保存されているデータ。 - ユーザーが提出したリクエスト、ユーザーが追加したリクエストへの応答、ユーザーが追加したナレッジ記事を含む顧客コンテンツ。 - ユーザー識別子(スポークユーザーアカウントを作成するために使用される名前、電子メール、アバター、電話番号)。 株式会社メールガンテクノロジーズ:電子メール通信(名前と電子メール)を送信するためのユーザー識別子と連絡先情報。 Twilio, Inc.: ユーザーの電話番号と顧客コンテンツ: テキスト、メッセージ本文、音声およびビデオメディア、画像、音声などのTwilio&#8217;sサービスの使用によって交換されるコンテンツ。 Mixpanel, Inc.: 転送される個人データには、メッセージコンテンツに含まれる名前、電子メール、IPアドレス、個人データが含まれます。 株式会社クラウドイナリー: エンドユーザーが提出したファイルベースの顧客コンテンツ。 Elasticsearch, Inc. : ログに記録されたアプリケーショントランザクション イベントには、顧客コンテンツから切り捨てられたテキストが含まれている場合があります。 Stitch, Inc.: 連絡先情報、使用上の情報、購読者の承認ユーザーの非従来の識別子、および購読者またはその承認ユーザーがプラットフォームに提出するその他の個人データ。 モード分析社: ユーザーごとの分析を提供するユーザー ID 情報。 DataDog: ログに記録されたアプリケーションのトランザクション イベントには、顧客コンテンツから切り捨てられたテキストが含まれている場合があります。ログの保持期間は 14 日間です。 フルストーリー株式会社:当社のWebユーザーインターフェイスで行われた行動の記録;には、識別のためにスポークのユーザー アカウントが含まれています。 |  | 私たちは、ボットフレームワークREST APIを使用しています。 この API を使用して、askSpoke ボット サービスにメッセージを送受信します。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| これにより、atSpoke はユーザーをMicrosoft Teamsから同期してユーザーを作成し、アクセス許可を定義できます。 | atSpoke は電子メールのみを保存するため、ユーザー Microsoft Teams有効なユーザーとして atSpoke にログインできます。 |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>アプリケーション ログには、ユーザーの姓と名、ユーザーの電子メール アドレス、ユーザーとグループに対する Azure 割り当てオブジェクト ID があります。 ログは、自動的に期限切れになった時点で 14 日間のみ保持されます。 ログアクセスは改ざんから保護され、特定のスタッフのみがログを表示できます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>アプリケーションデータは、マネージ MongoDB インスタンスに格納されます。 マネージド サービス Atlas MongoDB データベースへのアクセスは、承認を必要とする標準化されたユーザー アクセス要求プロセスによってプロビジョニングされます。 定期的なユーザー アクセス レビューは、管理サインオフを使用して実行されます。 機密性の高い顧客データにアクセスできるスタッフの数を制限し、どのマシンからのデータも直接変更することはできません&#8232;このデータベースへのリモートアクセスには多要素認証が必要です。 データベースとすべてのバックアップは、AES-256 ビット暗号化を使用して保管時に暗号化されます。


#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35866" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

