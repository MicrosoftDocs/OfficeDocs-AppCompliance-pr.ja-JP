---
title: Heedify による Heedify のアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 11/24/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: Heedify で使用可能なすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 9f1880c7e9478ce05b8ffe38a95c96a5a4d2d5a4
ms.sourcegitcommit: 5e2cd59a54fc018a6df761b00c18e3ba592d9dba
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/15/2022
ms.locfileid: "64877274"
---
# <a name="heedify"></a>Heedify

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 8 月 2 日</p>

* <a href="https://teams.microsoft.com/l/app/0587c0da-1445-4875-a9f3-2b8083b7338f" target="_blank">Teams ストアで表示する</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003512" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Heedify から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Heedify |
| ID | WA200003512 |
| サポートされているOffice 365 クライアント | Microsoft Teams |
| パートナー会社名 | Heedify |
| 会社の Web サイト | [https://heedify.io](https://heedify.io) |
| アプリの使用条件 | [https://heedify.io/terms](https://heedify.io/terms) |
| アプリのコア機能 | Microsoft Teams用のネイティブ 受付スタッフとコール センター エージェント。 |
| 会社の本社の場所 | フランス |
| アプリ情報ページ | |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | Paas |
| アプリで使用するホスティング クラウド プロバイダーはどれですか? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて Heedify によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリによって処理されるデータは何ですか? | プレゼンス情報と通話の詳細 (コール センターから)  |
| アプリは TLS 1.1 以降をサポートしていますか? | はい |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データは格納されますか? | はい |
| データベースに格納されているデータは何ですか? | プレゼンス情報と通話の詳細 (コール センターから)  |
| 基になるインファ構造が Microsoft 顧客データを処理または格納する場合、このデータは地理的にどこに保存されますか? | アイルランド |
| データの借用と廃棄プロセスが確立されていますか? | はい |
| アカウントの終了後、データはどのくらいの期間保持されますか? | 30 日間未満 |
| データ アクセス管理プロセスが確立されていますか? | はい |
| 顧客データまたは顧客コンテンツをサード パーティまたはサブプロセッサに転送しますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行していますか? | いいえ |
| バックアップと復元の戦略など、文書化されたディザスター リカバリー計画はアプリに含まれていますか? | はい |
| お使いの環境では、従来のマルウェア対策保護またはアプリケーション制御が使用されていますか? | TraditionalAntiMalware |
| セキュリティの脆弱性をインデントおよびリスク ランク付けするための確立されたプロセスはありますか? | いいえ |
| パッチを適用するためのサービス レベル アグリーメント (SLA) を管理するポリシーはありますか? | はい |
| パッチ ポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | はい |
| お使いの環境にサポートされていないオペレーティング システムまたはソフトウェアはありますか? | いいえ |
| アプリと、それをサポートするインファ構造に対して四半期ごとの脆弱性スキャンを行いますか? | いいえ |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | はい |
| 変更要求を運用環境にデプロイする前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスはありますか? | はい |
| 追加のユーザーは、元の開発者によって運用環境に送信されたすべてのコード変更要求を確認して承認していますか? | はい |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | はい |
| 多要素認証 (MFA) が有効になっているのは次のとおりです。 | CodeRepositories、DNSManagement、Credential |
| 従業員アカウントのプロビジョニング、変更、削除のための確立されたプロセスはありますか? | はい |
| アプリをサポートするネットワーク境界の境界に侵入検出と防止 (IDPS) ソフトウェアがデプロイされていますか? | N/A |
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
| アプリは、医療保険の可搬性と会計法 (HIPAA) に準拠していますか? | N/A |
| アプリは Health Information Trust Alliance、Common Security Framework (HITRUST CSF) に準拠していますか? | N/A |
| アプリはサービス組織コントロール (SOC 1) に準拠していますか? | N/A |
| アプリはサービス組織コントロール (SOC 2) に準拠していますか? | いいえ |
| アプリはサービス組織コントロール (SOC 3) に準拠していますか? | いいえ |
| アプリとそのサポート環境に対して、年間 PCI DSS 評価を実行していますか? | N/A |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | いいえ |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | N/A |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | いいえ |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | いいえ |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | いいえ |
| アプリは家族教育の権利とプライバシーに関する法律 (FERPA) に準拠していますか? | N/A |
| アプリは、子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | N/A |
| アプリはSarbanes-Oxley法 (SOX) に準拠していますか? | N/A |
| アプリは NIST 800-171 に準拠していますか? | N/A |
| アプリは Cloud Security Alliance (CSA Star) の認定を受けていますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **応答** |
|:----------------|:-------------|
| GDPR またはその他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | はい |
| アプリには、顧客データの収集、使用、共有、および格納方法を説明する外部向けのプライバシーに関する通知がありますか? | はい |
| プライバシー ポリシーの URL | https://heedify.io/privacy |
| アプリは、法的影響や同様の影響を及ぼす可能性のあるプロファイリングを含め、自動化された意思決定を実行しますか? | いいえ |
| アプリは、プライバシーに関する通知 (マーケティング、分析など) に記載されていない第 2 の目的で顧客データを処理しますか? | いいえ |
| 機密データの特別なカテゴリ (例: 人種的または民族的起源、ポリティカルオピニオン、宗教または哲学的信念、遺伝子または生体認証データ、健康データ)、または違反通知法の対象となるデータのカテゴリを処理しますか? | いいえ |
| アプリは未成年者 (16 歳未満の個人) からデータを収集または処理しますか? | いいえ |
| アプリには、要求に応じて個人の個人データを削除する機能はありますか? | いいえ |
| アプリには、要求に応じて個人の個人データの処理を制限または制限する機能がありますか? | いいえ |
| アプリは個人に個人データを修正または更新する機能を提供しますか? | はい |
| アプリの個人データの処理に関連するリスクを特定するために、定期的なデータ セキュリティとプライバシーのレビュー (データ保護影響評価やプライバシー リスク評価など) が実行されますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリケーションは、シングル サインオン、API アクセスなどのために Microsoft Identity Platform (Azure AD) と統合されますか? | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか? | はい |
| アプリは、最新バージョンの MSAL (Microsoft Authentication Library) または Microsoft Identity Web を認証に使用していますか? | いいえ |
| アプリで上記のライブラリのいずれかを使用していない場合、どの認証ライブラリまたはライブラリが使用されますか? | MSAL では ADFS での認証はまだサポートされていないため、ADAL (Javascript) を使用しています  |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリは継続的アクセス評価 (CAE) をサポートしていますか? | いいえ |
| アプリは、コードに資格情報を格納していますか? | いいえ |
| Microsoft 365用のアプリとアドインでは、Microsoft Graphの外部で追加の Microsoft API が使用される場合があります。 アプリまたはアドインは、追加の Microsoft API を使用していますか? | いいえ |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

>|   **Graphアクセス許可**  | **アクセス許可の種類** |          **妥当性**          | **Azure AD アプリ ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Calendars.Read | 委任 | 受付担当者は、電話を転送したり、電話で顧客と情報を共有したりする前に、ユーザーの予定表を確認する必要があります | [f3ad2154-7e10-4730-a055-8852ced42d47](../azure/f3ad2154-7e10-4730-a055-8852ced42d47.md) |
>| Contacts.ReadWrite | 委任 | アプリケーションは、ユーザー (エージェント) に連絡先を追加し、連絡先も読み取ることができる必要があります。  | [f3ad2154-7e10-4730-a055-8852ced42d47](../azure/f3ad2154-7e10-4730-a055-8852ced42d47.md) |
>| Contacts.ReadWrite.Shared | 委任 | アプリケーションは、他のユーザー (エージェント) と共有連絡先を追加し、共有連絡先も読み取ることができる必要があります  | [f3ad2154-7e10-4730-a055-8852ced42d47](../azure/f3ad2154-7e10-4730-a055-8852ced42d47.md) |
>| Presence.Read.All | 委任 | 通話を適切に管理し、通話転送の場合は特に連絡先を管理するために、連絡先センター エージェントにプレゼンス情報が必要です。  | [f3ad2154-7e10-4730-a055-8852ced42d47](../azure/f3ad2154-7e10-4730-a055-8852ced42d47.md) |
>| User.Read.All | 委任 | 連絡先を管理するには、ログに記録されたユーザーがユーザーを閲覧し、出発や上司などの情報を読み取ることができる必要があります (受付の場合)  | [f3ad2154-7e10-4730-a055-8852ced42d47](../azure/f3ad2154-7e10-4730-a055-8852ced42d47.md) |

>このアプリケーションには、追加の API はありません。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

