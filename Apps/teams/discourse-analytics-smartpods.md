---
title: Discourse Analytics による SmartPods のアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/20/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: SmartPods で使用可能なすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 96f1e7f8c85e924cfeb095d54d31adc8778b73e1
ms.sourcegitcommit: a615b7893956a0737e30e477d2870fd99e514ea5
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/20/2022
ms.locfileid: "65619440"
---
# <a name="smartpods"></a>SmartPods

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 10 月 5 日</p>

* <a href="https://teams.microsoft.com/l/app/ec120faa-4085-4380-ac60-f1e337f94fc1" target="_blank">Teams ストアで表示する</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004105" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Discourse Analytics から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | SmartPods |
| ID | WA200004105 |
| サポートされているOffice 365 クライアント | Microsoft Teams |
| パートナー会社名 | Discourse Analytics |
| 会社の Web サイト | [https://www.discourseanalytics.com](https://www.discourseanalytics.com) |
| アプリの使用条件 | [https://www.discourseanalytics.com/eula/](https://www.discourseanalytics.com/eula/) |
| アプリのコア機能 | 個人とグループの学習を最適化するためのスマート自動学習グループで明日をリードします。 |
| 会社の本社の場所 | 米国 オブ アメリカ |
| アプリ情報ページ | [https://www.discourseanalytics.com/smartpods/](https://www.discourseanalytics.com/smartpods/) |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | Paas |
| アプリで使用するホスティング クラウド プロバイダーはどれですか? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Discourse Analytics によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | 必要 |
| アプリによって処理されるデータは何ですか? | O365 リソースの学生の使用状況、課題と成績、会議出席に関するデータ |
| アプリは TLS 1.1 以降をサポートしていますか? | 必要 |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データは格納されますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行していますか? | いいえ |
| バックアップと復元の戦略など、文書化されたディザスター リカバリー計画はアプリに含まれていますか? | 必要 |
| お使いの環境では、従来のマルウェア対策保護またはアプリケーション制御が使用されていますか? | ApplicationControls、TraditionalAntiMalware |
| セキュリティの脆弱性をインデントおよびリスク ランク付けするための確立されたプロセスはありますか? | 必要 |
| パッチを適用するためのサービス レベル アグリーメント (SLA) を管理するポリシーはありますか? | 必要 |
| パッチ ポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | 必要 |
| お使いの環境にサポートされていないオペレーティング システムまたはソフトウェアはありますか? | いいえ |
| アプリと、それをサポートするインファ構造に対して四半期ごとの脆弱性スキャンを行いますか? | はい |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | 必要 |
| 変更要求を運用環境にデプロイする前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスはありますか? | 必要 |
| 追加のユーザーは、元の開発者によって運用環境に送信されたすべてのコード変更要求を確認して承認していますか? | 必要 |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | 必要 |
| 多要素認証 (MFA) が有効になっているのは次のとおりです。 | CodeRepositories、DNSManagement、Credential |
| 従業員アカウントのプロビジョニング、変更、削除のための確立されたプロセスはありますか? | 必要 |
| アプリをサポートするネットワーク境界の境界に侵入検出と防止 (IDPS) ソフトウェアがデプロイされていますか? | 該当なし |
| アプリをサポートするすべてのシステム コンポーネントにイベント ログ記録を設定していますか? | 必要 |
| すべてのログは、潜在的なセキュリティ イベントを検出するために、人間または自動化されたツールによって定期的に確認されますか? | 必要 |
| セキュリティ イベントが検出されると、トリアージのために従業員にアラートが自動的に送信されますか? | 必要 |
| 正式な情報セキュリティ リスク管理プロセスが確立されていますか? | 必要 |
| 正式なセキュリティ インシデント対応プロセスが文書化され、確立されていますか? | 必要 |
| 検出から 72 時間以内に、アプリまたはサービスのデータ侵害を監督機関や違反の影響を受けた個人に報告しますか? | 必要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリは、医療保険の可搬性と会計法 (HIPAA) に準拠していますか? | はい |
| アプリは Health Information Trust Alliance、Common Security Framework (HITRUST CSF) に準拠していますか? | いいえ |
| アプリはサービス組織コントロール (SOC 1) に準拠していますか? | いいえ |
| アプリはサービス組織コントロール (SOC 2) に準拠していますか? | いいえ |
| アプリはサービス組織コントロール (SOC 3) に準拠していますか? | いいえ |
| アプリとそのサポート環境に対して、年間 PCI DSS 評価を実行していますか? | いいえ |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | いいえ |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | いいえ |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | いいえ |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | いいえ |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | いいえ |
| アプリは家族教育の権利とプライバシーに関する法律 (FERPA) に準拠していますか? | 必要 |
| アプリは、子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | 該当なし |
| アプリはSarbanes-Oxley法 (SOX) に準拠していますか? | 該当なし |
| アプリは NIST 800-171 に準拠していますか? | 該当なし |
| アプリは Cloud Security Alliance (CSA Star) の認定を受けていますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **応答** |
|:----------------|:-------------|
| GDPR またはその他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリケーションは、シングル サインオン、API アクセスなどのために Microsoft Identity Platform (Azure AD) と統合されますか? | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか? | 必要 |
| アプリは、最新バージョンの MSAL (Microsoft Authentication Library) または Microsoft Identity Web を認証に使用していますか? | 必要 |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリは継続的アクセス評価 (CAE) をサポートしていますか? | いいえ |
| アプリは、コードに資格情報を格納していますか? | いいえ |
| Microsoft 365用のアプリとアドインでは、Microsoft Graphの外部で追加の Microsoft API が使用される場合があります。 アプリまたはアドインは、追加の Microsoft API を使用していますか? | いいえ |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

>|   **Graphアクセス許可**  | **アクセス許可の種類** |          **妥当性**          | **Azure AD アプリ ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| User.ReadBasic.All | 委任 | すべてのユーザーの基本プロファイルを読み取る | [312728bc-5d02-49a5-9230-1f09884f6d04](../azure/312728bc-5d02-49a5-9230-1f09884f6d04.md) |
>| メール | 委任 | ユーザーのメール アドレスを表示する | [312728bc-5d02-49a5-9230-1f09884f6d04](../azure/312728bc-5d02-49a5-9230-1f09884f6d04.md) |
>| openid | 委任 | ユーザーのサインイン | [312728bc-5d02-49a5-9230-1f09884f6d04](../azure/312728bc-5d02-49a5-9230-1f09884f6d04.md) |
>| profile | 委任 | ユーザーの基本的なプロファイルを表示する | [312728bc-5d02-49a5-9230-1f09884f6d04](../azure/312728bc-5d02-49a5-9230-1f09884f6d04.md) |
>| Calendars.ReadWrite | アプリケーション | ボットは、このアクセス許可を使用して会議をスケジュールします | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| Chat.ReadWrite | 委任 | チャットを作成するために必要 | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| ChatMember.Read.Chat | 委任 | チャットにメンバーを追加するために必要 | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| Directory.AccessAsUser.All | 委任 | クラス メンバーのディレクトリ ロールを読み取る | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| Directory.Read.All | 委任 | 学生/教師のディレクトリ ロールを読み取る | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| Directory.ReadWrite.All | 委任 | 学生/教師のディレクトリ ロールを読み取る | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| EduRoster.Read | 委任 | ユーザーの情報を読み取る | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| EduRoster.Read.All | アプリケーション | メッセージを送信するボットのユーザーを読み取る | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| EduRoster.ReadBasic | 委任 | ユーザーの情報を読み取る | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| EduRoster.ReadBasic.All | アプリケーション | ボット別のユーザーがユーザーの情報を読み取り、メッセージを送信する | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| EduRoster.ReadWrite | 委任 | 名簿のユーザー ビューの読み取りと書き込み | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| EduRoster.ReadWrite.All | アプリケーション | ボットがクラス メンバーを読み取るために使用する | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| Member.Read.Hidden | アプリケーション | ボットがクラス メンバーを読み取るために使用する | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| OnlineMeetings.ReadWrite.All | アプリケーション | オンライン会議を作成する | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| User.Read | 委任 | ユーザー プロファイルを読み取る | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| User.Read.All | 委任 | ユーザーの写真を取得するには | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| User.ReadBasic.All | 委任 | ユーザーの写真を取得するには | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| User.ReadWrite | 委任 | ユーザーの写真を取得するには | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |
>| User.ReadWrite.All | 委任 | ユーザーの写真を取得するには | [c884866a-50e4-4b61-a96c-1d22432f7139](../azure/c884866a-50e4-4b61-a96c-1d22432f7139.md) |

>このアプリケーションには、追加の API はありません。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

