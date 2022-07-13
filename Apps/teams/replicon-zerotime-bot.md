---
title: Replicon による ZeroTime Bot のアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/06/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: ZeroTime Bot で使用可能なすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 35065d4157b4a4870f76344189781e9ba3d6599b
ms.sourcegitcommit: 1d78b47ae32dd7ee29fb848e04ac0c5090d6b41c
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/13/2022
ms.locfileid: "66765161"
---
# <a name="zerotime-bot"></a>ZeroTime ボット

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 12 月 8 日</p>

* <a href="https://teams.microsoft.com/l/app/4db812e1-4d29-44e4-b72e-9654c0c91ce4" target="_blank">Teams ストアで表示する</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003717" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Replicon から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | ZeroTime ボット |
| ID | WA200003717 |
| サポートされているOffice 365 クライアント | Microsoft Teams |
| パートナー会社名 | Replicon |
| 会社の Web サイト | [https://www.replicon.com](https://www.replicon.com) |
| アプリの使用条件 | [https://www.replicon.com/terms-and-conditions/](https://www.replicon.com/terms-and-conditions/) |
| アプリのコア機能 | ゼロ タイム ボットを使用すると、ユーザーはボットとチャットすることで、Replicon タイムシートを直接設定できます。 |
| 会社の本社の場所 | カナダ |
| アプリ情報ページ | |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | Iaas |
| アプリで使用するホスティング クラウド プロバイダーはどれですか? | Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する Replicon によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | 必要 |
| アプリによって処理されるデータは何ですか? | ユーザー プロファイル データ、時刻データ |
| アプリは TLS 1.1 以降をサポートしていますか? | 必要 |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データは格納されますか? | 不要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

| **Information** | **Response** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行していますか? | 必要 |
| バックアップと復元の戦略など、文書化されたディザスター リカバリー計画はアプリに含まれていますか? | 必要 |
| お使いの環境では、従来のマルウェア対策保護またはアプリケーション制御が使用されていますか? | ApplicationControls |
| セキュリティの脆弱性をインデントおよびリスク ランク付けするための確立されたプロセスはありますか? | 必要 |
| パッチを適用するためのサービス レベル アグリーメント (SLA) を管理するポリシーはありますか? | 必要 |
| パッチ ポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | 必要 |
| お使いの環境にサポートされていないオペレーティング システムまたはソフトウェアはありますか? | 不要 |
| アプリと、それをサポートするインファ構造に対して四半期ごとの脆弱性スキャンを行いますか? | 必要 |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | 必要 |
| 変更要求を運用環境にデプロイする前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスはありますか? | 必要 |
| 追加のユーザーは、元の開発者によって運用環境に送信されたすべてのコード変更要求を確認して承認していますか? | 必要 |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | 必要 |
| 多要素認証 (MFA) が有効になっているのは次のとおりです。 | CodeRepositories、Credential、DNSManagement |
| 従業員アカウントのプロビジョニング、変更、削除のための確立されたプロセスはありますか? | 必要 |
| アプリをサポートするネットワーク境界の境界に侵入検出と防止 (IDPS) ソフトウェアがデプロイされていますか? | 必要 |
| アプリをサポートするすべてのシステム コンポーネントにイベント ログ記録を設定していますか? | 必要 |
| すべてのログは、潜在的なセキュリティ イベントを検出するために、人間または自動化されたツールによって定期的に確認されますか? | 必要 |
| セキュリティ イベントが検出されると、トリアージのために従業員にアラートが自動的に送信されますか? | 必要 |
| 正式な情報セキュリティ リスク管理プロセスが確立されていますか? | 必要 |
| 正式なセキュリティ インシデント対応プロセスが文書化され、確立されていますか? | 必要 |
| 検出から 72 時間以内に、アプリまたはサービスのデータ侵害を監督機関や違反の影響を受けた個人に報告しますか? | 必要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Response** |
|:----------------|:-------------|
| アプリは、医療保険の可搬性と会計法 (HIPAA) に準拠していますか? | 該当なし |
| アプリは Health Information Trust Alliance、Common Security Framework (HITRUST CSF) に準拠していますか? | 該当なし |
| アプリはサービス組織コントロール (SOC 1) に準拠していますか? | 該当なし |
| アプリはサービス組織コントロール (SOC 2) に準拠していますか? | 不要 |
| アプリはサービス組織コントロール (SOC 3) に準拠していますか? | いいえ |
| アプリとそのサポート環境に対して、年間 PCI DSS 評価を実行していますか? | 該当なし |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | 不要 |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | 該当なし |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | 不要 |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | 不要 |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | 不要 |
| アプリは家族教育の権利とプライバシーに関する法律 (FERPA) に準拠していますか? | 該当なし |
| アプリは、子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | 該当なし |
| アプリはSarbanes-Oxley法 (SOX) に準拠していますか? | 該当なし |
| アプリは NIST 800-171 に準拠していますか? | 該当なし |
| アプリは Cloud Security Alliance (CSA Star) の認定を受けていますか? | 不要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Response** |
|:----------------|:-------------|
| GDPR またはその他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | はい |
| アプリには、顧客データの収集、使用、共有、および格納方法を説明する外部向けのプライバシーに関する通知がありますか? | 不要 |
| アプリは、法的影響や同様の影響を及ぼす可能性のあるプロファイリングを含め、自動化された意思決定を実行しますか? | いいえ |
| アプリは、プライバシーに関する通知 (マーケティング、分析など) に記載されていない第 2 の目的で顧客データを処理しますか? | いいえ |
| 機密データの特別なカテゴリ (例: 人種的または民族的起源、ポリティカルオピニオン、宗教または哲学的信念、遺伝子または生体認証データ、健康データ)、または違反通知法の対象となるデータのカテゴリを処理しますか? | いいえ |
| アプリは未成年者 (16 歳未満の個人) からデータを収集または処理しますか? | いいえ |
| アプリには、要求に応じて個人の個人データを削除する機能はありますか? | 該当なし |
| アプリには、要求に応じて個人の個人データの処理を制限または制限する機能がありますか? | 該当なし |
| アプリは個人に個人データを修正または更新する機能を提供しますか? | 該当なし |
| アプリの個人データの処理に関連するリスクを特定するために、定期的なデータ セキュリティとプライバシーのレビュー (データ保護影響評価やプライバシー リスク評価など) が実行されますか? | 該当なし |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| アプリケーションは、シングル サインオン、API アクセスなどのために Microsoft Identity Platform (Azure AD) と統合されますか? | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか? | 必要 |
| アプリは、最新バージョンの MSAL (Microsoft Authentication Library) または Microsoft Identity Web を認証に使用していますか? | 該当なし |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリは継続的アクセス評価 (CAE) をサポートしていますか? | いいえ |
| アプリは、コードに資格情報を格納していますか? | いいえ |
| Microsoft 365 用のアプリとアドインでは、Microsoft Graph の外部で追加の Microsoft API が使用される場合があります。 アプリまたはアドインは、追加の Microsoft API を使用していますか? | いいえ |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph を使用したデータ アクセス

>|   **Graph のアクセス許可**  | **アクセス許可の種類** |          **妥当性**          | **Azure AD アプリ ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| User.Read.All | アプリケーション | ユーザーのメールを取得し、Replicon のシステム内のユーザーにマップして、チャット メッセージを Replicon のアプリケーションにプッシュする | [4db812e1-4d29-44e4-b72e-9654c0c91ce4](../azure/4db812e1-4d29-44e4-b72e-9654c0c91ce4.md) |

>このアプリケーションには、追加の API はありません。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

