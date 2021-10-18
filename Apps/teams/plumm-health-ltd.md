---
title: Plumm Health LTD による Plumm のアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 10/14/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: プラム、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 8fef6e74339b611b06d39e6bbe32f9661e20656c
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429875"
---
# <a name="plumm"></a>Plumm

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 8 月 18 日</p>

* <a href="https://teams.microsoft.com/l/app/d66da813-3337-4f88-8e08-f01c0bbb8f34" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003326" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Plumm Health LTD から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Plumm |
| ID | WA200003326 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Plumm Health LTD |
| パートナー Web サイトの URL | [https://www.plummhealth.com](https://www.plummhealth.com) |
| [アプリケーション情報Teamsページの URL | [https://www.plummhealth.com/about-us](https://www.plummhealth.com/about-us) |
| プライバシー ポリシーの URL | [https://www.plummhealth.com/privacy-policy](https://www.plummhealth.com/privacy-policy) |
| 利用規約の URL | [https://www.plummhealth.com/terms-of-use](https://www.plummhealth.com/terms-of-use) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて、Plumm Health LTD によって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| TeamsActivity.Send | アプリケーション | このアクセス許可で userID を使用します。 これは、サービスの使用状況に基づいてユーザーに必要な通知を送信するために使用されます。 これは、ユーザーがアプリで自分のアカウントの適切な通知を受け取る場合に重要です。 | このアクセス許可では、データベースにデータは格納されません。 実際、ユーザー ID を使用して、使用状況に基づいて個々のユーザーに適切な通知を送信しています。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| TeamsAppInstallation.ReadWriteForUser.All | アプリケーション | このアクセス許可を使用してインストール ID を受け取る。 これは、個々のユーザーに適切で正しい通知を送信するために重要です。 | このアクセス許可を使用して、アプリにデータを保存することは一切行われな ユーザー ID を指定することで実行時に取得されるインストール ID だけが必要なので、必要とされません。 これは実行時に動的に取得するため、インストール ID を保存する必要はありません。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read | 委任 | このアクセス許可を使用して、ユーザーの名前、画像、電子メールを収集しています。 これは、個々のユーザーを識別するために必要であり、これらのデータ ポイントは、個々のプロファイル ページや電子メール/通知通信など、必要な場所に表示されます。 | このアクセス許可により、アプリはユーザーの基本的なプロファイル (名前、画像、電子メール) を表示できます。 このデータは、ユーザーの名前やプロフィール画像をアプリ アカウントに表示したり、電子メール通信や通知に使用します。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| User.Read.All | アプリケーション | このアクセス許可を使用すると、サインインしているユーザーなしでユーザー プロファイルを読み取るアプリが許可されます。 ここでは、現在、名前、プロファイル画像、およびメールのみを収集しています。 これは、個々のユーザーを識別するために必要であり、これらのデータ ポイントは、個々のプロファイル ページや電子メール/通知通信など、必要な場所に表示されます。 | このアクセス許可により、アプリはユーザーの基本的なプロファイル (名前、画像、電子メール) を表示できます。 このデータは、ユーザーの名前やプロフィール画像をアプリ アカウントに表示したり、電子メール通信や通知に使用します。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| メール | 委任 | ユーザーの電子メール ID が収集されます。 このデータは、サービスのユーザーにアクセス権を付与し、アプリにサインインし、このメール ID で自分のアカウントとサービスに関する通知を受け取る必要があります。  | 電子メール ID はデータベースに格納されます。 ユーザーを一意に識別し、アプリへのアクセスを提供し、サインインし、アカウントに関する通知を受け取るのを助けるために、電子メール ID を保存する必要があります。 たとえば、電子メール ID を持つユーザー abc@xyz.com、このメール ID を使用してアプリとサービスにログインTeams &quot; &quot; アクセスできます。 使用状況に基づいて、このユーザーに電子メール ID で通知を送信できます。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| openid | 委任 | このアクセス許可については、データを収集する必要があります。  | このアクセス許可については、データを収集する必要があります。 このアクセス許可を使用すると、ユーザーは仕事用メール ID を使用してアプリにサインインし、アプリに基本的なユーザー プロファイル情報を表示できます。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |
>| profile | 委任 | このアクセス許可を使用して、ユーザーの名前、画像、電子メールを収集しています。 これは、個々のユーザーを識別するために必要であり、これらのデータ ポイントは、個々のプロファイル ページや電子メール/通知通信など、必要な場所に表示されます。 | このアクセス許可により、アプリはユーザーの基本的なプロファイル (名前、画像、電子メール) を表示できます。 このデータは、ユーザーの名前やプロフィール画像をアプリ アカウントに表示したり、電子メール通信や通知に使用します。 | [b1d1c038-a1f3-4802-be93-0f4a66589e73](https://docs.microsoft.com/microsoft-365-app-certification/azure/b1d1c038-a1f3-4802-be93-0f4a66589e73) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Intercom | 名、名、電子メール | Intercom は、すべてのユーザーとのコミュニケーションを管理するのに役立つ CRM です。 そのため、適切なメッセージ/電子メールをユーザーに送信するために、ユーザーの名、名、電子メール ID を CRM に送信する必要があります。 |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>使用される治療セッションの数、表示されたコース、表示された瞑想、セッションの日付などのサービス使用状況データを保存します。ユーザーがアカウントの削除または「忘れ」を特に求めるまで、ユーザーのデータは保持されます。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>サーバーを介して CRM に送信されるデータを管理します。 機能に必要な最小データは CRM (Intercom) に渡されます。 Plumm は、CRM に渡されるデータ、Intercom 上のデータの保持、およびデータの削除を完全に制御します。 Intercom の顧客データ ポリシーを確認するリンクを次に示します。 https://www.intercom.com/legal/terms-and-policies#customer-data

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の ID 基準を処理する方法について、Plumm Health LTD によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | いいえ |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | ,<br/><br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | はい |
| アクセス許可モデルでは、クライアント アプリが適切な同意を受け取った場合にのみ呼び出しが成功しますか? | はい |
| アプリでプレビュー API を使用していますか? | 不要 |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
