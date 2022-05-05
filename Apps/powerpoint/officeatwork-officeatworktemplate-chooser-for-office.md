---
title: Office テンプレート選択ツールの概要
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 01/25/2022
ms.topic: article
ms.service: attestation
certification_type: certified
description: officeatwork |で使用可能なすべてのセキュリティ情報とコンプライアンス情報Office用のテンプレート 選択ツール、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 2b58f6634c81405b9aef0c8d984dc4c16501b2b9
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225671"
---
# <a name="office-template-chooser-overview"></a>Office テンプレート選択ツールの概要

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2022 年 1 月 24 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104380050" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Officeatwork から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | officeatwork - Office用テンプレート選択子 |
| ID | WA104380050 |
| サポートされているOffice 365 クライアント | iPad、Excel 2016 以降の Mac、Excel 2013 以降、Windows、Excel on the web、iPad上の Word、Mac でのWord 2016以降、Word on the web、Word 2013 以降のExcelWindows、iPadでのPowerPoint、Mac でのPowerPoint 2016以降、PowerPoint on the web、Windows PowerPoint 2013 以降、Project 2016 以降Windows |
| パートナー会社名 | officeatwork |
| 会社の Web サイト | [https://www.officeatwork.com](https://www.officeatwork.com) |
| アプリの使用条件 | [https://links.officeatwork.com/officeatwork-licenseterms](https://links.officeatwork.com/officeatwork-licenseterms) |
| アプリのコア機能 | Office、Teams、SharePoint Online、その他のアプリで一元的に共有されたテンプレートにアクセスします。 |
| 会社の本社の場所 | スイス |
| アプリ情報ページ | [https://links.officeatwork.com/templatechooser](https://links.officeatwork.com/templatechooser) |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | Paas |
| アプリで使用するホスティング クラウド プロバイダーはどれですか? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する officeatwork によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリによって処理されるデータは何ですか? | 収集済み: Microsoft テナント ID、ユーザー Azure AD オブジェクト ID。データの処理は、付与されたアクセス許可に依存し、クライアント側で実行されます。 Officeatwork によって制御される一時的、サーバーレス、信頼された PaaS Azure サービスによって処理されるのは、アクセス許可とサインイン フローに必要なデータだけです。 |
| アプリは TLS 1.1 以降をサポートしていますか? | はい |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データは格納されますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行していますか? | はい |
| バックアップと復元の戦略など、文書化されたディザスター リカバリー計画はアプリに含まれていますか? | はい |
| お使いの環境では、従来のマルウェア対策保護またはアプリケーション制御が使用されていますか? | ApplicationControls |
| セキュリティの脆弱性をインデントおよびリスク ランク付けするための確立されたプロセスはありますか? | はい |
| パッチを適用するためのサービス レベル アグリーメント (SLA) を管理するポリシーはありますか? | はい |
| パッチ ポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | はい |
| お使いの環境にサポートされていないオペレーティング システムまたはソフトウェアはありますか? | いいえ |
| アプリと、それをサポートするインファ構造に対して四半期ごとの脆弱性スキャンを行いますか? | はい |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | はい |
| 変更要求を運用環境にデプロイする前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスはありますか? | はい |
| 追加のユーザーは、元の開発者によって運用環境に送信されたすべてのコード変更要求を確認して承認していますか? | はい |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | はい |
| 多要素認証 (MFA) が有効になっているのは次のとおりです。 | CodeRepositories、DNSManagement、Credential |
| 従業員アカウントのプロビジョニング、変更、削除のための確立されたプロセスはありますか? | はい |
| アプリをサポートするネットワーク境界の境界に侵入検出と防止 (IDPS) ソフトウェアがデプロイされていますか? | 該当なし |
| アプリをサポートするすべてのシステム コンポーネントにイベント ログ記録を設定していますか? | はい |
| すべてのログは、潜在的なセキュリティ イベントを検出するために、人間または自動化されたツールによって定期的に確認されますか? | はい |
| セキュリティ イベントが検出されると、トリアージのために従業員にアラートが自動的に送信されますか? | はい |
| 正式な情報セキュリティ リスク管理プロセスが確立されていますか? | はい |
| 正式なセキュリティ インシデント対応プロセスが文書化され、確立されていますか? | はい |
| 検出から 72 時間以内に、アプリまたはサービスのデータ侵害を監督機関や違反の影響を受けた個人に報告しますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリは、医療保険の可搬性と会計法 (HIPAA) に準拠していますか? | 該当なし |
| アプリは Health Information Trust Alliance、Common Security Framework (HITRUST CSF) に準拠していますか? | 該当なし |
| アプリはサービス組織コントロール (SOC 1) に準拠していますか? | 該当なし |
| アプリはサービス組織コントロール (SOC 2) に準拠していますか? | いいえ |
| アプリはサービス組織コントロール (SOC 3) に準拠していますか? | いいえ |
| アプリとそのサポート環境に対して、年間 PCI DSS 評価を実行していますか? | 該当なし |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | いいえ |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | 該当なし |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | いいえ |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | いいえ |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | いいえ |
| アプリは家族教育の権利とプライバシーに関する法律 (FERPA) に準拠していますか? | 該当なし |
| アプリは、子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | 該当なし |
| アプリはSarbanes-Oxley法 (SOX) に準拠していますか? | 該当なし |
| アプリは NIST 800-171 に準拠していますか? | 該当なし |
| アプリは Cloud Security Alliance (CSA Star) の認定を受けていますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **応答** |
|:----------------|:-------------|
| GDPR またはその他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | はい |
| アプリには、顧客データの収集、使用、共有、および格納方法を説明する外部向けのプライバシーに関する通知がありますか? | はい |
| プライバシー ポリシーの URL | https://links.officeatwork.com/officeatwork-privacypolicy |
| アプリは、法的影響や同様の影響を及ぼす可能性のあるプロファイリングを含め、自動化された意思決定を実行しますか? | いいえ |
| アプリは、プライバシーに関する通知 (マーケティング、分析など) に記載されていない第 2 の目的で顧客データを処理しますか? | いいえ |
| 機密データの特別なカテゴリ (例: 人種的または民族的起源、ポリティカルオピニオン、宗教または哲学的信念、遺伝子または生体認証データ、健康データ)、または違反通知法の対象となるデータのカテゴリを処理しますか? | いいえ |
| アプリは未成年者 (16 歳未満の個人) からデータを収集または処理しますか? | いいえ |
| アプリには、要求に応じて個人の個人データを削除する機能はありますか? | はい |
| アプリには、要求に応じて個人の個人データの処理を制限または制限する機能がありますか? | はい |
| アプリは個人に個人データを修正または更新する機能を提供しますか? | はい |
| アプリの個人データの処理に関連するリスクを特定するために、定期的なデータ セキュリティとプライバシーのレビュー (データ保護影響評価やプライバシー リスク評価など) が実行されますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリケーションは、シングル サインオン、API アクセスなどのために Microsoft Identity Platform (Azure AD) と統合されますか? | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか? | はい |
| アプリは、最新バージョンの MSAL (Microsoft Authentication Library) または Microsoft Identity Web を認証に使用していますか? | 該当なし |
| アプリで上記のライブラリのいずれかを使用していない場合、どの認証ライブラリまたはライブラリが使用されますか? |  |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | セキュリティの既定値 |
| アプリは継続的アクセス評価 (CAE) をサポートしていますか? | はい |
| アプリは、コードに資格情報を格納していますか? | いいえ |
| Microsoft 365用のアプリとアドインでは、Microsoft Graphの外部で追加の Microsoft API が使用される場合があります。 アプリまたはアドインは、追加の Microsoft API を使用していますか? | はい |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

>|   **Graphアクセス許可**  | **アクセス許可の種類** |          **妥当性**          | **Azure AD アプリ ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Files.ReadWrite.All | 委任 | お気に入りとOneDrive機能を有効にする | [dae2eacf-3eb5-4440-baff-984fbd5cae68](../azure/dae2eacf-3eb5-4440-baff-984fbd5cae68.md) |
>| Group.ReadWrite.All | 委任 | Teams機能を有効にする | [dae2eacf-3eb5-4440-baff-984fbd5cae68](../azure/dae2eacf-3eb5-4440-baff-984fbd5cae68.md) |
>| GroupMember.Read.All | 委任 | Teams機能を有効にする | [dae2eacf-3eb5-4440-baff-984fbd5cae68](../azure/dae2eacf-3eb5-4440-baff-984fbd5cae68.md) |
>| Sites.Read.All | 委任 | SharePointに格納されているユーザー テンプレート ファイルを読み取る | [dae2eacf-3eb5-4440-baff-984fbd5cae68](../azure/dae2eacf-3eb5-4440-baff-984fbd5cae68.md) |
>| User.Read | 委任 | サインインしているユーザーの表示を有効にする | [dae2eacf-3eb5-4440-baff-984fbd5cae68](../azure/dae2eacf-3eb5-4440-baff-984fbd5cae68.md) |
>| User.Read.All | 委任 | ユーザー プロパティの表示を有効にする | [dae2eacf-3eb5-4440-baff-984fbd5cae68](../azure/dae2eacf-3eb5-4440-baff-984fbd5cae68.md) |
>| offline_access | 委任 | 古いOffice ホストの自動サインインを有効にする | [dae2eacf-3eb5-4440-baff-984fbd5cae68](../azure/dae2eacf-3eb5-4440-baff-984fbd5cae68.md) |
>| openid | 委任 | サインインを有効にする | [dae2eacf-3eb5-4440-baff-984fbd5cae68](../azure/dae2eacf-3eb5-4440-baff-984fbd5cae68.md) |
>| profile | 委任 | サインインを有効にする | [dae2eacf-3eb5-4440-baff-984fbd5cae68](../azure/dae2eacf-3eb5-4440-baff-984fbd5cae68.md) |

>このアプリケーションには、追加の API はありません。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

