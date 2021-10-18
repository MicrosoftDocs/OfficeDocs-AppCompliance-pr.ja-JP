---
title: テンポラルによるワークベンチ インテリジェンスのアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 09/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ワークベンチ インテリジェンス、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-identity
ms.openlocfilehash: 4aaa94f3a1319a2eb06e332e1f23d4c5a1f07439
ms.sourcegitcommit: 983ed1755036e92d99745770f82f33417b21efec
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 10/18/2021
ms.locfileid: "60429024"
---
# <a name="workbench-intelligence"></a>Workbench Intelligence

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>最終更新日: 2021 年 9 月 22 日</p>

* <a href="https://teams.microsoft.com/l/app/d5630318-189a-4912-abae-99b1f8f82cce" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002705" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

テンポラルから Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | Workbench Intelligence |
| ID | WA200002705 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Temporall |
| パートナー Web サイトの URL | [https://www.temporall.com](https://www.temporall.com) |
| [アプリケーション情報Teamsページの URL | [https://www.temporall.com/teams_intelligence/](https://www.temporall.com/teams_intelligence/) |
| プライバシー ポリシーの URL | [https://temporall.com/privacy-policy/](https://temporall.com/privacy-policy/) |
| 利用規約の URL | [https://www.temporall.com/eula](https://www.temporall.com/eula) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関するテンポラルによって提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>| **アクセス許可**  | **アクセス許可の種類 (委任/アプリケーション)** | **データは収集されますか?収集の正当性** | **データは保存されますか?それを格納するための正当性?** | **Azure ADアプリ ID** |
>|:----------------|:------------------------------------------------|:--------------------------------------------------------|:--------------------------------------------------|:--------------------|
>| AppCatalog.Read.All | 委任 | 既知の外部 ID のローカル アプリ ID を取得するためにインストールされている Teams アプリの一覧を取得します。 | ローカル アプリ ID。別のテナントにインストールするときにアプリを識別できる必要があります。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Channel.ReadBasic.All | アプリケーション | チャネル ID &amp; 名。 理由: チャネルに参加または退出してメッセージ アクティビティを同期できます。  | チャネルの取得から返される生データ オブジェクト。 位置合わせ: テンポラル ワークベンチを使用すると、ユーザーはチャネルに応じてデータをフィルター処理して分類できます。 この生データは、元のオブジェクトへの参照を持つデータに保存されます。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| ChannelMessage.Read.All | アプリケーション | 送信者ターゲットと &amp; 共に、メッセージ アクティビティの &amp; 種類。 これらのルートから受信したデータ: /teams/${teamId}/channel/${channelId}/messages /teams/${teamId}/channel/${channelId}/messages/${messageId}。 理由: メッセージアクティビティに関する指標 &amp; レポートを計算する。 これは、組織のネットワーク分析モジュールの中核をなすので、ユーザー チーム間のアクティビティの図を作成 &amp; できます。 | 新しいメッセージ/返信/リアクション/メンションの量が検出され、返される生のメッセージ オブジェクトと共にこれらの指標 &amp; が格納されます。 データは、コア機能の一部を形成する際に必要です。 メッセージ データの分析を実行するには、最適なパフォーマンスを得るデータベースに保存する必要があります。これにより、同じデータに対するフォローアップ呼び出しの必要性も軽減されます。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Directory.Read.All | アプリケーション | ClientId、ユーザーの一覧、組織とサブ チャネルの一覧。 理由: テンポラル ワークベンチへの同期 &amp; ユーザーの読み取りが必要 | ユーザー名、メール、アイコン、会話参照。 Justification:&#160;テンポラル ワークベンチを使用すると、チャネルに従ってデータをフィルター処理して分類できます。 組織のデータは、インストール後にチームに再接続するために保存されます | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| Group.ReadWrite.All | アプリケーション | グループ ID &amp; 名。 理由: 各グループ/チャネルにアプリをインストールするには | 参照用 &amp; の生データ オブジェクトと共にグループ ID 名を指定します。 理由: テンポラル ワークベンチを使用すると、ユーザーはグループ/チームに従ってデータをフィルター処理して分類できます。 この生データは、元のオブジェクトへの参照を持つデータに保存されます。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamMember.Read.All | アプリケーション | チームのユーザー メンバーシップ。 位置合わせ: テンポラル ワークベンチとの間でTeamsユーザーの同期を許可する | 電子メール アドレス、名前、姓。 理由: メールによるユーザーの同期を許可するために、チーム内のユーザーとテンポラル ワークベンチのユーザーとの一致を許可します。 | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForTeam.All | アプリケーション | Team 用にインストールされているアプリの一覧を読み取る。 理由: アプリが既にインストールされている場合は、それ以外の場合はインストールして、グラフ API を介してメッセージ アクティビティを取得できる方法を確認します。 | 該当なし | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| TeamsAppInstallation.ReadWriteForUser.All | アプリケーション | インストールされているアプリの一覧を読み取る。 アプリが既にインストールされている場合は、アンケートを介してユーザーと対話するためにアプリがインストールされていることを確認する | 該当なし | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |
>| User.Read | 委任 | 基本的なユーザー &amp; 企業情報。 理由: ユーザーによるメッセージ アクティビティの分類に使用され、ボットはプロアクティブ メッセージングに参加できます。 | ユーザー名、メール、アイコン、会話参照。 理由: ボットが関連情報を持つユーザーにメッセージを積極的に送信できます。 データ表示用にユーザーをグループ化する | [d5630318-189a-4912-abae-99b1f8f82cce](https://docs.microsoft.com/microsoft-365-app-certification/azure/d5630318-189a-4912-abae-99b1f8f82cce) |


#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-----------------------------------------------------|:------------------------------|:----------------------------------------|
>| Google クラウド | LDAP 情報 | プラットフォームは Google クラウド プラットフォームに存在します |

#### <a name="data-access-via-bots"></a>ボット経由のデータ アクセス

このアプリにボットまたはメッセージング拡張機能が含まれている場合は、エンド ユーザー識別可能な情報 (EUII) にアクセスできます。チームまたはチャットのチーム メンバーの名簿 (名簿、名、表示名、電子メール アドレス)。 このアプリは、この機能を利用しますか?

>EUII にはアクセスされません。


#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>アプリケーションのテレメトリまたはログに OII または EUII は表示されません。

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>https://temporall.com/privacy-policy/

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>はい

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end


::: zone pivot="identity"

### <a name="identity-information"></a>ID 情報

この情報は、このアプリが認証、承認、アプリケーション登録のベスト プラクティス、その他の Id 条件を処理する方法について、テンポラルによって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| Microsoft Identify Platform (Azure AD) と統合しますか?  | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか?  | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) を使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリがシナリオに対して最小特権のアクセス許可を要求していますか? | はい |
| アプリの静的に登録されたアクセス許可は、アプリが動的かつ段階的に要求するアクセス許可を正確に反映していますか? | はい |
| アプリはマルチテナントをサポートしていますか? | はい |
| アプリに機密クライアントがありますか? | はい |
| アプリに登録されているリダイレクト統合リソース識別子 (URI) はすべて所有していますか? | はい |
| アプリの場合、何を使用しないのですか? | - ワイルドカード リダイレクト URI、<br/>- OAuth2 暗黙的Flow SPA に必要な場合を含む場合を含む<br/>- リソース所有者パスワード資格情報 (ROPC) フロー |
| アプリは Web API を公開していますか? | 不要 |
| アプリでプレビュー API を使用していますか? | はい |
| アプリで非推奨の API を使用していますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
