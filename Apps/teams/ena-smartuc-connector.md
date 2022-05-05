---
title: ENA SmartUC Connector by ENA のアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/11/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: ENA SmartUC Connector で使用可能なすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 35216e57d20e4893f3d349809568c89df0b60032
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/05/2022
ms.locfileid: "65226161"
---
# <a name="ena-smartuc-connector"></a>ENA SmartUC Connector

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2022 年 3 月 11 日</p>

* <a href="https://teams.microsoft.com/l/app/029cfd5a-4413-499d-bda6-a2a0a3f5e70e" target="_blank">Teams ストアで表示する</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003354" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

ENA から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | ENA SmartUC Connector |
| ID | WA200003354 |
| サポートされているOffice 365 クライアント | Microsoft Teams |
| パートナー会社名 | ENA |
| 会社の Web サイト | [https://www.ena.com](https://www.ena.com) |
| アプリの使用条件 | [https://www.ena.com/legal/aup/](https://www.ena.com/legal/aup/) |
| アプリのコア機能 | このアプリは、ENA SmartUC 製品セットを Teams アプリに接続し、エンド ユーザーが Teams 内から ENA SmartUC にバックアップされた電話を発信できるようにします。 |
| 会社の本社の場所 | 米国 オブ アメリカ |
| アプリ情報ページ | |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | ハイブリッド |
| アプリで使用するホスティング クラウド プロバイダーはどれですか? | その他、Metaswitch によって動作するサービスの一部は Azure でホストされます。 また、独自のインフラストラクチャ (EAS サーバーなど) のホスト方法の詳細も含める必要があります。 |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて、ENA から提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリによって処理されるデータは何ですか? | IP アドレス、ユーザーの電話番号の呼び出し、パスワード、CommPortal 認証トークン、CommPortal セッション ID、通話時の呼び出し先の電話番号、電子メール アドレスのドメインなど、次の EUII/OII を MCT プロキシ経由で CommPortal JSON API に転送できます。 |
| アプリは TLS 1.1 以降をサポートしていますか? | はい |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データは格納されますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行していますか? | いいえ |
| バックアップと復元の戦略など、文書化されたディザスター リカバリー計画はアプリに含まれていますか? | いいえ |
| お使いの環境では、従来のマルウェア対策保護またはアプリケーション制御が使用されていますか? | TraditionalAntiMalware |
| セキュリティの脆弱性をインデントおよびリスク ランク付けするための確立されたプロセスはありますか? | はい |
| パッチを適用するためのサービス レベル アグリーメント (SLA) を管理するポリシーはありますか? | はい |
| パッチ ポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | はい |
| お使いの環境にサポートされていないオペレーティング システムまたはソフトウェアはありますか? | いいえ |
| アプリと、それをサポートするインファ構造に対して四半期ごとの脆弱性スキャンを行いますか? | はい |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | はい |
| 変更要求を運用環境にデプロイする前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスはありますか? | はい |
| 追加のユーザーは、元の開発者によって運用環境に送信されたすべてのコード変更要求を確認して承認していますか? | はい |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | いいえ |
| 多要素認証 (MFA) が有効になっているのは次のとおりです。 | CodeRepositories、DNSManagement |
| 従業員アカウントのプロビジョニング、変更、削除のための確立されたプロセスはありますか? | はい |
| アプリをサポートするネットワーク境界の境界に侵入検出と防止 (IDPS) ソフトウェアがデプロイされていますか? | いいえ |
| アプリをサポートするすべてのシステム コンポーネントにイベント ログ記録を設定していますか? | はい |
| すべてのログは、潜在的なセキュリティ イベントを検出するために、人間または自動化されたツールによって定期的に確認されますか? | いいえ |
| セキュリティ イベントが検出されると、トリアージのために従業員にアラートが自動的に送信されますか? | いいえ |
| 正式な情報セキュリティ リスク管理プロセスが確立されていますか? | はい |
| 正式なセキュリティ インシデント対応プロセスが文書化され、確立されていますか? | はい |
| 検出から 72 時間以内に、アプリまたはサービスのデータ侵害を監督機関や違反の影響を受けた個人に報告しますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリは、医療保険の可搬性と会計法 (HIPAA) に準拠していますか? | いいえ |
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
| アプリは家族教育の権利とプライバシーに関する法律 (FERPA) に準拠していますか? | 該当なし |
| アプリは、子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | 該当なし |
| アプリはSarbanes-Oxley法 (SOX) に準拠していますか? | いいえ |
| アプリは NIST 800-171 に準拠していますか? | いいえ |
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
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか? | いいえ |
| アプリは、最新バージョンの MSAL (Microsoft Authentication Library) または Microsoft Identity Web を認証に使用していますか? | はい |
| アプリで上記のライブラリのいずれかを使用していない場合、どの認証ライブラリまたはライブラリが使用されますか? |  |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリは継続的アクセス評価 (CAE) をサポートしていますか? | いいえ |
| アプリは、コードに資格情報を格納していますか? | はい |
| Microsoft 365用のアプリとアドインでは、Microsoft Graphの外部で追加の Microsoft API が使用される場合があります。 アプリまたはアドインは、追加の Microsoft API を使用していますか? | はい |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

>|   **Graphアクセス許可**  | **アクセス許可の種類** |          **妥当性**          | **Azure AD アプリ ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| ChannelMember.Read.All | 委任 | 現在のチャネル/チャットのメンバーのユーザー ID と表示名。 アプリはこれを使用して、ユーザーに通話するチャネル/チャット メンバーの一覧を表示します。 | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](/microsoft-365-app-certification/azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| Chat.ReadBasic | 委任 | 現在のチャットのメンバーのユーザー ID と表示名。 アプリはこれを使用して、通話するチャット メンバーの一覧をユーザーに表示します。 | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](/microsoft-365-app-certification/azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| People.Read.All | 委任 | 現在のチームのメンバーのユーザー ID と表示名。 アプリはこれを使用して、呼び出すチーム メンバーの一覧をユーザーに提示します。 | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](/microsoft-365-app-certification/azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| User.Read.All | 委任 | ユーザーのビジネス番号と携帯電話番号。 これは、これらの番号への電話を開始できるようにするために必要です。 | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](/microsoft-365-app-certification/azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| offline_access | 委任 | ユーザーの承認トークン。アプリが自分の代わりに一覧表示されている他のGraph API エンドポイントにアクセスすることを承認します。 これらのアクセス許可は、Microsoft Identity プラットフォーム アプリケーションが機能するために必要です。 | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](/microsoft-365-app-certification/azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| openid | 委任 | ユーザーの承認トークン。アプリが自分の代わりに一覧表示されている他のGraph API エンドポイントにアクセスすることを承認します。 これらのアクセス許可は、Microsoft Identity プラットフォーム アプリケーションが機能するために必要です。 | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](/microsoft-365-app-certification/azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |
>| profile | 委任 | ユーザーの承認トークン。アプリが自分の代わりに一覧表示されている他のGraph API エンドポイントにアクセスすることを承認します。 これらのアクセス許可は、Microsoft Identity プラットフォーム アプリケーションが機能するために必要です。 | [029cfd5a-4413-499d-bda6-a2a0a3f5e70e](/microsoft-365-app-certification/azure/029cfd5a-4413-499d-bda6-a2a0a3f5e70e) |

>このアプリケーションには、追加の API はありません。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

