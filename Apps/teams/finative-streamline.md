---
title: Finative による Streamline のアプリケーション情報
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 05/24/2022
ms.topic: article
ms.service: attestation
certification_type: attested
description: Streamline で利用可能なすべてのセキュリティ情報とコンプライアンス情報、データ処理ポリシー、Microsoft Cloud App Securityアプリ カタログ情報、CSA STAR レジストリのセキュリティ/コンプライアンス情報。
zone_pivot_groups: app-info-data-security-compliance-privsection-zerotrust
ms.openlocfilehash: 42ee00766760eca68fde3804a83209de5b4a6fed
ms.sourcegitcommit: ef767e1079411056cb3ca86d6b29084e31b0ef1c
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/26/2022
ms.locfileid: "65692437"
---
# <a name="streamline"></a>合理化

<p></p>
<img alt="Publisher Attestation: The information on this page is based on a self-assessment report provided by the app developer on the security, compliance, and data handling practices followed by this app. Microsoft makes no guarantees regarding the accuracy of the information." src="../media/attested.png" width="650" />
<p>開発者が最終更新日: 2022 年 4 月 7 日</p>

* <a href="https://teams.microsoft.com/l/app/aa6e7fb6-34ac-4947-9c13-3565c66e368b" target="_blank">Teams ストアで表示する</a>
* <a href="https://appsource.microsoft.com/product/office/WA200004100" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Finative から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | 合理化 |
| ID | WA200004100 |
| サポートされているOffice 365 クライアント | Microsoft Teams |
| パートナー会社名 | Finative |
| 会社の Web サイト | [https://finative.it](https://finative.it) |
| アプリの使用条件 | [https://finative.it/streamline/terms-of-use/](https://finative.it/streamline/terms-of-use/) |
| アプリのコア機能 | 会議のエクスペリエンスを合理化することで、生産性を向上させます。 |
| 会社の本社の場所 | オランダ (the) |
| アプリ情報ページ | [https://finative.it/streamline/](https://finative.it/streamline/) |
| アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか? | IsvHosted |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織のデータを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて Finative によって提供されています。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリまたは基になるインフラストラクチャは、Microsoft のお客様またはデバイスに関連するデータを処理しますか? | はい |
| アプリによって処理されるデータは何ですか? | Azure AD ユーザー ID の |
| アプリは TLS 1.1 以降をサポートしていますか? | はい |
| アプリまたは基になるインフラストラクチャには、Microsoft の顧客データは格納されますか? | はい |
| データベースに格納されているデータは何ですか? | アプリ内で作成されたフォルダーへの Userids、tenantid、OneDrive リンク |
| 基になるインファ構造が Microsoft 顧客データを処理または格納する場合、このデータは地理的にどこに保存されますか? | オランダ (the) |
| データの借用と廃棄プロセスが確立されていますか? | はい |
| アカウントの終了後、データはどのくらいの期間保持されますか? | 90 日未満 |
| データ アクセス管理プロセスが確立されていますか? | はい |
| 顧客データまたは顧客コンテンツをサード パーティまたはサブプロセッサに転送しますか? | 不要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="security"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

| **Information** | **応答** |
|:----------------|:-------------|
| アプリで年間侵入テストを実行していますか? | 不要 |
| バックアップと復元の戦略など、文書化されたディザスター リカバリー計画はアプリに含まれていますか? | はい |
| お使いの環境では、従来のマルウェア対策保護またはアプリケーション制御が使用されていますか? | TraditionalAntiMalware |
| セキュリティの脆弱性をインデントおよびリスク ランク付けするための確立されたプロセスはありますか? | はい |
| パッチを適用するためのサービス レベル アグリーメント (SLA) を管理するポリシーはありますか? | 不要 |
| パッチ ポリシー SLA に従ってパッチ管理アクティビティを実行しますか? | 不要 |
| お使いの環境にサポートされていないオペレーティング システムまたはソフトウェアはありますか? | 不要 |
| アプリと、それをサポートするインファ構造に対して四半期ごとの脆弱性スキャンを行いますか? | 不要 |
| 外部ネットワーク境界にファイアウォールがインストールされていますか? | 不要 |
| 変更要求を運用環境にデプロイする前に、変更要求を確認および承認するために使用される、確立された変更管理プロセスはありますか? | はい |
| 追加のユーザーは、元の開発者によって運用環境に送信されたすべてのコード変更要求を確認して承認していますか? | はい |
| セキュリティで保護されたコーディングプラクティスでは、OWASP Top 10 などの一般的な脆弱性クラスが考慮されますか? | はい |
| 多要素認証 (MFA) が有効になっているのは次のとおりです。 | CodeRepositories、DNSManagement、Credential |
| 従業員アカウントのプロビジョニング、変更、削除のための確立されたプロセスはありますか? | はい |
| アプリをサポートするネットワーク境界の境界に侵入検出と防止 (IDPS) ソフトウェアがデプロイされていますか? | 不要 |
| アプリをサポートするすべてのシステム コンポーネントにイベント ログ記録を設定していますか? | はい |
| すべてのログは、潜在的なセキュリティ イベントを検出するために、人間または自動化されたツールによって定期的に確認されますか? | はい |
| セキュリティ イベントが検出されると、トリアージのために従業員にアラートが自動的に送信されますか? | 不要 |
| 正式な情報セキュリティ リスク管理プロセスが確立されていますか? | 不要 |
| 正式なセキュリティ インシデント対応プロセスが文書化され、確立されていますか? | 不要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="compliance"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリは、医療保険の可搬性と会計法 (HIPAA) に準拠していますか? | 不要 |
| アプリは Health Information Trust Alliance、Common Security Framework (HITRUST CSF) に準拠していますか? | 不要 |
| アプリはサービス組織コントロール (SOC 1) に準拠していますか? | 不要 |
| アプリはサービス組織コントロール (SOC 2) に準拠していますか? | 不要 |
| アプリはサービス組織コントロール (SOC 3) に準拠していますか? | 不要 |
| アプリとそのサポート環境に対して、年間 PCI DSS 評価を実行していますか? | 不要 |
| アプリの国際標準化機構 (ISO 27001) は認定されていますか? | 不要 |
| アプリは国際標準化機構 (ISO 27018) に準拠していますか? | 不要 |
| アプリは国際標準化機構 (ISO 27017) に準拠していますか? | 不要 |
| アプリは国際標準化機構 (ISO 27002) に準拠していますか? | 不要 |
| アプリの連邦リスクと承認管理プログラム (FedRAMP) は準拠していますか? | 不要 |
| アプリは家族教育の権利とプライバシーに関する法律 (FERPA) に準拠していますか? | 不要 |
| アプリは、子どものオンラインプライバシー保護法 (COPPA) に準拠していますか? | はい |
| アプリはSarbanes-Oxley法 (SOX) に準拠していますか? | 該当なし |
| アプリは NIST 800-171 に準拠していますか? | 不要 |
| アプリは Cloud Security Alliance (CSA Star) の認定を受けていますか? | 不要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="privsection"

| **Information** | **応答** |
|:----------------|:-------------|
| GDPR またはその他のプライバシーまたはデータ保護の要件または義務 (CCPA など) はありますか? | はい |
| アプリには、顧客データの収集、使用、共有、および格納方法を説明する外部向けのプライバシーに関する通知がありますか? | はい |
| プライバシー ポリシーの URL | https://finative.nl/streamline/privacy-statement |
| アプリは、法的影響や同様の影響を及ぼす可能性のあるプロファイリングを含め、自動化された意思決定を実行しますか? | 不要 |
| アプリは、プライバシーに関する通知 (マーケティング、分析など) に記載されていない第 2 の目的で顧客データを処理しますか? | 不要 |
| 機密データの特別なカテゴリ (例: 人種的または民族的起源、ポリティカルオピニオン、宗教または哲学的信念、遺伝子または生体認証データ、健康データ)、または違反通知法の対象となるデータのカテゴリを処理しますか? | 不要 |
| アプリは未成年者 (16 歳未満の個人) からデータを収集または処理しますか? | 不要 |
| アプリには、要求に応じて個人の個人データを削除する機能はありますか? | はい |
| アプリには、要求に応じて個人の個人データの処理を制限または制限する機能がありますか? | はい |
| アプリは個人に個人データを修正または更新する機能を提供しますか? | 該当なし |
| アプリの個人データの処理に関連するリスクを特定するために、定期的なデータ セキュリティとプライバシーのレビュー (データ保護影響評価やプライバシー リスク評価など) が実行されますか? | 不要 |

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="zerotrust"

| **Information** | **応答** |
|:----------------|:-------------|
| アプリケーションは、シングル サインオン、API アクセスなどのために Microsoft Identity Platform (Azure AD) と統合されますか? | はい |
| Microsoft ID プラットフォーム統合チェックリストに記載されているすべての適用可能なベスト プラクティスを確認し、遵守しましたか? | はい |
| アプリは、最新バージョンの MSAL (Microsoft Authentication Library) または Microsoft Identity Web を認証に使用していますか? | はい |
| アプリは条件付きアクセス ポリシーをサポートしていますか? | はい |
| サポートされているポリシーの種類を一覧表示する | ID |
| アプリは継続的アクセス評価 (CAE) をサポートしていますか? | 不要 |
| アプリは、コードに資格情報を格納していますか? | 不要 |
| Microsoft 365用のアプリとアドインでは、Microsoft Graphの外部で追加の Microsoft API が使用される場合があります。 アプリまたはアドインは、追加の Microsoft API を使用していますか? | 不要 |

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

>|   **Graphアクセス許可**  | **アクセス許可の種類** |          **妥当性**          | **Azure AD アプリ ID** |
>|:------------------------|:--------------------|:------------------------------------|:--------------------|
>| Calendars.ReadWrite | 委任 | ユーザーのアクションに基づいてユーザー スケジュールを表示および編集するために必要です。 | [7f6565a7-45e4-4bba-94d4-bac64886ed83](../azure/7f6565a7-45e4-4bba-94d4-bac64886ed83.md) |
>| Files.ReadWrite.All | 委任 | ユーザー&#8217;のOneDrive for Businessに添付ファイルやその他のファイルを格納するために必要です。 | [7f6565a7-45e4-4bba-94d4-bac64886ed83](../azure/7f6565a7-45e4-4bba-94d4-bac64886ed83.md) |
>| Notes.Create | 委任 | 会議の議題に基づいて OneNotes を作成するために必要です。 | [7f6565a7-45e4-4bba-94d4-bac64886ed83](../azure/7f6565a7-45e4-4bba-94d4-bac64886ed83.md) |
>| User.Read | 委任 | ユーザー&#8217;のプロファイルをサインインして読み取り、Streamline アプリへのアクセスを認証および承認するために必要です。 | [7f6565a7-45e4-4bba-94d4-bac64886ed83](../azure/7f6565a7-45e4-4bba-94d4-bac64886ed83.md) |
>| User.ReadBasic.All | 委任 | 他のユーザーを検索してタスク、ロール、議題などに割り当てる必要があります。ログイン ユーザーがアクセス権を持つユーザーのみが表示されます。 | [7f6565a7-45e4-4bba-94d4-bac64886ed83](../azure/7f6565a7-45e4-4bba-94d4-bac64886ed83.md) |
>| User.Read | 委任 | ログインしているユーザーに関する基本情報をアプリに表示する | [c7cdd862-2527-49ea-b873-0c5f51a83292](../azure/c7cdd862-2527-49ea-b873-0c5f51a83292.md) |
>| メール | 委任 | ウェルカム メールをユーザーに送信するには | [c7cdd862-2527-49ea-b873-0c5f51a83292](../azure/c7cdd862-2527-49ea-b873-0c5f51a83292.md) |
>| openid | 委任 | ユーザーにサインインする | [c7cdd862-2527-49ea-b873-0c5f51a83292](../azure/c7cdd862-2527-49ea-b873-0c5f51a83292.md) |
>| profile | 委任 | ログインしているユーザーに関する基本情報をアプリに表示する | [c7cdd862-2527-49ea-b873-0c5f51a83292](../azure/c7cdd862-2527-49ea-b873-0c5f51a83292.md) |

>このアプリケーションには、追加の API はありません。

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

