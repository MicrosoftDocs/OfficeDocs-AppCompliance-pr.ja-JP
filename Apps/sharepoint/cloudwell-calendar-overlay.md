---
title: Cloudwell によるカレンダー オーバーレイのアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/10/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: カレンダー オーバーレイに使用できるすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: e98ea9e1131121d82c9b8a41eb336000c464e8c6
ms.sourcegitcommit: 5e2cd59a54fc018a6df761b00c18e3ba592d9dba
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/15/2022
ms.locfileid: "64877374"
---
# <a name="calendar-overlay"></a>予定表オーバーレイ

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2022 年 3 月 10 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA200003806" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Cloudwell から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | 予定表オーバーレイ |
| ID | WA200003806 |
| サポートされているOffice 365 クライアント | SharePoint 2016 以降 |
| パートナー会社名 | Cloudwell |
| 会社の Web サイト | [https://cloudwell.io](https://cloudwell.io) |
| アプリの使用条件 | [https://cwlicensingprod.blob.core.windows.net/termsofuse/St...](https://cwlicensingprod.blob.core.windows.net/termsofuse/StandardContractMarch2019.pdf) |
| アプリのコア機能 | 予定表オーバーレイ Web パーツを使用すると、すべての Microsoft SharePoint、Planner、Exchange イベントを 1 か所で表示できます。 |
| 会社の本社の場所 | 米国 オブ アメリカ |
| アプリ情報ページ | [https://cloudwell.io/products/calendar-overlay](https://cloudwell.io/products/calendar-overlay) |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | Iaas |
| アプリで使用するホスティング クラウド プロバイダーはどれですか? | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて Cloudwell から提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリによって処理されるデータは何ですか? | ユーザーの電子メール アドレス、ユーザー テナント ID |
| アプリは TLS 1.1 以降をサポートしていますか? | はい |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データは格納されますか? | はい |
| データベースに格納されているデータは何ですか? | ユーザーの電子メール アドレス、ユーザー テナント ID |
| 基になるインファ構造が Microsoft 顧客データを処理または格納する場合、このデータは地理的にどこに保存されますか? | 米国 オブ アメリカ |
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
| アプリで年間侵入テストを実行していますか? | はい |
| バックアップと復元の戦略など、文書化されたディザスター リカバリー計画はアプリに含まれていますか? | いいえ |
| お使いの環境では、従来のマルウェア対策保護またはアプリケーション制御が使用されていますか? | TraditionalAntiMalware、ApplicationControls |
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
| セキュリティ イベントが検出されると、トリアージのために従業員にアラートが自動的に送信されますか? | いいえ |
| 正式な情報セキュリティ リスク管理プロセスが確立されていますか? | いいえ |
| 正式なセキュリティ インシデント対応プロセスが文書化され、確立されていますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリは、医療保険の可搬性と会計法 (HIPAA) に準拠していますか? | はい |
| アプリは Health Information Trust Alliance、Common Security Framework (HITRUST CSF) に準拠していますか? | はい |
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
| GDPR またはその他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリケーションは、シングル サインオン、API アクセスなどのために Microsoft Identity Platform (Azure AD) と統合されますか? | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか? | はい |
| アプリは、最新バージョンの MSAL (Microsoft Authentication Library) または Microsoft Identity Web を認証に使用していますか? | はい |
| アプリで上記のライブラリのいずれかを使用していない場合、どの認証ライブラリまたはライブラリが使用されますか? |  |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリは継続的アクセス評価 (CAE) をサポートしていますか? | いいえ |
| アプリは、コードに資格情報を格納していますか? | いいえ |
| Microsoft 365用のアプリとアドインでは、Microsoft Graphの外部で追加の Microsoft API が使用される場合があります。 アプリまたはアドインは、追加の Microsoft API を使用していますか? | はい |

>このアプリケーションでは、Microsoft Graphは使用されません。

>このアプリケーションには、追加の API はありません。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

