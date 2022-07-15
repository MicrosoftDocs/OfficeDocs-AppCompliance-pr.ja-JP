---
title: プッシュ セキュリティによるプッシュ セキュリティのアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/15/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: プッシュ セキュリティ、データ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報に関するすべての利用可能なセキュリティ情報とコンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: a8a853b6b4f581b8cf9c4951380527993ad9850e
ms.sourcegitcommit: 9e5c6c3b4885bc6fa0a4af61432c86a232bc7ec9
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/15/2022
ms.locfileid: "66817694"
---
# <a name="push-security"></a>セキュリティのプッシュ

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2022 年 7 月 12 日</p>

* <a href="https://teams.microsoft.com/l/app/db06ca6c-96a2-48ef-804e-54295b5c035a" target="_blank">Teams ストアで表示する</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002833" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Push Security から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | セキュリティのプッシュ |
| ID | WA200002833 |
| サポートされているOffice 365 クライアント | Microsoft Teams |
| パートナー会社名 | セキュリティのプッシュ |
| 会社の Web サイト | [https://pushsecurity.com](https://pushsecurity.com) |
| アプリの使用条件 | [https://pushsecurity.com/legal/terms/](https://pushsecurity.com/legal/terms/) |
| アプリのコア機能 | Microsoft は、従業員がアプリを安全に使用できるようにすることで、SaaS の生産性を高めるのに役立ちます。 |
| 会社の本社の場所 | 英国の英国と北アイルランド (the) |
| アプリ情報ページ | [https://pushsecurity.com/kb/10004/](https://pushsecurity.com/kb/10004/) |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | Paas |
| アプリで使用するホスティング クラウド プロバイダーはどれですか? | Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて、Push Security によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリによって処理されるデータは何ですか? | プッシュは、顧客の勤務時間を処理して、顧客が作業しているときにアラートを提供します。  |
| アプリは TLS 1.1 以降をサポートしていますか? | はい |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データは格納されますか? | はい |
| データベースに格納されているデータは何ですか? | プッシュは、顧客の勤務時間を保存して、顧客が作業しているときにアラートを提供します。  |
| 基になるインファ構造が Microsoft 顧客データを処理または格納する場合、このデータは地理的にどこに保存されますか? | アイルランド |
| データの借用と廃棄プロセスが確立されていますか? | はい |
| アカウントの終了後、データはどのくらいの期間保持されますか? | 保持されない |
| データ アクセス管理プロセスが確立されていますか? | はい |
| 顧客データまたは顧客コンテンツをサード パーティまたはサブプロセッサに転送しますか? | X |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

| **Information** | **Response** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行していますか? | はい |
| バックアップと復元の戦略など、文書化されたディザスター リカバリー計画はアプリに含まれていますか? | はい |
| お使いの環境では、従来のマルウェア対策保護またはアプリケーション制御が使用されていますか? | TraditionalAntiMalware、ApplicationControls |
| セキュリティの脆弱性をインデントおよびリスク ランク付けするための確立されたプロセスはありますか? | はい |
| パッチを適用するためのサービス レベル アグリーメント (SLA) を管理するポリシーはありますか? | はい |
| パッチ ポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | はい |
| お使いの環境にサポートされていないオペレーティング システムまたはソフトウェアはありますか? | X |
| アプリと、それをサポートするインファ構造に対して四半期ごとの脆弱性スキャンを行いますか? | 不要 |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | X |
| 変更要求を運用環境にデプロイする前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスはありますか? | はい |
| 追加のユーザーは、元の開発者によって運用環境に送信されたすべてのコード変更要求を確認して承認していますか? | はい |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | はい |
| 多要素認証 (MFA) が有効になっているのは次のとおりです。 | CodeRepositories、DNSManagement、Credential |
| 従業員アカウントのプロビジョニング、変更、削除のための確立されたプロセスはありますか? | はい |
| アプリをサポートするネットワーク境界の境界に侵入検出と防止 (IDPS) ソフトウェアがデプロイされていますか? | はい |
| アプリをサポートするすべてのシステム コンポーネントにイベント ログ記録を設定していますか? | はい |
| すべてのログは、潜在的なセキュリティ イベントを検出するために、人間または自動化されたツールによって定期的に確認されますか? | はい |
| セキュリティ イベントが検出されると、トリアージのために従業員にアラートが自動的に送信されますか? | はい |
| 正式な情報セキュリティ リスク管理プロセスが確立されていますか? | はい |
| 正式なセキュリティ インシデント対応プロセスが文書化され、確立されていますか? | はい |
| 検出から 72 時間以内に、アプリまたはサービスのデータ侵害を監督機関や違反の影響を受けた個人に報告しますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Response** |
|:----------------|:-------------|
| アプリは、医療保険の可搬性と会計法 (HIPAA) に準拠していますか? | 該当なし |
| アプリは Health Information Trust Alliance、Common Security Framework (HITRUST CSF) に準拠していますか? | 該当なし |
| アプリはサービス組織コントロール (SOC 1) に準拠していますか? | 該当なし |
| アプリはサービス組織コントロール (SOC 2) に準拠していますか? | 不要 |
| アプリはサービス組織コントロール (SOC 3) に準拠していますか? | X |
| アプリとそのサポート環境に対して、年間 PCI DSS 評価を実行していますか? | 該当なし |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | 不要 |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | 不要 |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | X |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | 不要 |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | X |
| アプリは家族教育の権利とプライバシーに関する法律 (FERPA) に準拠していますか? | 該当なし |
| アプリは、子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | 該当なし |
| アプリはSarbanes-Oxley法 (SOX) に準拠していますか? | 該当なし |
| アプリは NIST 800-171 に準拠していますか? | 該当なし |
| アプリは Cloud Security Alliance (CSA Star) の認定を受けていますか? | 不要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **応答** |
|:----------------|:-------------|
| GDPR またはその他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | はい |
| アプリには、顧客データの収集、使用、共有、および格納方法を説明する外部向けのプライバシーに関する通知がありますか? | はい |
| プライバシー ポリシーの URL | https://pushsecurity.com/legal/privacy/ |
| アプリは、法的影響や同様の影響を及ぼす可能性のあるプロファイリングを含め、自動化された意思決定を実行しますか? | 不要 |
| アプリは、プライバシーに関する通知 (マーケティング、分析など) に記載されていない第 2 の目的で顧客データを処理しますか? | X |
| 機密データの特別なカテゴリ (例: 人種的または民族的起源、ポリティカルオピニオン、宗教または哲学的信念、遺伝子または生体認証データ、健康データ)、または違反通知法の対象となるデータのカテゴリを処理しますか? | 不要 |
| アプリは未成年者 (16 歳未満の個人) からデータを収集または処理しますか? | X |
| アプリには、要求に応じて個人の個人データを削除する機能はありますか? | はい |
| アプリには、要求に応じて個人の個人データの処理を制限または制限する機能がありますか? | はい |
| アプリは個人に個人データを修正または更新する機能を提供しますか? | 不要 |
| アプリの個人データの処理に関連するリスクを特定するために、定期的なデータ セキュリティとプライバシーのレビュー (データ保護影響評価やプライバシー リスク評価など) が実行されますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリケーションは、シングル サインオン、API アクセスなどのために Microsoft Identity Platform (Azure AD) と統合されますか? | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか? | はい |
| アプリは、最新バージョンの MSAL (Microsoft Authentication Library) または Microsoft Identity Web を認証に使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | X |
| アプリは継続的アクセス評価 (CAE) をサポートしていますか? | 不要 |
| アプリは、コードに資格情報を格納していますか? | X |
| Microsoft 365 用のアプリとアドインでは、Microsoft Graph の外部で追加の Microsoft API が使用される場合があります。 アプリまたはアドインは、追加の Microsoft API を使用していますか? | X |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph を使用したデータ アクセス

>|   **Graph のアクセス許可**  | **アクセス許可の種類** |          **妥当性**          | **Azure AD アプリ ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Channel.ReadBasic.All | アプリケーション | ボットのインストールを容易にするチャネルを一覧表示する  | [4ed8651a-5a01-44f0-abdf-536bbc441c02](../azure/4ed8651a-5a01-44f0-abdf-536bbc441c02.md) |
>| MailboxSettings.Read | アプリケーション | 時間外にメッセージを送信しないように、顧客の勤務時間にクエリを実行する | [4ed8651a-5a01-44f0-abdf-536bbc441c02](../azure/4ed8651a-5a01-44f0-abdf-536bbc441c02.md) |
>| Team.ReadBasic.All | アプリケーション | ボットのインストールを簡単にするためにチームを一覧表示する  | [4ed8651a-5a01-44f0-abdf-536bbc441c02](../azure/4ed8651a-5a01-44f0-abdf-536bbc441c02.md) |
>| TeamsAppInstallation.ReadWriteSelfForTeam.All | アプリケーション | ボットがチームに対してそれ自体をインストールできるようにする | [4ed8651a-5a01-44f0-abdf-536bbc441c02](../azure/4ed8651a-5a01-44f0-abdf-536bbc441c02.md) |
>| TeamsAppInstallation.ReadWriteSelfForUser.All | アプリケーション | ボットがユーザーに対してそれ自体をインストールできるようにする | [4ed8651a-5a01-44f0-abdf-536bbc441c02](../azure/4ed8651a-5a01-44f0-abdf-536bbc441c02.md) |
>| User.Read.All | アプリケーション | メッセージを送信できるようにユーザーを一覧表示する | [4ed8651a-5a01-44f0-abdf-536bbc441c02](../azure/4ed8651a-5a01-44f0-abdf-536bbc441c02.md) |

>このアプリケーションには、追加の API はありません。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

