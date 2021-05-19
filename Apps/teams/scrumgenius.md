---
title: スクラムジーニアスによるスクラムジーニアスのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: attested
description: ScrumGenius、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: ba3b54f7d99672d657b200bf36725d0c7bf03d83
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553908"
---
# <a name="scrumgenius"></a>ScrumGenius

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2019年12月16日</p>

* <a href="https://teams.microsoft.com/l/app/14510476-fa9d-4dad-add9-aa5975a60a8b" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381097" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

マイクロソフトにスクラムジーニウスによって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | ScrumGenius |
| ID | WA104381097 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | ScrumGenius |
| パートナーウェブサイトのURL | [https://scrumgenius.com/](https://scrumgenius.com/) |
| プライバシーポリシーの URL | [https://scrumgenius.com/privacy/](https://scrumgenius.com/privacy/) |
| 利用規約の URL | [https://scrumgenius.com/tos/](https://scrumgenius.com/tos/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法と、アプリが収集するデータに対する組織のコントロールについて、ScrumGeniusによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.Read | 委任 | ユーザーのカレンダーに設定された休暇の日付。 | ユーザーがスクラム天才と自分の休暇を同期するため。 |  |
>| User.Read | 委任 | ユーザーの名前と電子メール アドレス。 | ユーザーが Microsoft ログインでサインインできるようにする。 |  |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| チームの名簿にアクセスするため、チーム管理者が scrumgenius をインストールすると、チームの残りの名簿を scrumgenius と同期して、プラットフォームに登録して、スタンドアップ レポートを構成し、レポートを取得する必要のあるチームのメンバーを割り当てることができます。 | 名、姓、表示名、電子メール アドレス |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>いいえ。 ログの内部 ID にユーザーを結び付ける。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>はい、アプリケーションデータは転送中および保存時に暗号化されます。 Web アプリのみが DB に直接アクセスできます。 外部からのアクセスは制限されており、IP 範囲を使用してアクセスを保護します。


[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35745' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35745" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

