---
title: 意思決定による意思決定に関するアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 08/18/2021
ms.topic: article
ms.service: attestation
certification_type: attested
description: 意思決定、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリのセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 0353886df853f0916252e41e8829214ce1e0a4d5
ms.sourcegitcommit: 58c50d1704196178455927329748485b40dd7880
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/17/2022
ms.locfileid: "63544945"
---
# <a name="decisions"></a>決定事項

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2021 年 6 月 2 日</p>

* <a href="https://teams.microsoft.com/l/app/d3d1be68-066c-4967-a74b-9edcf902dcfb" target="_blank">ストアでの表示Teamsする</a>
* <a href="https://appsource.microsoft.com/product/office/WA104381880" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Microsoft に対して Decisions によって提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | 決定事項 |
| ID | WA104381880 |
| Office 365サポートされているクライアント | Microsoft Teams |
| パートナー会社名 | 決定事項 |
| 会社の Web サイト | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| アプリの利用規約 | [https://www.meetingdecisions.com/terms-of-service](https://www.meetingdecisions.com/terms-of-service) |
| アプリのコア機能 | 議題ビルダー、分テンプレートなど、会議の数を会議の内部に構築Teams。 |
| 会社の本社所在地 | ノルウェー |
| アプリ情報ページ | [https://www.meetingdecisions.com](https://www.meetingdecisions.com) |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | Paas |
| アプリで使用するホスティング クラウド プロバイダー | Azure |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集して格納する方法と、アプリが収集するデータに対して組織が持つコントロールに関する決定によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリで処理されるデータは何ですか? | Microsoft.Ingestion.Attestation.DocsPublishingCommon.AppInfos.DataProcess |
| アプリは TLS 1.1 以上をサポートしていますか? |  |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データが格納されていますか? | はい |
| データベースに格納されているデータは何ですか? |  |
| 基になるインファ構造が Microsoft 顧客データを処理または保存する場合、このデータは地理的にどこに保存されますか? |  |
| データの借入および廃棄プロセスが確立されていますか? |  |
| アカウントの終了後にデータが保持される期間 | 3months 内で削除済み |
| データ アクセス管理プロセスが確立されていますか? |  |
| 顧客データまたは顧客コンテンツを第三者またはサブプロセッサに転送しますか? |  |
| Microsoft カスタマー データを共有するサードパーティ サービスとデータ共有契約が締結されていますか? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

次[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報を示します。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行しますか? | はい |
| アプリには、バックアップと復元の戦略を含む、文書化された障害復旧計画がありますか? | はい |
| 環境で従来のマルウェア対策保護またはアプリケーションコントロールを使用していますか? |  |
| セキュリティの脆弱性をインデントおよびリスクランク付けするプロセスが確立されていますか? |  |
| パッチの適用に関するサービス レベル契約 (SLA) を管理するポリシーはありますか? |  |
| パッチポリシー SLA に従ってパッチ管理アクティビティを実行しますか? |  |
| 環境にサポートされていないオペレーティング システムやソフトウェアはありますか? |  |
| アプリとアプリをサポートするインファ構造で四半期ごとに脆弱性スキャンを実行しますか? |  |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? |  |
| 変更要求が運用に展開される前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスがありますか? |  |
| 追加のユーザーが、元の開発者によって実稼働環境に提出されたコード変更要求を確認および承認していますか? |  |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? |  |
| 多要素認証 (MFA) が有効になっているのは、次の場合です。 |  |
| 従業員アカウントのプロビジョニング、変更、削除のプロセスが確立されていますか? |  |
| アプリをサポートするネットワーク境界の境界の境界に侵入検出と防御 (IDPS) ソフトウェアが展開されていますか? |  |
| アプリをサポートしているすべてのシステム コンポーネントにイベント ログが設定されていますか? |  |
| すべてのログは、潜在的なセキュリティ イベントを検出するために、人間または自動ツールによって定期的に確認されますか? | |
| セキュリティ イベントが検出されると、アラートが従業員に自動的に送信され、トリアージが発生しますか? |  |
| 正式な情報セキュリティリスク管理プロセスが確立されていますか? |  |
| 正式なセキュリティ インシデント対応プロセスが文書化され、確立されていますか? |  |
| 検出から 72 時間以内に、侵害の影響を受けた監督当局や個人にアプリまたはサービスのデータ侵害を報告しますか?| |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリは、健康保険の移植性および会計法 (HIPAA) に準拠していますか? | 該当なし |
| アプリは、正常性情報信頼アライアンス、共通セキュリティ フレームワーク (HITRUST CSF) に準拠していますか? | 該当なし |
| アプリはサービス組織のコントロール (SOC 1) に準拠していますか? | 該当なし |
| 最新の SOC1 認定日 |   |
| アプリはサービス組織のコントロール (SOC 2) に準拠していますか? | 不要 |
| どの SOC 2 認定を取得しましたか? | |
| 最新の SOC2 認定日 | |
| アプリは Service Organization Controls (SOC 3) に準拠していますか? | 不要 |
| 最新の SOC3 認定日 | |
| アプリとそのサポート環境に対して、PCI DSS の年次評価を実行しますか。 | 不要 |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | 不要 |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | いいえ |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | いいえ |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | いいえ |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | 不要 |
| アプリは家族教育の権利とプライバシー法 (FERPA) に準拠していますか? | 該当なし |
| アプリは子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | 該当なし |
| アプリは、ユーザー法 (SOX) Sarbanes-Oxley準拠していますか? | 不要 |
| アプリは NIST 800-171 に準拠していますか? |  |
| アプリはクラウド セキュリティ アライアンス (CSA Star) の認定を受けていますか? | いいえ |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **応答** |
|:----------------|:-------------|
| GDPR または他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | はい |
| アプリには、顧客データの収集、使用、共有、および保存方法を示す外部向けプライバシー通知がありますか? |  |
| アプリは、法的な影響や同様の影響を与える可能性があるプロファイリングを含む、自動化された意思決定を実行しますか? |  |
| アプリは、プライバシーに関する通知 (マーケティング、分析) に記載されていない第 2 の目的で顧客データを処理しますか? |  |
| 機密データの特別なカテゴリ (人種的または民族的な起源、政治的意見、宗教的または哲学的信念、遺伝的または生体認証データ、健康データ) または違反通知法の対象となるデータのカテゴリを処理しますか? |  |
| アプリは未成年者 (16 歳未満の個人) からデータを収集または処理しますか? |  |
| アプリには、要求に応じて個人の個人データを削除する機能がありますか? |  |
| アプリには、要求に応じて個人の個人データの処理を制限または制限する機能がありますか? |  |
| アプリは個人に個人データを修正または更新する機能を提供しますか? |  |
| アプリの個人データの処理に関連するリスクを特定するために、定期的なデータ セキュリティとプライバシーレビュー (データ保護影響評価やプライバシー リスク評価など) が実行されますか? |  |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリケーションは Microsoft Identity Platform (Azure AD) と統合してシングル サインオンや API アクセスなどを行いますか。 | はい |
| 統合チェックリストの概要に示されている適用可能なすべてのベスト プラクティスを確認し、Microsoft ID プラットフォームしましたか? | はい |
| アプリで認証に MSAL (Microsoft 認証ライブラリ) または Microsoft Identity Web の最新バージョンを使用していますか? | true |
| アプリで上記のライブラリのいずれかを使用しない場合、どの認証ライブラリまたはライブラリを使用しますか? |  |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | すべて |
| アプリは継続的アクセス評価 (CAE) をサポートしています |  |
| アプリはコードに資格情報を保存しますか? |  |
| アプリとアドインは、microsoft Microsoft 365外部で追加の Microsoft API を使用Graph。 アプリまたはアドインで追加の Microsoft API を使用していますか? | 不要 |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graph を使用したデータ アクセス

>|   **Graphアクセス許可**  | **アクセス許可の種類** |          **妥当性**          | **Azure ADアプリ ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Calendars.ReadWrite | 委任 | 会議の一覧や検索&#8217;機能を有効にするには、ユーザーの予定表から情報を読み取る場合に使用します。 また、アイテムが Decisions から削除された場合に、予定表から特定の会議を削除するオプションもユーザーに与えます。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| Chat.ReadWrite | 委任 | 投票の決定を送信し、個々の議題アイテムのスピーカー リストを会議チャットに直接Microsoft Teamsします。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| Directory.Read.All | 委任 | テナント名や検証済みドメインなど、Office 365に関する基本情報を収集するために使用されます。 また、グループ メンバーシップの確認にも必要です。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| Files.Read.All | 委任 | ユーザーと共有されているファイルを読み取り、それらのファイルを PDF 会議帳に結合するために使用します。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| Files.ReadWrite.All | 委任 | 個人用ファイル注釈のサポートをユーザーに提供するために使用します。 注釈付きファイルは、ユーザーファイルの&#8217;にOneDrive for Business。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| Group.ReadWrite.All | 委任 | 会議の議題、関連ファイル、グループOffice 365&#8217;SharePointグループサイトにフォルダー構造を作成するために使用します。   注: 意思決定のユーザーは、組織のテナント内のリソース (グループなど) へのアクセス権を持Office 365できません。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| Mail.Send | 委任 | 意思決定のユーザーが会議参加者の通知 (議題の更新や共同執筆者向け会議へのリンクなど) を送信するために使用します。 メールは、会議の参加者または会議の所有者が選択した配布リストに移動します。 送信された通知と電子メールはすべて、Decisions ユーザーによってアクティブに行われます。  注: これにより、ユーザーは Decisions を介して受信トレイにアクセスできます。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| MailboxSettings.Read | 委任 | ユーザーの言語設定&#8217;識別するために使用します。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| Notes.ReadWrite | 委任 | 会議用のプライベート ノートブックをセットアップしてメモを取り、備考や質問を準備するために使用します。 また、グループが会議の使用を選択した場合、グループ会議の議OneNote共有ノートブック内に保存OneNote。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| Sites.ReadWrite.All | 委任 | 会議情報のプライベート チャネルにフォルダー構造を作成するために使用します。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| Tasks.ReadWrite | 委任 | タスクと決定を Microsoft Planner に同期するために使用します。 また、ユーザーはタスクや決定をエクスポートして、ユーザーにExcel。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| TeamsAppInstallation.ReadWriteForUser | 委任 | チャットに Decisions App をプログラムでインストールするために必要です。 これは、会議のエクスペリエンスに [決定] タブを追加する前に必要です。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| TeamsAppInstallation.ReadWriteForUser.All | 委任 | チャットに Decisions App をプログラムでインストールするために必要です。 これは、会議のエクスペリエンスに [決定] タブを追加する前に必要です。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| TeamsTab.Create | 委任 | [会議内/チャネル] タブを追加する必要Teams。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| TeamsTab.Read.All | 委任 | タブがインストールされていないか確認するために必要です。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| User.ReadBasic.All | 委任 | グループ メンバーと外部参加者の名前、写真、電子メール アドレスを表示するために使用します。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |
>| profile | 委任 | サインインに使用します。 | [1064f7e4-a9e2-467d-8d42-f45cc59f145d](../azure/1064f7e4-a9e2-467d-8d42-f45cc59f145d.md) |

>このアプリケーションには、追加の API が含まれる必要があります。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

