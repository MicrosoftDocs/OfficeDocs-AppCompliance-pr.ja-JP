---
title: エキスパート システム IVR(Asia) による ecBooking のアプリケーション Co.Ltd。
ms.author: elmalova
author: elenamalova
ms.date: 12/28/2020
ms.topic: article
ms.service: attestation
certification_type: attested
description: ecBooking で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: f36edd400f35d7e4ccbfef5edd0225855f73ab69
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59288203"
---
# <a name="ecbooking"></a>ecBooking

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2020 年 12 月 28 日</p>

* <a href="https://teams.microsoft.com/l/app/fe9627db-f23e-42b1-b454-d4d1ca5af33e" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002096" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

エキスパート システム IVR(Asia) が提供する情報 Co.Ltd。Microsoft に:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | ecBooking |
| ID | WA200002096 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Expert Systems IVR(Asia) Co.Ltd. |
| パートナー Web サイトの URL | [https://www.esi-asia.com](https://www.esi-asia.com) |
| [アプリケーション情報Teamsページの URL | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/) |
| プライバシー ポリシーの URL | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1510822239639-efecac03-d43200b0-aa88) |
| 利用規約の URL | [https://www.esi-asia.com/product/intelligent-room-booking-s...](https://www.esi-asia.com/product/intelligent-room-booking-system/#1598241760681-29d114e0-5c2b) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、エキスパート システム IVR(Asia) Co.Ltd。このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Calendars.ReadWrite | アプリケーション | ユーザー メール、ユーザー イベントなどのデータが格納されます。 ユーザー イベントは、会議室の可用性を確認し、イベントを作成する際に収集されます。 | Users イベントの ID、場所名、その他のイベントの詳細が保存されます。 会議室の空き時間情報を確認し、イベントを作成するためのデータが収集されます。 | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| Mail.Send | アプリケーション | ユーザーメールなどのデータ。 ユーザーメールは、ルーム予約通知メールの送信用に収集されます。 | ユーザーメールなどのデータ。 ユーザーメールは、ルーム予約通知メールの送信用に収集されます。 | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| User.Read | 委任 | ユーザー ID、名前、電子メールなどのデータ。 ユーザー データは、アプリケーションでのサインイン ユーザーのために収集されます。 | ユーザー ID、名前、電子メールなどのデータ。 ユーザー データは、アプリケーションでのサインイン ユーザーのために収集されます。 | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| User.Read.All | アプリケーション | ユーザー ID、名前、電子メールなどのデータ。 ユーザー データは、アプリケーションでのサインイン ユーザーのために収集されます。 | ユーザー ID、名前、電子メールなどのデータ。 ユーザー データは、アプリケーションでのサインイン ユーザーのために収集されます。 | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| メール | 委任 | ユーザーメールなどのデータ。 User Emailare は、ユーザーの可用性を確認し、イベントを作成するための収集を行います。 | ユーザーメールなどのデータ。 User Emailare は、ユーザーの可用性を確認し、イベントを作成するための収集を行います。 | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |
>| openid | 委任 | ユーザーがアプリケーションにログインする openid inorder。 | ユーザーがアプリケーションにログインする openid inorder。 | [a85d5d70-9b9c-46e4-bdd6-d139f1648dea](https://docs.microsoft.com/microsoft-365-app-certification/azure/a85d5d70-9b9c-46e4-bdd6-d139f1648dea) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>ユーザー メール、ユーザー イベントなどのデータが格納されます。 

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データベースに格納されているデータ。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/36415" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、エキスパート システム IVR(Asia) Co.Ltd。このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について説明します。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | いいえ |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/><br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
