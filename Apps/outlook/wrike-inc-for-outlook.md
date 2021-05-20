---
title: Wrike Inc. Outlook Wrike for Outlookアプリケーション情報
ms.author: elmalova
author: elenamalova
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: wrike for Outlook、そのデータ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、および CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関して利用可能なすべてのセキュリティおよびコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: 1ee6c98b2513459c588100a9b3b19ba529d98af0
ms.sourcegitcommit: a44420a99a1a3a9d0e49f4be66f266e2d4ca7bbb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/19/2021
ms.locfileid: "52553698"
---
# <a name="wrike-for-outlook"></a>Wrike for Outlook

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2020 年 3 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104381120" target="_blank">AppSource での表示</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Wrike Inc. から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Wrike for Outlook |
| ID | WA104381120 |
| Office 365サポートされているクライアント | Outlook 2013 以降の mac Windows、Outlook 2016 以降、iOS の Outlook、web 上の Outlook、Android Outlook |
| パートナー会社名 | Wrike Inc. |
| パートナー Web サイトの URL | [https://wrike.com/](https://wrike.com/) |
| プライバシー ポリシーの URL | [https://www.wrike.com/security/privacy](https://www.wrike.com/security/privacy) |
| 利用規約の URL | [https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US](https://go.microsoft.com/fwlink/?LinkID=521715&amp;omkt=en-US) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は、このアプリが組織データを収集および保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて Wrike Inc. から提供されています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft サービスを使用したデータ アクセスGraph

このアプリが[必要とする microsoft Graphアクセス許可](https://docs.microsoft.com/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft アプリケーションをGraph。

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

アプリとアドインは、組織Microsoft 365情報 (OII) を収集または処理するために、Microsoft Graph 以外の追加の Microsoft API を使用する場合があります。 このアプリで使用する Microsoft 以外の Microsoft API Graph一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集する理由** | **OII は格納されていますか?** | **OII を格納する理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript API for Office | はい | アドインは、Office.js API を使用して、アプリケーションOfficeします。 |  | Wrike のデータベースには組織データは格納されません。 |  |

#### <a name="non-microsoft-services-used"></a>非使用Microsoft サービス

アプリが組織データを Microsoft 以外のサービスと転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリでこの情報を転送する必要がある理由の理由を説明します。

>| **OII のすべての非Microsoft サービスに転送されます。** |  **どのような OII が転送されますか?** | **OII を転送する理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike には、一部のデータにアクセスできる次のベンダーとの統合があります。Marketo は電子メール リード キャプチャ サービスであり、名前と電子メールだけが提供されます。 Outreach はクラウドベースの販売契約であり、名前と電子メールだけが提供されます。 Salesforce CRM システム - 顧客の連絡先情報と請求 (機密データなし) 情報があります。 Zuora - 請求と請求の顧客。 すべてのベンダーに対して DPA が設定されています。 |  | JS Office API を使用しますが、組織情報を収集/処理/保存することはできません。 |



#### <a name="telemetry-data"></a>テレメトリ データ

組織識別可能な情報 (OII) またはエンド ユーザー識別可能な情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はいの場合は、保存されているデータと保持ポリシーと削除ポリシーについて説明します。

>いいえ

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって保存されるデータの組織的な制御

組織の管理者がパートナー システムで情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンドユーザー ポリシーなど。

>Wrike には、顧客のメタデータに基づくアクセス制御を通じて&#8217;データを論理的に分離するマルチテナント アーキテクチャがあります。 このメタデータは、特定の Wrike アカウント内の役割ベースのアクセス ルールに従って、特定のテナントとそのアクセス権に関連付けられる。 データは論理的に分離され分離され、データへのアクセスは、セキュリティとプライバシーを確保するためにアプリケーションを通じてのみ利用できます。 アプリケーション レベルのセキュリティは、テナントが別のテナントが所有するアプリケーション データへのアクセスや変更をブロックします。 Wrike のアプリケーションには、広範な認証、役割ベースのアクセス制御、承認、およびデータ共有および制御メカニズムがあります (承認されたユーザーのデータ アクセスのみを許可する機能を参照してください https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles https://help.wrike.com/hc/en-us/articles/209602969) )。 さらに、保存時の暗号化は、Web アプリケーションと API の両方を介してファイル ストレージ内の Wrike サーバーにアップロードされたユーザー ファイルに適用されます。ファイルは、AES 256 ビット暗号化を使用して自動的に暗号化されます。 さらに、すべてのサーバーは、ファイル システムの暗号化を使用して保存時に暗号化され、さらに Wrike は、顧客が管理する暗号化キー用の Wrike Lock アドインを提供しています。 https://www.wrike.com/add-on-wrike-lock/ https://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock データ セキュリティの追加層として、Wrike には監査機能とレポート機能が用意されています。これにより、管理者は Wrike アカウントで何が起こっているかの可視性を高めながら、完全なセキュリティ レビューを実行できます。詳細については、以下を参照してください。 https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports 最後に、Wrike は、アクセス ロールの詳細な追跡を可能にする機能を提供し、お客様が既存のデータ共有を完全に監査するのに役立ちます https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reports 。
顧客データへのアクセスは、次の 2 つの場合に考慮できます。
- Wrike サポート チームによるアクセス: 問題のトラブルシューティングまたは確認の場合、アカウントにアクセスするにはサポートが必要です。そのアクセス権は、ユーザーだけが付与できます。 これは、サポート チームに帯域外で提供するシステム生成セキュリティ トークンによって有効になります。これにより、サポートは限られた時間の間、問題の解決について深く掘り下げられています。 このシステム的なアプローチにより、Wrike に保存されているデータに対する追加の機密性が確保されます。
- Wrike の運用チームによるアクセス: Wrike の運用チームは、監視、パッチ適用、更新、新しいビルドの運用への配信など、運用環境の保守とサポートを担当します。この場合のアクセスは、手続き的および技術的な側面の両方から厳しく禁止され、VPN、2FA、個人証明書を含むがこれらに限定されない強力な承認制御が実施されています。さらに、HIDS (ホストベースの侵入検出システム) を使用して詳細に監視され、Wrike Operational Security チームによって確認されます。 Amazon KMS (Wrike ロック機能) の場合、顧客データは Wrike データベースに暗号化されて保存されます。そのため、顧客の Amazon KMS へのアクセスを使用してデータを復号化できるのは顧客の Amazon KMS のみによって管理および制御されるため、データは Wrike Operational チームが直接または間接的に利用することはできません。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

以下[に、Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security)カタログの情報が表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no' style='width: 100%;'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

