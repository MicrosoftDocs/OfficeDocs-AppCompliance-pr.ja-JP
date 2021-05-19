---
title: アドビ・サイン・フォー・ワードおよびPowerPointのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 02/12/2021
ms.topic: article
ms.service: attestation
certification_type: certified
description: Adobe Sign for Word および PowerPoint、データ処理ポリシー、Microsoft Cloud App Securityアプリカタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: aa9b4a19f83574d7d9428bbf979ac7ee1375227c
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553648"
---
# <a name="adobe-sign-for-word-and-powerpoint"></a>アドビ・サイン・フォー・ワードとPowerPoint

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者による最終更新日: 2021 年 2 月 12 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381155" target="_blank">アプリソースで表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

アドビ社がマイクロソフトに提供する情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | アドビ・サイン・フォー・ワードとPowerPoint |
| ID | WA104381155 |
| サポートされるクライアントOffice 365 | Mac でWord 2016以降、2013 年サービス パック 1 以降 PowerPointの Windows、Word 2013 Service Pack 1 以降の Windows、Word on the web、PowerPoint on the web、PowerPoint 2016以降の Mac 上でのWord 2016以降 |
| パートナー会社名 | 株式会社アドビ |
| パートナーウェブサイトのURL | [https://www.adobe.com/](https://www.adobe.com/) |
| プライバシーポリシーの URL | [https://www.adobe.com/privacy/policies-business/esign.html](https://www.adobe.com/privacy/policies-business/esign.html) |
| 利用規約の URL | [https://support.office.com/client/61994a3b-2c87-41c4-a88d-a...](https://support.office.com/client/61994a3b-2c87-41c4-a88d-a6455efa362d?omkt=en) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法、およびアプリが収集するデータに対する組織のコントロールに関する Adobe Inc. によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>マイクロソフトGraphを使用したデータ アクセス

このアプリが必要とする[Microsoft Graphのアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?それを収集するための正当化?** | **データは保存されますか?それを保存するための正当化?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Mail.ReadWrite | 委任 | 添付されたドキュメント、送信者と受信者の電子メール、および電子メールから Adobe への署名に送信するメッセージの内容を設定します。 これは、ユーザーが Adobe Sign でこれらのフィールドを再入力する時間を節約するために使用します。 契約が締結されると、ユーザーが電子メールを送信して、取引が完了したことを受信者に通知するための新しい電子メールが自動的に作成されます。 | Adobe Sign は添付ファイルを一時ファイルとして保存し、有効期限は 24 時間です。 | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| People.Read | 委任 | 署名用に送信エクスペリエンスで電子メール アドレスを自動入力するには &quot; &quot; 、いくつかの最初の文字を入力して、ユーザーが電子メール全体を入力する必要はありません。 | アドビサインは、受信者の電子メールと表示名のみを契約に保存します。 | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| User.Read | 委任 | ユーザーのプロファイルを読み取り、彼らがAdobe Signを使用できるように、自分のプロファイル(基本的には、電子メールとuserId)をデータベースに一致させる。 | ユーザーのプロファイルを読み取り、彼らがAdobe Signを使用できるように、自分のプロファイル(基本的には、電子メールとuserId)をデータベースに一致させる。 | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| offline_access | 委任 | 現在のトークンが期限切れになったときにアクセス トークンを更新します。 たとえば、ユーザーが &quot; 署名の送信ウィンドウに表示 &quot; され、非アクティブな状態に長時間放置した場合、ユーザーがアクティブな場合に新しいトークンを更新する必要があります。 | 現在のトークンが期限切れになったときにアクセス トークンを更新します。 たとえば、ユーザーが &quot; 署名の送信ウィンドウに表示 &quot; され、非アクティブな状態に長時間放置した場合、ユーザーがアクティブな場合に新しいトークンを更新する必要があります。 | 72d5ac5d-a427-408b-907d-72da3f33dd1 |
>| openid | 委任 | 電子メールとユーザー ID。 Adobe Sign アプリの使用許可に対する同意を確認するためにユーザーにサインインすること。  | 電子メールは、アドビサインのユーザーの一意の識別子です。 電子メール ID を保存して、そのユーザーのすべてのアクティビティを、そのユーザーの Adobe Sign レコードにマップできるようにします。  | 72d5ac5d-a427-408b-907d-72da3f33dd1 |


#### <a name="non-microsoft-services-used"></a>使用Microsoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由を示します。

>非Microsoft サービスは使用されません。



#### <a name="telemetry-data"></a>テレメトリ データ

このアプリケーションのテレメトリまたはログに、組織を識別できる情報 (OII) またはエンド ユーザーを特定できる情報 (EUII) が表示されますか。 「はい」の場合、保存されるデータと保存ポリシーと削除ポリシーについて説明します。

>当社のログには、お客様の問題を特定して修正するための十分な情報が含まれています。 ログは 90 日間保持され、アクセスは制限されます。 ユーザーがオフラインの間、認証用のハッシュ識別情報をデータベースストアに格納します。 データベースの保持ポリシーは、最後に使用された 30 日後です。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーが保存するデータの組織的な統制

組織の管理者がパートナー システムの情報を制御する方法について説明する。削除、保存、監査、アーカイブ、エンドユーザーポリシーなど

>私たちは、アプリケーションのシステムに顧客管理の相互作用Microsoft Teams持っていません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間的レビュー

人間は、このアプリによって収集または保存される組織識別情報(OII)データのレビューまたは分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報は以下に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/11641" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベストプラクティス、およびその他の ID 基準を処理する方法について Adobe Inc. から提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| マイクロソフト識別プラットフォーム (Azure AD) と統合しますか。  | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか。  | はい |
| アプリは認証に MSAL (マイクロソフト認証ライブラリ) を使用していますか? | いいえ |
| アプリで条件付きアクセス ポリシーがサポートされていますか。 | いいえ |
| アプリがシナリオに対して最低限の権限を要求しているか。 | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的に、または増分的に要求するアクセス許可を正確に反映していますか。 | はい |
| アプリでマルチテナント機能がサポートされていますか。 | はい |
| アプリに機密クライアントが存在しますか? | いいえ |
| アプリに登録されているすべてのリダイレクト統一リソース識別子 (URI) を所有していますか。 | はい |
| アプリの場合、何を使用しないようにしますか。 | - ワイルドカードリダイレクト URI<br/>- Spa に必要な場合を除き、OAuth2 暗黙的なFlow<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか。 | はい |
| クライアント アプリが適切な同意を得た場合にのみ、アクセス許可モデルで呼び出しが成功することを許可しますか。 | はい |
| アプリでプレビュー API を使用していますか。 | いいえ |
| アプリで非推奨の API が使用されていますか。 | なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
