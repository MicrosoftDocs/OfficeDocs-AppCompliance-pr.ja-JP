---
title: AvePoint Inc. &amp; インサイト (BYOL) Microsoft 365ポリシーに関するアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 11/01/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: ポリシー インサイト for Microsoft 365 (BYOL)、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関する利用可能なすべてのセキュリティおよびコンプライアンス情報 &amp; 。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 2f86ce69199b8573824f5207ea1e7b78147b73ea
ms.sourcegitcommit: cb50f8967ff1ca98c98bcadb26c05b3a5c5a6ea8
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 11/09/2021
ms.locfileid: "60874961"
---
# <a name="policies-amp-insights-for-microsoft-365-byol"></a>ポリシーインサイト &amp; (BYOL) Microsoft 365ポリシー

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 10 月 26 日</p>

* <a href="https://appsource.microsoft.com/product/web-apps/avepoint.policies-insights_mo365_byol" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

AvePoint Inc. から Microsoft に提供される情報:

| **Information** | **Response** |
|:----------------|:-------------|
| アプリ名 | ポリシーインサイト &amp; (BYOL) Microsoft 365ポリシー |
| ID | avepoint.policies-insights_mo365_byol |
| パートナー会社名 | AvePoint Inc. |
| 会社の Web サイト | [https://www.avepoint.com](https://www.avepoint.com) |
| アプリの利用規約 | [https://www.avepoint.com/company/terms-of-use](https://www.avepoint.com/company/terms-of-use) |
| アプリのコア機能 | セキュリティに関する分析情報を取得し、自動化されたポリシーを Teams、グループ、SharePoint、およびOneDrive |
| 会社の本社所在地 | アメリカ |
| アプリ情報ページ | |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | Paas |
| アプリで使用するホスティング クラウド プロバイダー | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールについて、AvePoint Inc.によって提供されています。

| **Information** | **Response** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリで処理されるデータは何ですか? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| アプリは TLS 1.1 以上をサポートしていますか? | はい |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データが格納されていますか? | はい |
| データベースに格納されているデータは何ですか? |  SharePoint/ODFB サイト/Microsoft 365/チーム ID、名前、URL。  |
| 基になるインファ構造が Microsoft 顧客データを処理または保存する場合、このデータは地理的にどこに保存されますか? | アメリカ |
| データの借入および廃棄プロセスが確立されていますか? | はい |
| アカウントの終了後にデータが保持される期間 | 30 日未満 |
| データ アクセス管理プロセスが確立されていますか? | はい |
| 顧客データまたは顧客コンテンツを第三者またはサブプロセッサに転送しますか? | 不要 |
| Microsoft カスタマー データを共有するサードパーティ サービスとデータ共有契約が締結されていますか? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

| **Information** | **Response** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行しますか? | はい |
| アプリには、バックアップと復元の戦略を含む、文書化された障害復旧計画がありますか? | はい |
| 環境で従来のマルウェア対策保護またはアプリケーションコントロールを使用していますか? | ApplicationControls |
| セキュリティの脆弱性をインデントおよびリスクランク付けするプロセスが確立されていますか? | はい |
| パッチの適用に関するサービス レベル契約 (SLA) を管理するポリシーはありますか? | はい |
| パッチポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | はい |
| 環境にサポートされていないオペレーティング システムやソフトウェアはありますか? | 不要 |
| アプリとアプリをサポートするインファ構造で四半期ごとに脆弱性スキャンを実行しますか? | はい |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | はい |
| 変更要求が運用に展開される前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスがありますか? | はい |
| 追加のユーザーが、元の開発者によって実稼働環境に提出されたコード変更要求を確認および承認していますか? | はい |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | はい |
| 多要素認証 (MFA) が有効になっているのは、次の場合です。 | CodeRepositories, Credential, DNSManagement |
| 従業員アカウントのプロビジョニング、変更、削除のプロセスが確立されていますか? | はい |
| アプリをサポートするネットワーク境界の境界の境界に侵入検出と防御 (IDPS) ソフトウェアが展開されていますか? | はい |
| アプリをサポートしているすべてのシステム コンポーネントにイベント ログが設定されていますか? | はい |
| すべてのログは、潜在的なセキュリティ イベントを検出するために、人間または自動ツールによって定期的に確認されますか? | はい|
| セキュリティ イベントが検出されると、アラートが従業員に自動的に送信され、トリアージが発生しますか? | はい |
| 正式な情報セキュリティリスク管理プロセスが確立されていますか? | はい |
| 正式なセキュリティ インシデント対応プロセスが文書化され、確立されていますか? |  |
| 検出から 72 時間以内に、侵害の影響を受けた監督当局や個人にアプリまたはサービスのデータ侵害を報告しますか?| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **Response** |
|:----------------|:-------------|
| アプリは、健康保険の移植性および会計法 (HIPAA) に準拠していますか? | 該当なし |
| アプリは、正常性情報信頼アライアンス、共通セキュリティ フレームワーク (HITRUST CSF) に準拠していますか? | 該当なし |
| アプリはサービス組織のコントロール (SOC 1) に準拠していますか? | 該当なし |
| 最新の SOC1 認定日 |   |
| アプリはサービス組織のコントロール (SOC 2) に準拠していますか? | はい |
| どの SOC 2 認定を取得しましたか? |  type2 |
| 最新の SOC2 認定日 |  2021-02-19 |
| アプリは Service Organization Controls (SOC 3) に準拠していますか? | 不要 |
| 最新の SOC3 認定日 | |
| アプリとそのサポート環境に対して、PCI DSS の年次評価を実行しますか。 | 該当なし |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | はい |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | 該当なし |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | はい |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | 不要 |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | 不要 |
| アプリは家族教育の権利とプライバシー法 (FERPA) に準拠していますか? | 該当なし |
| アプリは子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | 該当なし |
| アプリは、ユーザー法 (SOX) Sarbanes-Oxley準拠していますか? | はい |
| アプリは NIST 800-171 に準拠していますか? | 該当なし |
| アプリはクラウド セキュリティ アライアンス (CSA Star) の認定を受けていますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **Response** |
|:----------------|:-------------|
| GDPR または他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | はい |
| アプリには、顧客データの収集、使用、共有、および保存方法を示す外部向けプライバシー通知がありますか? | はい |
| プライバシー ポリシーの URL | https://www.avepoint.com/license/dataprotection.html |
| アプリは、法的な影響や同様の影響を与える可能性があるプロファイリングを含む、自動化された意思決定を実行しますか? | 不要 |
| アプリは、プライバシーに関する通知 (マーケティング、分析) に記載されていない第 2 の目的で顧客データを処理しますか? | 不要 |
| 機密データの特別なカテゴリ (人種的または民族的な起源、政治的意見、宗教的または哲学的信念、遺伝的または生体認証データ、健康データ) または違反通知法の対象となるデータのカテゴリを処理しますか? | 不要 |
| アプリは未成年者 (16 歳未満の個人) からデータを収集または処理しますか? | 不要 |
| アプリには、要求に応じて個人の個人データを削除する機能がありますか? | 不要 |
| アプリには、要求に応じて個人の個人データの処理を制限または制限する機能がありますか? | 不要 |
| アプリは個人に個人データを修正または更新する機能を提供しますか? | 不要 |
| アプリの個人データの処理に関連するリスクを特定するために、定期的なデータ セキュリティとプライバシーレビュー (データ保護影響評価やプライバシー リスク評価など) が実行されますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **Response** |
|:----------------|:-------------|
| アプリケーションは Microsoft Identity Platform (Azure AD) と統合してシングル サインオンや API アクセスなどを行いますか。 | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか? | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) または Microsoft Identity Web の最新バージョンを使用していますか? | はい |
| アプリで上記のライブラリのいずれかを使用しない場合、どの認証ライブラリまたはライブラリを使用しますか? |  |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | アプリケーションは、すべての条件付Azure ADルールを使用できるよう、アプリケーションとフェデレーションを行います。 |
| アプリは継続的アクセス評価 (CAE) をサポートしています | はい |
| アプリはコードに資格情報を保存しますか? | 不要 |
| アプリとアドインは、microsoft Microsoft 365外部で追加の Microsoft API を使用Graph。 アプリまたはアドインで追加の Microsoft API を使用していますか? | はい |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

>|   **Graphアクセス許可**  | **アクセス許可の種類** |          **妥当性**          |
>|:------------------------|:--------------------|:------------------------------------|
>| Sites.FullControl.All | アプリケーション | サイト コレクションおよびグループ/チームの情報を取得および更新し、&#8217;します。 |
>| User.Read.All | アプリケーション | すべてのユーザーの設定を読み取る |
>| User.ReadWrite.All | アプリケーション | ユーザーの設定の読み取りおよび書き込み |
>| Group.Read.All | アプリケーション | グループのメンバーと設定の読み取り |
>| Group.ReadWrite.All | アプリケーション | グループのメンバーと設定を更新する |
>| Directory.ReadWrite.All | アプリケーション |   組織のディレクトリ内のユーザーとグループ データの読み取りおよび書き込み。 |

>このアプリケーションには、追加の API が含まれる必要があります。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

