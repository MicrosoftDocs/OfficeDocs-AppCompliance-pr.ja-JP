---
title: バルト海アマデウスによるレトロのためのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Retro、データ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、およびCSA STARレジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 49b17e202fb358284b9a36ed33646926d649afe3
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553458"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年11月3日</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

バルト海のアマデウスがマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Retro |
| ID | WA200001892 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | Baltic Amadeus |
| パートナーウェブサイトのURL | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| プライバシーポリシーの URL | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| 利用規約の URL | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが収集し、組織のデータを格納する方法と、アプリが収集するデータに対する組織のコントロールについてバルト海のアマデウスによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションは、マイクロソフトのGraphを使用していません。


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>| **すべての非Microsoft サービス OII は、** |  **どのようなOIIが転送されますか?** | **OIIを転送するための正当性?** |
>|:-------------------|:--------------------------|:--------------------------|
>| レトロアプリには、マイクロソフトのサービスとは見なされない独自のWeb APIがあります。 前述のように、識別と適切なコンテンツ表示のために電子メールとフルネームを保存します。 このデータは他の場所には送信されません。 さらに、Retro には、スプリント データをアトラシアン合流空間にエクスポートするオプション機能があります。 そのためには、ユーザーは合流ユーザー名とパスワードを入力する必要があります。 このデータは、ユーザーに代わってコンフルエンス API に対して認証された要求を行うためだけに使用され、どこにも保存または記録されません。 |  | Retro には、Azure にも登録されている独自の Web API があります。 これを使用するには、ユーザーが Microsoft ID プラットフォームを介して認証される必要があります。 ユーザーは認証を受ける必要があるため、Retro アプリはユーザー固有のコンテンツをサーバーに提供できます。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>| **EUIIにアクセスするための正当性?**  | **EUII はデータベースに格納されていますか?** | **EUIIを保存するための正当性?** |
>|:--------------------------------|:---------------------|:--------------------------|
>| ボットは、チームに参加または退社したメンバーを確認するために、名簿にアクセスします。 それに基づいて、ユーザーがスプリント参加者リストに表示されないように、プロジェクトに対してそのユーザーを追加または非アクティブ化します。 | 電子メールとフルネームは、一緒にリンクされ、データベースに格納されます。 電子メールは、ログインしているユーザーに適切なコンテンツを表示するために、ユーザーの識別に使用されます。 FullName は、子犬を表示するために使用されるため、他のユーザーは、フィードバックを評価または書いているユーザーを知ることができます。  |  |


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>いいえ。 Retro アプリでテレメトリ/ログを生成するプロセスは、エラー ログだけです。 エラー ログに EUII または OII が含まれなかった

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>データは、Azure SQL サーバー データベースに格納されます。 レトロアプリとレトロボットを介して保存されます。
既定では、azure sql データベースでは透過的なデータ暗号化が有効になっています。
データベースは基本認証の背後にロックされています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

