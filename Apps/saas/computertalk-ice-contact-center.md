---
title: ComputerTalk による Ice Contact Center のアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 07/07/2022
ms.topic: article
ms.service: attestation
certification_type: certified
description: ice Contact Center で使用可能なすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust-certification
ms.openlocfilehash: 3624609e62383a44e9dd6eba04d68a6bcc356685
ms.sourcegitcommit: 7902a8fe5a55d715023f34ea1ab987b4d715a4f7
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/10/2022
ms.locfileid: "66707344"
---
# <a name="ice-contact-center"></a>ice Contact Center

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2022 年 2 月 14 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/computertalk.ice-contact-center" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

ComputerTalk から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | ice Contact Center |
| ID | computertalk.ice-contact-center |
| パートナー会社名 | ComputerTalk |
| 会社の Web サイト | [https://www.computer-talk.com](https://www.computer-talk.com) |
| アプリの使用条件 | [https://www.computer-talk.com/product/enterprise-contact-ce...](https://www.computer-talk.com/product/enterprise-contact-center/ice-contact-center-for-teams) |
| アプリのコア機能 | ice は、通話のルーティング、録音、監視、レポートなど、サービス機能としてコンタクト センターを提供します。 |
| 会社の本社の場所 | カナダ |
| アプリ情報ページ | [https://www.computer-talk.com/product/enterprise-contact-ce...](https://www.computer-talk.com/product/enterprise-contact-center/ice-contact-center-for-teams) |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | IsvHosted |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールに関する ComputerTalk によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリによって処理されるデータは何ですか? | AzureADGuid (アカウントのリンク)。  メール アドレスと電話番号は、AAD からインポートできます。 |
| アプリは TLS 1.1 以降をサポートしていますか? | はい |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データは格納されますか? | はい |
| データベースに格納されているデータは何ですか? | AzureADGuid (アカウントのリンク)。  メール アドレスと電話番号は、AAD からインポートできます。 |
| 基になるインファ構造が Microsoft 顧客データを処理または格納する場合、このデータは地理的にどこに保存されますか? | カナダ |
| データの借用と廃棄プロセスが確立されていますか? | はい |
| アカウントの終了後、データはどのくらいの期間保持されますか? | 30 日間未満 |
| データ アクセス管理プロセスが確立されていますか? | はい |
| 顧客データまたは顧客コンテンツをサード パーティまたはサブプロセッサに転送しますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

| **Information** | **Response** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行していますか? | はい |
| バックアップと復元の戦略など、文書化されたディザスター リカバリー計画はアプリに含まれていますか? | はい |
| お使いの環境では、従来のマルウェア対策保護またはアプリケーション制御が使用されていますか? | TraditionalAntiMalware |
| セキュリティの脆弱性をインデントおよびリスク ランク付けするための確立されたプロセスはありますか? | はい |
| パッチを適用するためのサービス レベル アグリーメント (SLA) を管理するポリシーはありますか? | はい |
| パッチ ポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | はい |
| お使いの環境にサポートされていないオペレーティング システムまたはソフトウェアはありますか? | いいえ |
| アプリと、それをサポートするインファ構造に対して四半期ごとの脆弱性スキャンを行いますか? | はい |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | はい |
| 変更要求を運用環境にデプロイする前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスはありますか? | はい |
| 追加のユーザーは、元の開発者によって運用環境に送信されたすべてのコード変更要求を確認して承認していますか? | はい |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | はい |
| 多要素認証 (MFA) が有効になっているのは次のとおりです。 | DNSManagement、Credential、CodeRepositories |
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
| アプリは、医療保険の可搬性と会計法 (HIPAA) に準拠していますか? | はい |
| アプリは Health Information Trust Alliance、Common Security Framework (HITRUST CSF) に準拠していますか? | はい |
| アプリはサービス組織コントロール (SOC 1) に準拠していますか? | 該当なし |
| アプリはサービス組織コントロール (SOC 2) に準拠していますか? | はい |
| どの SOC 2 認定を取得しましたか? | type2 |
| 最新の SOC2 認定日 | 2021-10-15 |
| アプリはサービス組織コントロール (SOC 3) に準拠していますか? | いいえ |
| アプリとそのサポート環境に対して、年間 PCI DSS 評価を実行していますか? | はい |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | いいえ |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | いいえ |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | いいえ |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | いいえ |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | いいえ |
| アプリは家族教育の権利とプライバシーに関する法律 (FERPA) に準拠していますか? | 該当なし |
| アプリは、子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | 該当なし |
| アプリはSarbanes-Oxley法 (SOX) に準拠していますか? | 該当なし |
| アプリは NIST 800-171 に準拠していますか? | はい |
| アプリは Cloud Security Alliance (CSA Star) の認定を受けていますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Response** |
|:----------------|:-------------|
| GDPR またはその他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| アプリケーションは、シングル サインオン、API アクセスなどのために Microsoft Identity Platform (Azure AD) と統合されますか? | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか? | はい |
| アプリは、最新バージョンの MSAL (Microsoft Authentication Library) または Microsoft Identity Web を認証に使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリは継続的アクセス評価 (CAE) をサポートしていますか? | いいえ |
| アプリは、コードに資格情報を格納していますか? | いいえ |
| Microsoft 365 用のアプリとアドインでは、Microsoft Graph の外部で追加の Microsoft API が使用される場合があります。 アプリまたはアドインは、追加の Microsoft API を使用していますか? | いいえ |

>このアプリケーションでは、Microsoft Graph は使用されません。

>このアプリケーションには、追加の API はありません。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="certification"

### <a name="certification-information"></a>認定情報

| **Control** | **Microsoft 365 認定結果** |
|:------------|:---------------------------------------|
| [**アプリケーションのセキュリティ**](../docs/certification-submission-guide.md#application-security) | **FAIL** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;侵入テスト | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;脆弱性評価レビュー (DAST/SAST/ペネトレーション テスト) | スコープ内 |
| [**運用上のセキュリティ**](../docs/certification-submission-guide.md#operational-security) | **渡す** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;マルウェア対策 - ウイルス対策 | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;マルウェア対策 - アプリケーション制御 | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;パッチ管理 - リスクのランク付け | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;パッチ管理 - パッチ適用 | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;脆弱性スキャン | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ファイアウォール - ファイアウォール (または同等のテクノロジ) | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ファイアウォール - Web アプリケーション ファイアウォール (WAF) (省略可能) | 該当なし |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;コントロールの変更 | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;セキュリティで保護されたソフトウェア開発/展開 | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;アカウント管理 | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;侵入の検出と防止 (省略可能) | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;セキュリティ イベント ログ | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;レビュー (データのログ記録) | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;セキュリティ イベント アラート | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;情報セキュリティ リスク管理 | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;インシデント対応 | スコープ内 |
| [**データ処理のセキュリティ &amp; プライバシー**](../docs/certification-submission-guide.md#data-handling-security-and-privacy) | **渡す** |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;転送中のデータ | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;保存データ | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;データの保持と破棄 | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;データ アクセス管理 | スコープ内 |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;GDPR | スコープ内 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end
