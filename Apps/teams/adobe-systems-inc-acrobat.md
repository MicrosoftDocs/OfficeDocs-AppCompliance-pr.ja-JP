---
title: Adobe Systems Inc. による Adobe Acrobat のアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/09/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Adobe Acrobat で使用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: b94696ec95be7b58f03aaa048169e7c5b6cd89a0
ms.sourcegitcommit: 62e60dfc73f78900307418e60318353faf8d9a57
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/12/2022
ms.locfileid: "63459320"
---
# <a name="adobe-acrobat"></a>Adobe Acrobat

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者による最終更新日: 2022 年 3 月 6 日</p>

* <a href="https://teams.microsoft.com/l/app/10aea93d-20cf-44c2-b4a5-284c5ef2e6a5" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200002564" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Adobe Systems Inc. から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Adobe Acrobat |
| ID | WA200002564 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | Adobe Systems Inc. |
| 会社の Web サイト | [https://www.adobe.com](https://www.adobe.com) |
| アプリの利用規約 | [https://www.adobe.com/legal/terms.html](https://www.adobe.com/legal/terms.html) |
| アプリのコア機能 | Microsoft Teams 用 Adobe Acrobat を使用すると、PDF ファイル形式の作成者は、チャネル内のすべてのユーザーと共同作業を行い、Teams 環境から離れることなく、1 つの PDF &#8211; でフィードバックを収集する方法を提供しています。 他のユーザーがドキュメントに対してアクションを実行すると、アクティビティ通知を受け取る。 レビュー担当者は、フィードバックを表示してコメント&#8217;、競合の管理に&#8217;時間を減らします |
| 会社の本社所在地 | アメリカ |
| アプリ情報ページ | [https://helpx.adobe.com/document-cloud/help/microsoft-teams...](https://helpx.adobe.com/document-cloud/help/microsoft-teams.html) |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | Paas |
| アプリで使用するホスティング クラウド プロバイダー | Azure、 Aws |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、Adobe Systems Inc. から、このアプリが組織データを収集および保存する方法、およびアプリが収集するデータに対して組織が持つコントロールについて提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリで処理されるデータは何ですか? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| アプリは TLS 1.1 以上をサポートしていますか? | はい |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データが格納されていますか? | はい |
| データベースに格納されているデータは何ですか? | tenant_id、upn_hash、profile_and_token_info、oauth_state、ims_login_changed_at、preference_data、updated_at、created_at、expires_at |
| 基になるインファ構造が Microsoft 顧客データを処理または保存する場合、このデータは地理的にどこに保存されますか? |  |
| データの借入および廃棄プロセスが確立されていますか? | はい |
| アカウントの終了後にデータが保持される期間 | 30 日未満 |
| データ アクセス管理プロセスが確立されていますか? | はい |
| 顧客データまたは顧客コンテンツを第三者またはサブプロセッサに転送しますか? | はい |
| Microsoft カスタマー データを共有するサードパーティ サービスとデータ共有契約が締結されていますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

次[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報を示します。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行しますか? | はい |
| アプリには、バックアップと復元の戦略を含む、文書化された障害復旧計画がありますか? | はい |
| 環境で従来のマルウェア対策保護またはアプリケーションコントロールを使用していますか? | ApplicationControls, TraditionalAntiMalware |
| セキュリティの脆弱性をインデントおよびリスクランク付けするプロセスが確立されていますか? | はい |
| パッチの適用に関するサービス レベル契約 (SLA) を管理するポリシーはありますか? | はい |
| パッチポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | はい |
| 環境にサポートされていないオペレーティング システムやソフトウェアはありますか? | 不要 |
| アプリとアプリをサポートするインファ構造で四半期ごとに脆弱性スキャンを実行しますか? | はい |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | はい |
| 変更要求が運用に展開される前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスがありますか? | はい |
| 追加のユーザーが、元の開発者によって実稼働環境に提出されたコード変更要求を確認および承認していますか? | はい |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | はい |
| 多要素認証 (MFA) が有効になっているのは、次の場合です。 | CodeRepositories, DNSManagement, Credential |
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

| **Information** | **応答** |
|:----------------|:-------------|
| アプリは、健康保険の移植性および会計法 (HIPAA) に準拠していますか? | 不要 |
| アプリは、正常性情報信頼アライアンス、共通セキュリティ フレームワーク (HITRUST CSF) に準拠していますか? | 不要 |
| アプリはサービス組織のコントロール (SOC 1) に準拠していますか? | 不要 |
| 最新の SOC1 認定日 |   |
| アプリはサービス組織のコントロール (SOC 2) に準拠していますか? | はい |
| どの SOC 2 認定を取得しましたか? |  type2 |
| 最新の SOC2 認定日 |  2021-11-22 |
| アプリは Service Organization Controls (SOC 3) に準拠していますか? | 不要 |
| 最新の SOC3 認定日 | |
| アプリとそのサポート環境に対して、PCI DSS の年次評価を実行しますか。 | 不要 |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | はい |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | 不要 |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | いいえ |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | いいえ |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | はい |
| アプリは家族教育の権利とプライバシー法 (FERPA) に準拠していますか? | はい |
| アプリは子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | はい |
| アプリは、ユーザー法 (SOX) Sarbanes-Oxley準拠していますか? | いいえ |
| アプリは NIST 800-171 に準拠していますか? | はい |
| アプリはクラウド セキュリティ アライアンス (CSA Star) の認定を受けていますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **応答** |
|:----------------|:-------------|
| GDPR または他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | はい |
| アプリには、顧客データの収集、使用、共有、および保存方法を示す外部向けプライバシー通知がありますか? | はい |
| プライバシー ポリシーの URL | https://business.adobe.com/privacy/general-data-protection-regulation.html |
| アプリは、法的な影響や同様の影響を与える可能性があるプロファイリングを含む、自動化された意思決定を実行しますか? | 不要 |
| アプリは、プライバシーに関する通知 (マーケティング、分析) に記載されていない第 2 の目的で顧客データを処理しますか? | いいえ |
| 機密データの特別なカテゴリ (人種的または民族的な起源、政治的意見、宗教的または哲学的信念、遺伝的または生体認証データ、健康データ) または違反通知法の対象となるデータのカテゴリを処理しますか? | いいえ |
| アプリは未成年者 (16 歳未満の個人) からデータを収集または処理しますか? | いいえ |
| アプリには、要求に応じて個人の個人データを削除する機能がありますか? | いいえ |
| アプリには、要求に応じて個人の個人データの処理を制限または制限する機能がありますか? | いいえ |
| アプリは個人に個人データを修正または更新する機能を提供しますか? | はい |
| アプリの個人データの処理に関連するリスクを特定するために、定期的なデータ セキュリティとプライバシーレビュー (データ保護影響評価やプライバシー リスク評価など) が実行されますか? | はい |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリケーションは Microsoft Identity Platform (Azure AD) と統合してシングル サインオンや API アクセスなどを行いますか。 | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか? | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) または Microsoft Identity Web の最新バージョンを使用していますか? | 不要 |
| アプリで上記のライブラリのいずれかを使用しない場合、どの認証ライブラリまたはライブラリを使用しますか? |  |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | いいえ |
| アプリは継続的アクセス評価 (CAE) をサポートしています | いいえ |
| アプリはコードに資格情報を保存しますか? | いいえ |
| アプリとアドインは、microsoft Microsoft 365外部で追加の Microsoft API を使用Graph。 アプリまたはアドインで追加の Microsoft API を使用していますか? | いいえ |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph を使用したデータ アクセス

>|   **Graphアクセス許可**  | **アクセス許可の種類** |          **妥当性**          | **Azure ADアプリ ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Files.ReadWrite.All | 委任 | ユーザーの最近のチャネルのファイルとフォルダーをリストOneDrive、Teams移動する。 ユーザーは、これらのファイルにアクセスし、それらを使用して操作を実行し、ファイルをストレージに保存することができます。 | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| Team.ReadBasic.All | 委任 | チーム名とチームの説明の読み取り | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| User.Read | 委任 | サインインおよびユーザー プロファイルの読み取り | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| メール | 委任 | ユーザーのメール アドレスを表示する | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| offline_access | 委任 | アクセス権を与えられたデータへのアクセスを維持する | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| openid | 委任 | ユーザーのサインイン | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |
>| profile | 委任 | ユーザーの基本プロファイルの表示 | [ecff17cf-5629-49ba-a629-7f575496aeac](../azure/ecff17cf-5629-49ba-a629-7f575496aeac) |

>このアプリケーションには、追加の API が含まれる必要があります。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

