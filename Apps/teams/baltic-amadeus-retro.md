---
title: バルト海のアマデウスによるレトロのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/03/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: レトロで利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 0aa4d73311b10112ef62b2caf5219d1346eafeaa
ms.sourcegitcommit: 50bd8e07d9355ae65935767a34aca39c46ade8f4
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/06/2021
ms.locfileid: "52250835"
---
# <a name="retro"></a>Retro

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 11 月 3 日</p>

* <a href="https://teams.microsoft.com/l/app/434e1a1a-2ed7-4e45-9588-04f5099fd876" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001892" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

バルト海アマデウスから Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Retro |
| ID | WA200001892 |
| 機能 | ボット、タブ |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Baltic Amadeus |
| パートナー Web サイトの URL | [https://www.ba.lt/en/](https://www.ba.lt/en/) |
| プライバシー ポリシーの URL | [https://retro.ba.lt/privacypolicy](https://retro.ba.lt/privacypolicy) |
| 利用規約の URL | [https://retro.ba.lt/termsandconditions](https://retro.ba.lt/termsandconditions) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関するバルト・アマデウスによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| レトロ アプリには、Microsoft サービスとは見なされない独自の Web API があります。 前述したように、識別と適切なコンテンツ表示の目的で Email と Fullname が格納されます。 このデータは他の場所には送信されません。 さらに、Retro には、スプリント データを Atlassian の合流空間にエクスポートするオプションの機能があります。 これを行うには、ユーザーはユーザー名とパスワードを入力する必要があります。 このデータは、ユーザーに代わって api を confluence するために認証された要求を行う場合にのみ使用され、どこにも保存もログにも記録されません。 |  | Retro には、Azure にも登録されている独自の Web API があります。 それを使用するには、Microsoft Identity Platform 経由でユーザーを認証する必要があります。 ユーザーを認証する必要があります。そのため、Retro アプリはユーザー固有のコンテンツをサーバーに接続できます。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:--------------------------------|:---------------------|:--------------------------|
>| ボットは、どのメンバーがチームに参加したのか、チームから去ったのか確認するために、名簿にアクセスします。 その結果、プロジェクトからそのユーザーが追加または非アクティブ化され、ユーザーがスプリント参加者リストに表示されなくなりました。 | メールと FullName は一緒にリンクされ、データベースに格納されます。 ログインしているユーザーに適したコンテンツを表示するために、電子メールはユーザー識別に使用されます。 FullName は puproses の表示に使用されます。そのため、他のユーザーは、フィードバックを評価または書き込むユーザーを知る必要があります。  |  |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>いいえ。 Retro アプリでテレメトリ/ログを生成する唯一のプロセスは、エラー ログです。 エラー ログに EUII または OII が含まれる

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データは Azure sql server データベースに格納されます。 これは、レトロアプリとレトロボットを介して保存されます。
既定では、Azure sql データベースには透過的なデータ暗号化が有効になっています。
データベースは基本認証の背後にロックされています。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36148" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

