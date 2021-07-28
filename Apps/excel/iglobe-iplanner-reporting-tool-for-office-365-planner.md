---
title: iGlobe による Office 365プランナーの iPlanner レポート ツールのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 12/16/2019
ms.topic: article
ms.service: attestation
certification_type: certified
description: Office 365 Planner の iPlanner レポート ツールで使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 3591c67721188d8dc70bf4f2cf0e34bdb9ffc506
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/22/2021
ms.locfileid: "53526053"
---
# <a name="iplanner-reporting-tool-for-office-365-planner"></a>iPlanner レポート ツール for Office 365 Planner

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2019 年 12 月 16 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380686" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

iGlobe から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | iPlanner レポート ツール for Office 365 Planner |
| ID | WA104380686 |
| Office 365サポートされているクライアント | Excel 2016 Mac の Windows、Excel on the web、Excel 2016以降の場合 |
| パートナー会社名 | iGlobe |
| パートナー Web サイトの URL | [https://iglobecrm.com/](https://iglobecrm.com/) |
| プライバシー ポリシーの URL | [https://instassl.iglobecrm.com/legal-information](https://instassl.iglobecrm.com/legal-information) |
| 利用規約の URL | [https://mipa.iglobe.dk/EULA](https://mipa.iglobe.dk/EULA) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する iGlobe によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 委任 | アプリケーション データベースにデータは格納されません。 | ユーザーにカレンダー エントリを作成するには、タスク&#8217;にカレンダーを追加します。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.AccessAsUser.All | 委任 | アプリケーション データベースにデータは格納されません。 | ユーザーが同意を持ち、API を使用するアクセス権を持っている場合。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Directory.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | プランナー タスクを取得するには、Outlook To Doフラグを付け、それらを更新します。 新しい Planner タスクを作成するには。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Files.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | 添付ファイルとしてファイルにアクセスし、ファイルをタスクにアップロードする。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.Read.All | 委任 | アプリケーション データベースにデータは格納されません。 | 計画リストを取得し、タスクを更新します。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Group.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | プランナー タスクを取得し、新しいタスクを追加するには、バケットとスイム ラインを更新します。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.Read | 委任 | アプリケーション データベースにデータは格納されません。 | User.Read, to get planner task Outlook To Doフラグ付きメールと更新. 新しい Planner タスクを作成するには | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite | 委任 | アプリケーション データベースにデータは格納されません。 | メールを表示し、メールを送信します。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Mail.ReadWrite.All | 委任 | アプリケーション データベースにデータは格納されません。 | 選択したメールからメールの件名を取得します。 アプリが選択したメールから情報を取得できるようにし、説明フィールドをタスクの説明にコピーし、メールまたはメール自体からタスクに添付ファイルを保存できます。 通知を送信します。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| Tasks.ReadWrite | 委任 | アプリケーション データベースにデータは格納されません。 | User.Read を使用してサインインOutlook To Doを取得し、User.Read を更新するには、プランナー タスクを取得し、Outlook To Doフラグを設定して更新します。 新しい Planner タスクを作成するには。 | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |
>| User.Read | 委任 | アプリケーション データベースにデータは格納されません。 | サインインおよびユーザー プロファイルの読み取り | [](https://docs.microsoft.com/microsoft-365-app-certification/azure/) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>iGlobe は、効果的に運用するためのデータを収集し、製品とサービスで最高のエクスペリエンスを提供します。 ライセンスの場合: 無料アドインの展開、試用版サブスクリプションの作成、サブスクリプションの購入など、組織&#8217;のライセンス アカウントを管理するために収集されたデータ。 以下の情報が収集されます。 
- 財務目的: 会社名と住所
- サブスクライブしたユーザー: ユーザー名とメール

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>すべてのデータは、お客様自身のテナント上に含まれており、 アプリケーション データは保存されません。 最新のアドインはサンドボックス ブラウザーで実行され、&#8220;プロセスが&#8221;。 ユーザー データと対話するには、ユーザー データを使用Microsoft サービス。 アドインは、ユーザーが作業しているデータにのみアクセスできます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>なし

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35699" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

