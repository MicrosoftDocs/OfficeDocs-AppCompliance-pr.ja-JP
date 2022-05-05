---
title: Office ドキュメントの Wrike の概要
ms.author: elmalova
author: elenamalova
manager: tonybal
ms.date: 03/23/2020
ms.topic: article
ms.service: attestation
certification_type: certified
description: Office ドキュメント、データ処理ポリシー、Microsoft Cloud App Security アプリ カタログ情報、CSA STAR レジストリ内のセキュリティ/コンプライアンス情報に関する Wrike で利用可能なすべてのセキュリティ情報とコンプライアンス情報。
zone_pivot_groups: app-info-data-mcas
ms.openlocfilehash: c4407cdf68b92369e45c798ef76e051980e6c23a
ms.sourcegitcommit: 7a7de9f48f6cf5b6acd435412477b6a59127f19a
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/05/2022
ms.locfileid: "65225621"
---
# <a name="wrike-for-office-documents-overview"></a>Office ドキュメントの Wrike の概要

<p></p><a href="https://aka.ms/appcertification" alt="This Microsoft 365 Certified app has been reviewed by Microsoft against industry standards and controls for security, compliance, and data handling practices. Where applicable, Microsoft has verified the developer's claims of compliance with reasonable and effective practices." target="_blank"><img alt="Click here for more information on the Microsoft Certified app program." src="../media/certified.png" width="650" /></a>
<p>開発者が最終更新日: 2020 年 3 月 23 日</p>

* <a href="https://appsource.microsoft.com/product/office/WA104379841" target="_blank">AppSource で表示する</a>

::: zone pivot="general"

### <a name="general-information"></a>一般情報

Wrike Inc. から Microsoft に提供される情報:

| **Information** | **応答** |
|:----------------|:-------------|
| アプリ名 | Office ドキュメントの Wrike |
| ID | WA104379841 |
| サポートされているOffice 365 クライアント | Windows、Word 2013 以降、Windows、Windows PowerPoint 2013 以降、mac、Excel on the web、Word 2016 以降の mac でのExcel 2016以降のExcel 2016以降Excel 2016 Excel 2016Word on the web、mac PowerPoint 2016 以降、PowerPoint on the web |
| パートナー会社名 | Wrike Inc. |
| パートナー Web サイトの URL | [https://www.wrike.com/](https://www.wrike.com/) |
| プライバシー ポリシーの URL | [https://www.wrike.com/privacy/](https://www.wrike.com/privacy/) |
| 使用条件の URL | [https://www.wrike.com/terms/](https://www.wrike.com/terms/) |

 [!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="data"

### <a name="how-the-app-handles-data"></a>アプリがデータを処理する方法

この情報は Wrike Inc. によって提供されています。このアプリが組織データを収集して保存する方法と、アプリが収集するデータに対して組織が持つコントロールについて説明しています。

#### <a name="data-access-using-microsoft-graph"></a>Microsoft Graphを使用したデータ アクセス

このアプリ[で必要な Microsoft Graphアクセス許可](/graph/permissions-reference)を一覧表示します。

>このアプリケーションでは、Microsoft Graphは使用されません。

#### <a name="data-access-using-other-microsoft-apis"></a>他の Microsoft API を使用したデータ アクセス

Microsoft 365に基づいて構築されたアプリとアドインでは、Microsoft Graph以外の追加の Microsoft API を使用して、組織の識別可能な情報 (OII) を収集または処理できます。 このアプリで使用Graph Microsoft 以外の Microsoft API を一覧表示します。

>| **API** |  **OII は収集されますか?** |  **収集される OII は何ですか?** | **OII を収集するための正当な理由** | **OII は格納されますか?** | **OII を格納するための正当な理由** |
>|:-------------------|:-------------------|:--------------------------|:--------------------------|:---------------------------------------------------|:--------------------------|
>| JavaScript API for Office | はい | アドインは、Office.js API を使用して、Office アプリケーションと統合します。 |  | Wrike のデータベースには、組織データは格納されません。 |  |

#### <a name="non-microsoft-services-used"></a>使用されていないMicrosoft サービス

アプリが Microsoft 以外のサービスと組織データを転送または共有する場合は、アプリが使用する Microsoft 以外のサービス、転送されるデータを一覧表示し、アプリがこの情報を転送する必要がある理由の正当な理由を含めます。

>| **Microsoft サービス以外のすべての OII は、** |  **転送される OII は何ですか?** | **OII を転送するための正当な理由** |
>|:-------------------|:--------------------------|:--------------------------|
>| Wrike には、一部のデータにアクセスできる次のベンダーとの統合があります。Marketo は電子メール リード キャプチャ サービスです。名前と電子メールのみが提供されます。 Outreach はクラウドベースのセールス エンゲージメントです。名前と電子メールのみが提供されます。 Salesforce CRM システム - 顧客の連絡先情報と課金情報 (機密データなし) があります。 Zuora - 課金と請求のお客様。 すべてのベンダーに対して DPA が用意されています。 |  | JS Office API を使用しますが、組織の情報を収集/処理/保存することはありません。 |



#### <a name="telemetry-data"></a>テレメトリ データ

組織の識別可能な情報 (OII) またはエンド ユーザー識別情報 (EUII) は、このアプリケーションのテレメトリまたはログに表示されますか? はい場合は、保存されるデータと保持ポリシーと削除ポリシーについて説明します。

>いいえ

#### <a name="organizational-controls-for-data-stored-by-partner"></a>パートナーによって格納されたデータの組織コントロール

組織の管理者がパートナー システムで自分の情報を制御する方法について説明します。削除、保持、監査、アーカイブ、エンド ユーザー ポリシーなど。

>Wrike にはマルチテナント アーキテクチャがあり、顧客のメタデータに基づいてアクセス制御によって顧客&#8217;データを論理的に分離します。 このメタデータは、特定の Wrike アカウント内のロールベースのアクセス規則に従って、特定のテナントとそのアクセス権に関連付けられます。 データは論理的に分離され、分離され、データへのアクセスはアプリケーションを通じてのみ使用でき、セキュリティとプライバシーが確保されます。 アプリケーション レベルのセキュリティは、テナントが別のテナントが所有するアプリケーション データへのアクセスまたは変更をブロックします。 Wrike のアプリケーションには、広範な認証、ロールベースのアクセス制御、承認、およびデータ共有と制御メカニズムがあります (承認されたユーザーに対してのみデータ アクセスを許可するメカニズムを参照 https://help.wrike.com/hc/en-us/articles/209603589-Access-Roles してください https://help.wrike.com/hc/en-us/articles/209602969) 。 さらに、保存時の暗号化は、Web アプリケーションと API の両方を介してファイル ストレージ内の Wrike サーバーにアップロードされたユーザー ファイルに適用されます。ファイルは AES 256 ビット暗号化を使用して自動的に暗号化されます。 さらに、すべてのサーバーは、ファイル システムの暗号化を使用して保存時に暗号化され、さらに Wrike では、顧客が管理する暗号化キー用の Wrike Lock アドインを提供していますhttps://help.wrike.com/hc/en-us/articles/360012347934-Wrike-Lock。詳細については、以下をご覧くださいhttps://www.wrike.com/add-on-wrike-lock/。 データ セキュリティの追加レイヤーとして、Wrike は監査とレポート機能を提供しています。これにより、管理者は完全なセキュリティ レビューを実行しながら、Wrike アカウントで何が発生しているかの可視性を高めることができます。詳細については、以下をご覧ください https://help.wrike.com/hc/en-us/articles/209606309-Audit-Reports。 最後に、Wrike には、既存のデータ共有 https://help.wrike.com/hc/en-us/articles/360002004534-Access-Reportsを完全に監査するのに役立つアクセス ロールの詳細な追跡を可能にする機能が用意されています。
顧客データへのアクセスは、次の 2 つのケースで考慮できます。
- Wrike サポート チームによるアクセス: 問題のトラブルシューティングまたは検証を行う場合は、アカウントにアクセスするためのサポートが必要です。そのアクセス権は、ユーザーのみが許可できます。 これは、サポート チームに帯域外で提供するシステム生成セキュリティ トークンによって有効になり、サポートは限られた時間の間、問題の解決をより深く掘り下げることができます。 この体系的なアプローチにより、Wrike に格納されているデータに対する追加の機密性が確保されます。
- Wrike 運用チームによるアクセス: Wrike 運用チームは、監視、修正プログラムの適用、更新、新しいビルドの運用環境への配信など、運用環境のメンテナンスとサポートを担当します。この場合のアクセスは、手続き上および技術的な側面の両方から厳密に禁止されており、VPN、2FA、個人証明書を含むがこれらに限定されない強力な承認制御が実施されています。さらに、HIDS (ホストベースの侵入検出システム) を使用して詳細に監視され、Wrike Operational Security チームによって確認されます。 Amazon KMS (Wrike Lock 機能) の場合、顧客データは Wrike データベースに暗号化されて格納されるため、データは Wrike Operational チームによって直接的または間接的に利用できません。データは、お客様の Amazon KMSへのアクセスを使用して復号化できるためです。これは、お客様のみが管理および制御します。

#### <a name="human-review-of-organizational-information"></a>組織情報の人間によるレビュー

人間は、このアプリによって収集または保存される組織識別可能な情報 (OII) データの確認または分析に関与していますか?

>いいえ

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

::: zone pivot="mcas"

[Microsoft Cloud App Security](https://www.microsoft.com/enterprise-mobility-security/cloud-app-security) カタログからの情報が次に表示されます。

<iframe height='1020' title='Microsoft Cloud App Security情報' src='https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522' frameborder='no'></iframe>

<a href="https://appmcasinfoprod.azurewebsites.net/#/dashboard/21522" target="_blank">新しいタブで表示する</a>

[!INCLUDE [Corrections or suggestions contact information](../includes/corrections-or-suggestions.md)]

::: zone-end

