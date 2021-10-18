---
title: AvePoint Inc. による MyHub for Teamsアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 10/06/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Teams の MyHub で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 09e1b6500f75bde564b3f4cf40538516fb6dbae4
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429234"
---
# <a name="myhub-for-teams"></a>MyHub for Teams

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 9 月 29 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/avepoint.myhubforteams" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

AvePoint Inc. から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | MyHub for Teams |
| ID | avepoint.myhubforteams |
| パートナー会社名 | AvePoint Inc. |
| パートナー Web サイトの URL | [https://www.avepoint.com](https://www.avepoint.com) |
| プライバシー ポリシーの URL | [https://www.avepoint.com/company/privacy-policy](https://www.avepoint.com/company/privacy-policy) |
| 利用規約の URL | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて、AvePoint Inc.によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 両方とも | アプリケーション構成データは、データ処理の観点から保存されます | ディレクトリ データの読み取り | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Group.ReadWrite.All | 両方とも | アプリケーション構成データは、データ処理の観点から保存されます | すべてのグループの読み取りと書き込み | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Mail.Send | 委任 | アプリケーション構成データは、データ処理の観点から保存されます | ユーザーからのメールとして送信 | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Reports.Read.All | アプリケーション | アプリケーション構成データは、データ処理の観点から保存されます | すべての利用状況レポートの読み取り | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.FullControl.All | アプリケーション | アプリケーション構成データは、データ処理の観点から保存されます | すべてのサイト コレクションのフル コントロール | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.Read.All | アプリケーション | アプリケーション構成データは、データ処理の観点から保存されます | すべてのサイト コレクションに含まれるアイテムの読み取り | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| Sites.ReadWrite.All | 委任 | アプリケーション構成データは、データ処理の観点から保存されます | すべてのサイト コレクション内のアイテムを編集または削除する | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |
>| User.Read.All | 両方とも | アプリケーション構成データは、データ処理の観点から保存されます | フル プロファイルのすべてのユーザー&#65533;読み取る | [4d69a8e1-9c38-4b33-b76f-9d59b5ae051b](https://docs.microsoft.com/microsoft-365-app-certification/azure/4d69a8e1-9c38-4b33-b76f-9d59b5ae051b) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>はい、ユーザーの電子メールとテナント ID がログに表示されます。 ログはセキュリティで保護された場所に保存され、トラブルシューティング中にアクセスできるのは承認された担当者のみです。 ログは、セキュリティ監査の目的で 60 日後にアーカイブされ、1 年後に削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>アプリケーションのデータは、アプリケーションとAzure SQL DatabaseにAzure Storage。 Azure SQLとAzure Storage暗号化が有効になっています。
データにアクセスできるのは、承認された管理者のみです。 管理者がログインするには MFA が必要です。 操作は監査されます。 IP ホワイトリストは、データへのアクセスを制限するためにも使用されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity の条件を処理する方法について、AvePoint Inc. から提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | アプリケーションは、すべての条件付Azure ADルールを使用できるよう、アプリケーションとフェデレーションを行います。 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | はい |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
