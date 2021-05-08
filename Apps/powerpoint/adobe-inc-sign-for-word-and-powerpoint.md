---
title: Adobe Sign for Word および Adobe Inc. PowerPointアプリケーション情報。
ms.author: elmalova
author: elenamalova
ms.date: 02/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Adobe Sign for Word および PowerPoint、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 3ac861b6472b9c96483ea3e8a9ad8fd4d7f02834
ms.sourcegitcommit: 84c041bf4c0e79f1f3a14c4885ca5acd8709b129
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/06/2021
ms.locfileid: "52258944"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>Adobe Sign for Word and PowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2021 年 2 月 12 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Adobe Inc. から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Adobe Sign for Word and PowerPoint |
| ID | WA104381155 |
| Office 365サポートされているクライアント | Word 2016 Mac の PowerPoint 2013 Service Pack 1 以降の Windows、Word 2013 Service Pack 1 以降 (Windows、Word on the web、PowerPoint on the web、PowerPoint 2016 以降) |
| パートナー会社名 | Adobe Inc. |
| パートナー Web サイトの URL | [https://www.adobe.com/](https://www.adobe.com/) |
| プライバシー ポリシーの URL | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| 利用規約の URL | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つ制御に関して Adobe Inc. から提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | 委任 | 添付されたドキュメント、送信者と受信者の電子メール、およびメッセージ コンテンツを電子メールから Adobe 記号に入力して署名用に送信します。 これは、Adobe Sign でこれらのフィールドを再入力するユーザー時間を節約するために使用します。 契約が署名された後、ユーザーが電子メールを送信して、トランザクションが完了したことを受信者に通知する新しい電子メールを自動的に作成します。 | Adobe Sign は添付ファイルを一時ファイルとして保存します。有効期限は 24 時間です。 | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| People.Read | 委任 | 署名用に送信エクスペリエンスで電子メール アドレスを自動入力するには、最初の文字を入力して、ユーザーにメール全体を入力 &quot; &quot; する必要が生じかねない。 | Adobe Sign は、受信者の電子メールと displayName のみを契約に保存します。 | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| User.Read | 委任 | ユーザーのプロファイルを読み取り、自分のプロファイル (基本的には電子メールと userId) をデータベースに一致して、Adobe Sign を使用できます。 | ユーザーのプロファイルを読み取り、自分のプロファイル (基本的には電子メールと userId) をデータベースに一致して、Adobe Sign を使用できます。 | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| offline_access | 委任 | アクセス トークンを更新するには、現在のトークンの有効期限が切れています。 たとえば、ユーザーが署名用の送信ウィンドウで非アクティブな状態を長くする場合は、ユーザーがアクティブなときに新しいトークンを更新 &quot; &quot; する必要があります。 | アクセス トークンを更新するには、現在のトークンの有効期限が切れています。 たとえば、ユーザーが署名用の送信ウィンドウで非アクティブな状態を長くする場合は、ユーザーがアクティブなときに新しいトークンを更新 &quot; &quot; する必要があります。 | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |
>| openid | 委任 | メールと UserId。 ユーザーにサインインして、Adobe Sign アプリの使用許可に対する同意を得る。  | 電子メールは、Adobe Sign のユーザーの一意の識別子です。 メール ID を保存して、そのユーザーのすべてのアクティビティを Adobe Sign レコードにマップできます。  | 72d5ac5d-a427-408b-907d-72da3f33ddd1 |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>非Microsoft サービスは使用されません。



#### <a name="add-in-data-access"></a>アドイン のデータ アクセス

このアプリが組織のデータにアクセスするために必要なアクセス許可、このアクセス許可の正当性と目的 (アプリは何のためにこの情報を使用するのか)、およびアプリがデータベースにこの情報を格納するかどうかを一覧表示します。

>| **アクセス許可**  | **説明** |
>|:----------------|:----------------|
>| ReadWrite ドキュメント | ドキュメントの読み取りおよび変更が可能 |
>| データの送信 | インターネットを使用してデータを送信できます |

#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>ログには、お客様の問題を特定して修正できる十分な情報が含まれます。 ログは 90 日間保持され、アクセスが制限されます。 データベース ストアには、ユーザーがオフラインの間に認証用のハッシュ化された ID 情報が格納されます。 データベース保持ポリシーは、最後に使用された日から 30 日です。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>アプリケーションを使用する場合、システムに顧客管理者の操作Microsoft Teamsしません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity の条件を処理する方法について Adobe Inc. から提供されています。

| **Information** | **応答** |
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
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的フロー (SPA に必要な場合を含む)<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | いいえ |
| アプリで非推奨の API を使用していますか? | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
