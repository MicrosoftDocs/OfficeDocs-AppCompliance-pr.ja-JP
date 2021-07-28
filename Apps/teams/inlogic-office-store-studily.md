---
title: inLogic-Studi.ly ストア別のアプリケーションOffice情報
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: Studi.ly、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: d682e758d9632a2c3ac19296dda7083dc8379689
ms.sourcegitcommit: a613e40971c8b48fa2b7a35039b4331a8116763b
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/22/2021
ms.locfileid: "53525571"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 8 月 24 日</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

InLogic-Officeストアから Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Studi.ly |
| ID | WA200001668 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | inLogic-Office Store |
| パートナー Web サイトの URL | [https://www.inlogic.dk](https://www.inlogic.dk) |
| プライバシー ポリシーの URL | [https://studi.ly/Studily_Privacy_Statement.pdf](https://studi.ly/Studily_Privacy_Statement.pdf) |
| 利用規約の URL | [https://studi.ly/Studily_Terms_Of_Use_v1.pdf](https://studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する inLogic-Office Store によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | 委任 | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.Read.All | 委任 | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 | 割り当てと資料のグループにディレクトリを記述します。 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Directory.ReadWrite.All | アプリケーション | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 | 割り当てと資料のグループにディレクトリを記述します。 | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.Read.All | アプリケーション | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。 教育 API からデータベースへの時間ベースのイベントで同期します。 | 「Education Classes,School,Members and Terms.Get all classes and schools of a tenant for synchronization of app database. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadBasic | 委任 | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 | 「Education Classes,School,Members and Terms.Get all classes and schools of a tenant for synchronization of app database. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| EduRoster.ReadWrite.All | アプリケーション | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 | 「Education Classes,School,Members and Terms.Get all classes and schools of a tenant for synchronization of app database. | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Files.ReadWrite.All | 委任 | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 | 1 つのドライブからの ReadWrite ファイル | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.Read.All | 委任 | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 | このアクセス許可により、アプリはテナントのグループに対して異なるクレンダー イベントを取得できます。subject、start、end、extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Group.ReadWrite.All | 両方とも | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 | このアクセス許可により、アプリはテナントのグループに対して異なるクレンダー イベントを取得できます。subject、start、end、extensions | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Member.Read.Hidden | アプリケーション |  |  | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| Sites.ReadWrite.All | 両方とも | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 | 1 つのドライブからの ReadWrite ファイル | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.Read | 委任 | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 | ユーザー情報の読み取り | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |
>| User.ReadBasic.All | 委任 | 教育 API のクラス、学校、メンバー、用語の情報を API に保存しています。また、アプリケーションの動作が遅くなるグラフ API から毎回取得する場合に必要です。教育 API からデータベースへの時間ベースのイベントで同期します。 | ユーザー情報の読み取り | [917edb36-f047-45cf-ad96-0e7e9ec7d8af](https://docs.microsoft.com/microsoft-365-app-certification/azure/917edb36-f047-45cf-ad96-0e7e9ec7d8af) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>そのようなデータはログに表示されません

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Azure cosmos データベースに格納され、cosmos データベースで既定で使用できる暗号化とストレージは、このアプリケーションに適用できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>なし

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

