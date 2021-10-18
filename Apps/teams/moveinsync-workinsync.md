---
title: MoveInSync による WorkInSync のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/02/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: WorkInSync で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 35a505013b59bdd9cc0d9b40986acea1f1c19b53
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60442719"
---
# <a name="workinsync"></a>WorkInSync

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 9 月 1 日</p>

* <a href="https://teams.microsoft.com/l/app/4e00663a-be72-4de1-a163-269a477a7a6e" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002974" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

MoveInSync から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | WorkInSync |
| ID | WA200002974 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | MoveInSync |
| パートナー Web サイトの URL | [https://www.workinsync.io](https://www.workinsync.io) |
| [アプリケーション情報Teamsページの URL | [https://www.workinsync.io/teams-app-for-workinsync/](https://www.workinsync.io/teams-app-for-workinsync/) |
| プライバシー ポリシーの URL | [https://www.workinsync.io/privacy-policy/](https://www.workinsync.io/privacy-policy/) |
| 利用規約の URL | [https://www.workinsync.io/terms-and-condition/](https://www.workinsync.io/terms-and-condition/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する MoveInSync によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| Directory.Read.All | 委任 | 1. 推移的なグループ メンバーの詳細を取得します。 チャネル コンテキストにインストールされている場合は、[チーム アクティビティ] タブで使用されます。 2. 組織内のユーザーのログイン ユーザー プロファイルの &amp;  詳細一覧を取得します。 これらは、個人のコンテキストで [チーム アクティビティ] タブがインストールされている場合に使用されます。ユーザー API が失敗した場合にチームメイトのプレビューを表示するためにフォール バックとして使用されます (Outlook 以外のユーザー) | なし | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| People.Read | 委任 | ログインしているユーザーに最も関連のあるユーザーを [チーム アクティビティ] タブに表示するには、個人コンテキストにインストールされます。 | なし | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| Presence.Read | 委任 | 個人用コンテキストとチャネル コンテキストの両方の [チーム アクティビティ] タブでユーザーのリストのプレゼンス情報を取得するには | なし | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| Presence.Read.All | 委任 | 個人用コンテキストとチャネル コンテキストの両方の [チーム アクティビティ] タブでユーザーのリストのプレゼンス情報を取得するには | なし | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| User.Read.All | アプリケーション | 予約とチェックイン/チェックアウトの通知をマネージャーに送信する任意のユーザーのレポート マネージャー情報を取得するために使用されます。 | なし | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| User.ReadBasic.All | 委任 | 従業員のプロフィール写真を読み取る場合に使用します。 | なし | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| メール | 委任 | クライアント ライブラリを使用して SSO トークンを取得Teams必要 | なし | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| offline_access | 委任 | クライアント ライブラリを使用して SSO トークンを取得Teams必要 | なし | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| openid | 委任 | クライアント ライブラリを使用して SSO トークンを取得Teams必要 | なし | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |
>| profile | 委任 | クライアント ライブラリを使用して SSO トークンを取得Teams必要 | なし | [fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc](https://docs.microsoft.com/microsoft-365-app-certification/azure/fdabfc71-2cf8-42f0-bcdd-83e5f4acfdcc) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>| **EUII にアクセスする理由**  | **EUII はデータベースに格納されていますか?** | **EUII を格納するための理由** |
>|:---------------------------------------|:-----------------------------------|:------------------------------------|
>| 1. 従業員の電子メール アドレス (ユーザー原則名) を読み取り、WorkInSync の登録済みユーザーの一覧と一致します。  | いいえ |  |


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>データはパートナー システムと共有または保存されません。 すべてのデータ ストアは、WorkInSync だけで完全に所有および管理されます。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>不要

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の IDENTITY 条件を処理する方法について MoveInSync によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | いいえ |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | 多要素認証 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/><br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | いいえ |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
