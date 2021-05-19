---
title: inLogic-Office ストアによる Studi.ly のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 08/24/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: STUDI.LY、そのデータ処理ポリシー、そのMicrosoft Cloud App Securityアプリカタログ情報、CSA STARレジストリ内のセキュリティ/コンプライアンス情報に関する、利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 26a89739809e0d398db2a823bd714aa06a2d210d
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553058"
---
# <a name="studily"></a>Studi.ly

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2020年8月24日</p>

* <a href="https://teams.microsoft.com/l/app/a1eca727-7b59-4439-b269-f4b800030518" target="_blank">Teams店舗で表示</a>
* <a href="https://appsource.microsoft.com/product/office/WA200001668" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

inLogic-Officeストアからマイクロソフトに提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Studi.ly |
| ID | WA200001668 |
| サポートされるクライアントOffice 365 | Microsoft Teams |
| パートナー会社名 | inLogic-Office Store |
| パートナーウェブサイトのURL | [https://www.studi.ly](https://www.studi.ly) |
| プライバシーポリシーの URL | [https://www.studi.ly/Studily_Privacy_Statement.pdf](https://www.studi.ly/Studily_Privacy_Statement.pdf) |
| 利用規約の URL | [https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf](https://www.studi.ly/Studily_Terms_Of_Use_v1.pdf) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して格納する方法、およびアプリが収集するデータに対する組織のコントロールに関する inLogic-Office Store によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Calendars.ReadWrite | 委任 | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.Read.All | 委任 | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 | 割り当てと資料のグループにディレクトリを書き込みます。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Directory.ReadWrite.All | アプリケーション | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 | 割り当てと資料のグループにディレクトリを書き込みます。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.Read.All | アプリケーション | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合、私たちはそれを必要とします。 教育 API からデータベースに時間ベースのイベントで同期します。 | 教育クラス、学校、メンバー、および用語を読む.アプリデータベースに同期するためのテナントのすべてのクラスと学校を取得します。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadBasic | 委任 | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 | 教育クラス、学校、メンバー、および用語を読む.アプリデータベースに同期するためのテナントのすべてのクラスと学校を取得します。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| EduRoster.ReadWrite.All | アプリケーション | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 | 教育クラス、学校、メンバー、および用語を読む.アプリデータベースに同期するためのテナントのすべてのクラスと学校を取得します。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Files.ReadWrite.All | 委任 | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 | 1 つのドライブからファイルを読み書きする | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.Read.All | 委任 | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 | このアクセス許可により、アプリはテナントのグループに対して異なるクレーンダ イベントを取得することができました。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Group.ReadWrite.All | 両方とも | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 | このアクセス許可により、アプリはテナントのグループに対して異なるクレーンダ イベントを取得することができました。 | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Member.Read.Hidden | アプリケーション |  |  | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| Sites.ReadWrite.All | 両方とも | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 | 1 つのドライブからファイルを読み書きする | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.Read | 委任 | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 | ユーザー情報の読み取り | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |
>| User.ReadBasic.All | 委任 | 私たちは、私たちのAPIに教育APIからのクラス、学校やメンバーと用語の情報を格納しており、私たちは私たちのアプリケーションの仕事を遅くするグラフAPIから毎回それを取得する場合のために、私たちはそれを必要とします。教育 API からデータベースに時間ベースのイベントで同期します。 | ユーザー情報の読み取り | 917edb36-f047-45cf-ad96-0e7e9ec7d8af |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータアクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合、チームまたはチャットのチーム メンバーの名簿 (名前、姓、表示名、電子メール アドレス) のユーザーを識別できる情報 (EUII) にアクセスできます。 このアプリはこの機能を利用していますか?

>EUII はアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>このようなデータはログに表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>このデータベースは Azure cosmos データベースに格納され、cosmos データベースで既定で使用できる暗号化とストレージは、このアプリケーションに適用できます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35976" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

