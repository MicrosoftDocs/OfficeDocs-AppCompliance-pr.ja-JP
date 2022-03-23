---
title: EasyLife 365 AG による EasyLife 365 のアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/21/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: EasyLife 365 で利用可能なすべてのセキュリティおよびコンプライアンス情報、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 1bbd4661f847866ed0d9094f641ba7d34fefd8c0
ms.sourcegitcommit: af065aeee2812a85ead9e0de968fc474204a6e8a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/22/2022
ms.locfileid: "63696509"
---
# <a name="easylife-365"></a>EasyLife 365

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2022 年 3 月 21 日</p>

* <a href="https://teams.microsoft.com/l/app/93731bac-4d43-480f-9e40-9fc567dfb817" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA200003697" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

EasyLife 365 AG から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | EasyLife 365 |
| ID | WA200003697 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | EasyLife 365 AG |
| 会社の Web サイト | [https://www.easylife365.cloud](https://www.easylife365.cloud) |
| アプリの利用規約 | [https://www.easylife365.cloud/terms](https://www.easylife365.cloud/terms) |
| アプリのコア機能 | ガバナンスを簡単に! |
| 会社の本社所在地 | スイス |
| アプリ情報ページ | [https://www.easylife365.cloud/governance/features](https://www.easylife365.cloud/governance/features) |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | Paas |
| アプリで使用するホスティング クラウド プロバイダー | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、EasyLife 365 AG によって、このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリで処理されるデータは何ですか? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| アプリは TLS 1.1 以上をサポートしていますか? | はい |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データが格納されていますか? | はい |
| データベースに格納されているデータは何ですか? | 90 日間のログ記録のグループ メタデータ (ID、名前) とユーザー情報 (ID、メール) |
| 基になるインファ構造が Microsoft 顧客データを処理または保存する場合、このデータは地理的にどこに保存されますか? | オランダ (the) |
| データの借入および廃棄プロセスが確立されていますか? | はい |
| アカウントの終了後にデータが保持される期間 | 90days 未満 |
| データ アクセス管理プロセスが確立されていますか? | はい |
| 顧客データまたは顧客コンテンツを第三者またはサブプロセッサに転送しますか? | 不要 |
| Microsoft カスタマー データを共有するサードパーティ サービスとデータ共有契約が締結されていますか? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

次[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報を示します。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行しますか? | はい |
| アプリには、バックアップと復元の戦略を含む、文書化された障害復旧計画がありますか? | はい |
| 環境で従来のマルウェア対策保護またはアプリケーションコントロールを使用していますか? | TraditionalAntiMalware, ApplicationControls |
| セキュリティの脆弱性をインデントおよびリスクランク付けするプロセスが確立されていますか? | はい |
| パッチの適用に関するサービス レベル契約 (SLA) を管理するポリシーはありますか? | はい |
| パッチポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | はい |
| 環境にサポートされていないオペレーティング システムやソフトウェアはありますか? | 不要 |
| アプリとアプリをサポートするインファ構造で四半期ごとに脆弱性スキャンを実行しますか? | 不要 |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | 不要 |
| 変更要求が運用に展開される前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスがありますか? | はい |
| 追加のユーザーが、元の開発者によって実稼働環境に提出されたコード変更要求を確認および承認していますか? | はい |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | はい |
| 多要素認証 (MFA) が有効になっているのは、次の場合です。 | DNSManagement、Credential、CodeRepositories |
| 従業員アカウントのプロビジョニング、変更、削除のプロセスが確立されていますか? | はい |
| アプリをサポートするネットワーク境界の境界の境界に侵入検出と防御 (IDPS) ソフトウェアが展開されていますか? | 該当なし |
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
| アプリはサービス組織のコントロール (SOC 2) に準拠していますか? | 不要 |
| どの SOC 2 認定を取得しましたか? | |
| 最新の SOC2 認定日 | |
| アプリは Service Organization Controls (SOC 3) に準拠していますか? | 不要 |
| 最新の SOC3 認定日 | |
| アプリとそのサポート環境に対して、PCI DSS の年次評価を実行しますか。 | 不要 |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | 不要 |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | 不要 |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | 不要 |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | 不要 |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | 不要 |
| アプリは家族教育の権利とプライバシー法 (FERPA) に準拠していますか? | 不要 |
| アプリは子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | 不要 |
| アプリは、ユーザー法 (SOX) Sarbanes-Oxley準拠していますか? | 不要 |
| アプリは NIST 800-171 に準拠していますか? | 不要 |
| アプリはクラウド セキュリティ アライアンス (CSA Star) の認定を受けていますか? | 不要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **応答** |
|:----------------|:-------------|
| GDPR または他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | はい |
| アプリには、顧客データの収集、使用、共有、および保存方法を示す外部向けプライバシー通知がありますか? | はい |
| プライバシー ポリシーの URL | https://www.easylife365.cloud/web/privacy |
| アプリは、法的な影響や同様の影響を与える可能性があるプロファイリングを含む、自動化された意思決定を実行しますか? | 不要 |
| アプリは、プライバシーに関する通知 (マーケティング、分析) に記載されていない第 2 の目的で顧客データを処理しますか? | 不要 |
| 機密データの特別なカテゴリ (人種的または民族的な起源、政治的意見、宗教的または哲学的信念、遺伝的または生体認証データ、健康データ) または違反通知法の対象となるデータのカテゴリを処理しますか? | 不要 |
| アプリは未成年者 (16 歳未満の個人) からデータを収集または処理しますか? | 不要 |
| アプリには、要求に応じて個人の個人データを削除する機能がありますか? | 不要 |
| アプリには、要求に応じて個人の個人データの処理を制限または制限する機能がありますか? | 不要 |
| アプリは個人に個人データを修正または更新する機能を提供しますか? | 不要 |
| アプリの個人データの処理に関連するリスクを特定するために、定期的なデータ セキュリティとプライバシーレビュー (データ保護影響評価やプライバシー リスク評価など) が実行されますか? | 不要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリケーションは Microsoft Identity Platform (Azure AD) と統合してシングル サインオンや API アクセスなどを行いますか。 | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか? | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) または Microsoft Identity Web の最新バージョンを使用していますか? | はい |
| アプリで上記のライブラリのいずれかを使用しない場合、どの認証ライブラリまたはライブラリを使用しますか? |  |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | 不要 |
| アプリは継続的アクセス評価 (CAE) をサポートしています | 不要 |
| アプリはコードに資格情報を保存しますか? | 不要 |
| アプリとアドインは、microsoft Microsoft 365外部で追加の Microsoft API を使用Graph。 アプリまたはアドインで追加の Microsoft API を使用していますか? | はい |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph を使用したデータ アクセス

>|   **Graphアクセス許可**  | **アクセス許可の種類** |          **妥当性**          | **Azure ADアプリ ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Group.Read.All | 委任 | グループまたはグループを読み取Teams | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Group.ReadWrite.All | 委任 | グループまたはグループのメタデータをマニTeams | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| GroupMember.Read.All | 委任 | グループのメンバーを読み取る | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.Read.All | 委任 | ゲスト アカウントのメタデータを取得できます | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| User.ReadBasic.All | 委任 | 組織内のメンバーまたはゲスト アカウントを検索できます | [192ba193-b68c-464c-a920-7eaa93b59a12](../azure/192ba193-b68c-464c-a920-7eaa93b59a12.md) |
>| Channel.Create | アプリケーション | チームのチャネルを作成する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Channel.ReadBasic.All | アプリケーション | 既存のチームのチャネルを読み取る | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.Read.All | アプリケーション | 現在のグループおよびゲスト アカウント設定テンプレートを取得する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Directory.ReadWrite.All | アプリケーション | グループまたはチームのゲスト アカウント設定を適用する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Create | アプリケーション | グループを作成する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | 両方とも | グループ情報を読み取り、グループ エイリアスを取得する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.ReadWrite.All | アプリケーション | バックエンドでグループ メタデータを操作する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.Read.All | アプリケーション | バックエンドでグループまたはチーム のメンバーシップを取得する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| GroupMember.ReadWrite.All | アプリケーション | グループまたはチームからメンバーを追加または削除できます | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| IdentityRiskyUser.ReadWrite.All | アプリケーション | ゲスト アカウントとそのメタデータを操作できます | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Mail.Send | アプリケーション | 共有メールボックスを使用してメールを送信する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| MailboxSettings.Read | アプリケーション | ユーザーの優先言語設定を取得します。 | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Reports.Read.All | アプリケーション | グループとグループの使用状況データを取得Teams | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Team.ReadBasic.All | アプリケーション | 基本的なチーム情報を取得する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamSettings.ReadWrite.All | アプリケーション | チームのアーカイブとアーカイブ解除を許可する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Teams。作成 | アプリケーション | チームを作成する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.Read.All | アプリケーション | 作成したチームからタブを取得する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| TeamsTab.ReadWrite.All | アプリケーション | 作成したチームのタブを作成または manipualte できます | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Invite.All | アプリケーション | ユーザーをテナントに招待する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read | 委任 | ユーザー情報と組織情報を取得する | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| User.Read.All | 両方とも | ゲストおよびユーザー情報を取得します。 | [2e8b6192-7ea3-44a7-921e-86e0afd8cd0a](../azure/2e8b6192-7ea3-44a7-921e-86e0afd8cd0a.md) |
>| Group.Read.All | 委任 | すべてのユーザーのグループを読み取る | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| Group.ReadWrite.All | 委任 | ユーザーのグループ メタデータを変更し、グループとグループを操作Teams | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.Read.All | 委任 | グループの所有者がグループまたはチームのメンバーシップを読み取る | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| GroupMember.ReadWrite.All | 委任 | グループの所有者がグループまたはチームのメンバーシップを操作できます | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamSettings.ReadWrite.All | 委任 | チームをアーカイブまたはアーカイブ解除できます | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsActivity.Send | アプリケーション | バックエンドで通知Teams送信する場合に使用します。 | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| TeamsAppInstallation.ReadForUser.All | アプリケーション | ユーザーが EasyLife アプリがインストールされていることを確認してから、ユーザーに通知を送信Teams。 | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read | 委任 | 組織データとユーザー情報の読み取り | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.Read.All | 委任 | ディレクトリ内の他のメンバーまたはゲスト アカウントを検索できます | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| User.ReadBasic.All | 委任 | ユーザーの写真を表示する | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| メール | 委任 | SSO 認証で使用される | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| offline_access | 委任 | SSO 認証で使用される | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| openid | 委任 | SSO 認証で使用される | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |
>| profile | 委任 | SSO 認証で使用される | [716a0b19-6f38-4909-a80a-ffaac7957316](../azure/716a0b19-6f38-4909-a80a-ffaac7957316.md) |

>このアプリケーションには、追加の API が含まれる必要があります。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

