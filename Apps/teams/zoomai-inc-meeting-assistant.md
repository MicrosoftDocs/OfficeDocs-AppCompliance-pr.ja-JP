---
title: Zoom.ai Inc. Zoom.ai 会議アシスタントのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/17/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Zoom.ai 会議アシスタント、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: dda27747fdfde0f863611caef27f71547c971b98
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/06/2021
ms.locfileid: "52251937"
---
# <a name="zoomai-meeting-assistant"></a>Zoom.ai Meeting Assistant

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020 年 3 月 17 日</p>

* <a href="https://teams.microsoft.com/l/app/cac7469b-37cc-44f5-bf08-ff6654d35819" target="_blank">Teams ストアでの表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200000150" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

microsoft に Zoom.ai Inc が提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Zoom.ai Meeting Assistant |
| ID | WA200000150 |
| 機能 | ボット、タブ、コネクタ |
| Office 365 クライアントがサポートされている | Microsoft Teams |
| パートナー会社名 | Zoom.ai Inc |
| パートナー Web サイトの URL | [https://zoom.ai](https://zoom.ai) |
| Teams アプリケーション情報ページの URL | [https://faq.zoom.ai/](https://faq.zoom.ai/) |
| プライバシー ポリシーの URL | [https://zoom.ai/privacy](https://zoom.ai/privacy) |
| 利用規約の URL | [https://zoom.ai/terms-of-use](https://zoom.ai/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Zoom.ai Inc. から、このアプリが組織データを収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールについて提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph を使用したデータ アクセス

このアプリで [必要な Microsoft Graph の](https://docs.microsoft.com/graph/permissions-reference) アクセス許可を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 両方とも | 会議は Azure 上の mongoDB にキャッシュされますが、説明は暗号化されます。 | ユーザーの予定表イベントへのアクセス。 |  |
>| Contacts.ReadWrite | 両方とも | 連絡先の名前と電子メール アドレス。 | ユーザーの連絡先を読み取ります (会議に招待できます)。 |  |
>| Group.Read.All | 両方とも | グループ名とメンバー。 | (オプション) 企業のユーザー グループを読み取ります (グループを使用したスケジュール設定の場合)。 |  |
>| Mail.Read | 両方とも | 連絡先の電子メール/名前、対話の頻度/最新の情報。 | (省略可能) は、ユーザーの最も重要な連絡先が (機械学習を介して) 誰かの下に電子メールのメタデータを読み取る場合に使用されます。 |  |
>| MailboxSettings.ReadWrite | 両方とも | ユーザーのタイム ゾーン。 | ユーザーのタイム ゾーン。 |  |
>| User.Read.All | 両方とも | ユーザーの名前 &amp; の電子メール (連絡先として保存)。 | (オプション) 企業ユーザーの読み取り (同僚とのスケジュール設定用) |  |
>| offline_access | アプリケーション | いいえ | ユーザーが存在せずに、いつでもバック エンドを通じて読み書きする必要があります。 |  |


#### <a name="non-microsoft-services-used"></a>使用されている Microsoft 以外のサービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>Microsoft 以外のサービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| 同僚の名前/メールをインポートして、会議アシスタント ボットが会議をスケジュールできるよう | 名前 &amp; の電子メール。 どちらもデータベースに保存され、クイック ルックアップと部分的な名前の参照用に格納されます (たとえば、 Joe P と会う) |  |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>ユーザーまたは連絡先の電子メール アドレスは、ログ プロバイダーである LogDNA にイベントを記録するために使用されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>すべてのデータは、カナダのケベックシティにある MS Azure クラウド データ センターに格納されます。 複数のフィールドは AES256 で暗号化されます。 データベースへのアクセスは、ユーザー/サービス レベルの資格情報を介してエンジニアと弊社のバック エンド サーバーでのみ利用できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security カタログの情報を以下](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)に示します。

<iframe height='1020' title='Microsoft Cloud App セキュリティ情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35668" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

