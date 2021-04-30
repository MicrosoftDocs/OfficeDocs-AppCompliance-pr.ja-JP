---
title: OnePlace ソリューションによる OnePlaceMail Outlookアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 01/31/2021
ms.topic: article
ms.service: attestation
description: onePlaceMail for Outlook、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas-identity
ms.openlocfilehash: 380e836399d5978b0312b7f1e9dccb4144e09840
ms.sourcegitcommit: e97156a6eaf1d5ec5c26fd14add210a92bacd944
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/30/2021
ms.locfileid: "52095914"
---
# <a name="oneplacemail-for-outlook"></a>OnePlaceMail for Outlook

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 1 月 31 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380723" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

OnePlace Solutions から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | OnePlaceMail for Outlook |
| ID | WA104380723 |
| Office 365サポートされているクライアント | Outlook 2013 以降の mac Windows、Outlook 2016 以降、iOS の Outlook、Android 上の Outlook、web Outlook |
| パートナー会社名 | OnePlace ソリューション |
| パートナー Web サイトの URL | [https://www.oneplacesolutions.com/](https://www.oneplacesolutions.com/) |
| プライバシー ポリシーの URL | [https://www.oneplacesolutions.com/oneplacemailapp-privacy](https://www.oneplacesolutions.com/oneplacemailapp-privacy) |
| 利用規約の URL | [https://www.oneplacesolutions.com/oneplacemailapp-eula](https://www.oneplacesolutions.com/oneplacemailapp-eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する OnePlace ソリューションによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure AD アプリ ID** |
>|:----------------|:--------------------|:---------------------------------------------------|:--------------------------|:--------------------------|
>| Group.ReadWrite.All | 委任 | 現在のユーザー Teamsのメンバーを特定するために必要です。 | なし | 44a72516-136f-4a55-ae26-ef09977230be |
>| Mail.ReadWrite.Shared | 委任 | メール のプロパティにアクセスして、SharePoint列を設定し、メール アイテムの [SharePointに転送] カテゴリを追加するために必要 | なし | 44a72516-136f-4a55-ae26-ef09977230be |
>| MailboxSettings.ReadWrite | 委任 | 収集または使用されるデータがない場合、ユーザー メールボックスのマスター カテゴリ リストにカテゴリを追加するために使用されます。 | なし | 44a72516-136f-4a55-ae26-ef09977230be |
>| Sites.ReadWrite.All | 委任 | アプリがアップロードしたアイテムのプロパティを設定するために必要SharePoint。 | なし | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.Read | 委任 | Microsoft サーバーへの認証にGraph。 | 次のデータは、アプリによってデータベースに格納され、サブスクリプションとユーザー ライセンスの追跡に使用されます。ユーザー ID、メール、名。 | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | 委任 | ユーザー選択フィールドにユーザー プロファイル イメージを表示するために必要です。 | なし | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadBasic.All | 委任 | ユーザー選択フィールドにユーザー プロファイル イメージを表示するために必要です。 | なし | 44a72516-136f-4a55-ae26-ef09977230be |
>| User.ReadWrite.All | 委任 | テナントのユーザー内で Teamsサービスが有効になっているかどうかを確認Office 365必要です。 | なし | 44a72516-136f-4a55-ae26-ef09977230be |

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| SharePoint | はい | SharePointURL、ライブラリ名、リスト名、フォルダー名 | アクセスされる組織の情報は、電子メールや添付ファイルをユーザーからユーザーに保存するプロセスExchangeにSharePoint。 この追加のデータは保存され、転送中に暗号化されます。 このデータの例には、Choice SharePoint、分類値、コンテンツ タイプ名、フォルダー名、サイト名などの列の値が含まれます。  | このデータはアプリによって保存または収集されませんが、テレメトリ/ログに表示され、90 日間保持されます。 | データが保存されない |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| 課金サービスは、サブスクリプションの管理と請求に使用されます。 アプリ内 (無料) サブスクリプションの作成では、ユーザーの名、名、電子メール アドレスが Chargify と共有されます。 購入したサブスクリプション (複数のライセンスユーザーをサポート) の場合、個々のユーザーの詳細は Chargify サービスと共有されません。 | 電子メール アドレス | サブスクリプション ライフサイクル イベントをユーザーに伝達するには |



#### <a name="add-in-data-access"></a>アドイン のデータ アクセス

このアプリが組織のデータにアクセスするために必要なアクセス許可、このアクセス許可の正当性と目的 (アプリは何のためにこの情報を使用するのか)、およびアプリがデータベースにこの情報を格納するかどうかを一覧表示します。

>| **アクセス許可**  | **説明** |
>|:----------------|:----------------|
>| ReadWrite メールボックス | このアドインは、メールボックス内の任意のアイテムの内容を読み取りまたは変更し、新しいアイテムを作成できます。 任意のメッセージまたは予定表アイテムの本文、件名、送信者、受信者、添付ファイルなどの個人情報にアクセスできます。 このデータは、サードパーティ のサービスに送信される場合があります。 |
>| データの送信 | インターネットを使用してデータを送信できます |

#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>EUII と OII はテレメトリに表示されます。 この情報は Application Insights に保存され、保存時に暗号化され、アクセスが制御され、90 日後に削除されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>アプリケーションに格納されているデータは、転送中および保存時に暗号化されます。 アプリのOffice 365に依存しています。そのため、ユーザー パスワードはシステムに保存できません。 保存されたデータ/ログ/テレメトリへのアクセスは、アプリの正常性を実行および監視するために情報にアクセスする必要がある内部管理スタッフに厳しく制御されます。 Two-Factorすべての内部管理スタッフに適用される認証。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/35746" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Identity 条件を処理する方法について OnePlace ソリューションによって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、
<br />
- OAuth2 暗黙的なFlow(SPA に必要な場合を含む)
<br />
- リソース所有者パスワード資格情報 (ROPC) フロー | |アプリは Web API を公開していますか? |はい | |アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? |はい | |アプリでプレビュー API を使用していますか? |いいえ| |アプリで非推奨の API を使用していますか? |いいえ|

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
