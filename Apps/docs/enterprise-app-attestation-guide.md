---
title: 構成証明Publisherとは
author: LGerrard
ms.author: legerrar
description: 構成証明プログラムのPublisher詳細
keywords: アプリ構成証明認定 365 アンケート appSource Publisher
ms.topic: conceptual
ms.service: attestation
ms.openlocfilehash: 06c64ab2aa09790a0c20ee9d555adf1177031f12
ms.sourcegitcommit: d85595f6518d8d05f0aee75380f51659908b6bcb
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/12/2021
ms.locfileid: "59287651"
---
# <a name="what-is-publisher-attestation"></a>構成証明Publisherとは

Publisher構成証明は、アプリ コンプライアンス プログラムの次Microsoft 365層です。 アプリ開発者は、ユーザーまたは IT 管理者がアプリのセキュリティとコンプライアンスを評価するときによく寄せられる質問を含む自己評価を完了する必要があります。 その後、Microsoft は、この情報を公開して、より簡単で、より時間の大きいな評価を行います。

> [!IMPORTANT]
> Microsoft は、提供された情報の一部を検証する必要があります。 アプリ開発者は、発行元の構成証明で提供する情報に対して責任を負います。 

Publisher構成証明は、Web アプリ (パートナー センターの商用マーケットプレースを通じて公開される SaaS アプリ) に適用されます。 SaaS アプリは現在プライベート プレビューに参加しています。参加に興味がある場合は、このフォームに記入 [してください](https://customervoice.microsoft.com/Pages/ResponsePage.aspx?id=v4j5cvGGr0GRqy180BHbR4cf3qxCU_RNtqjCSalFdSFUNDMzTVJKR0wzTEJRSFJVSk9OQUlOV0RJSyQlQCN0PWcu)。 構成証明には、次の Microsoft 製品と統合されるすべてのアプリも含まれます。

- Teams
- Word
- Excel
- PowerPoint 
- Outlook
- SharePoint
- Project
- OneNote

### <a name="benefits-for-it-admins"></a>IT 管理者のメリット
IT 管理者向け構成証明のPublisherの利点は次のとおりです。
-   組織で有効になっているアプリケーションのセキュリティとコンプライアンス対策に対する信頼度を追加しました
-   アプリのセキュリティとコンプライアンスの姿勢を確認する時間の短縮

### <a name="benefits-for-app-developers"></a>アプリ開発者のメリット 
開発者向けの構成証明のPublisherには、次の利点があります。 
-   時間の節約。 よく聞く質問に関する情報については、アプリの Microsoft Docs ページを表示する
-   企業組織のセキュリティとコンプライアンスの内部レビュータイムラインの高速化
-   透明度の向上
- Microsoft は追加コストでこのサービスを提供します
-   ストア内の他のアプリとの差別化
-   AppSource、管理センター、Microsoft 管理センターのTeamsドキュメント ページへのリンク
-   認定を開始するMicrosoft 365認定


## <a name="publisher-attestation-scope"></a>Publisher構成証明スコープ

構成証明プロセスは、アプリのセキュリティ、データ処理、コンプライアンス属性を詳細に示す広範なアンケートを中心に行います。 提供される情報は、組織の Microsoft 365 プラットフォームでアプリがアクティブ化された場合に公開されるアプリの機能全体を対象とします。

- データ処理: アプリが組織データを収集および保存する方法と、そのデータに対する組織の制御
- セキュリティ: アプリがデータを保護し、サイバー攻撃を検出して撃退するために必要なプロトコル、プロセス、および手順
- コンプライアンス: 必要な業界標準と仕様へのアプリの準拠
- 法的: 適用される立法上の彫像と規制に対するアプリの遵守

### <a name="confirmation-criteria"></a>確認条件

構成証明は、アプリのセキュリティ、データ処理、コンプライアンスのプラクティスを、ユーザーが特定した 80 を超えるリスク要因に対して[反映Microsoft Cloud App Security。](https://www.microsoft.com/microsoft-365/enterprise-mobility-security/cloud-app-security) 最初の構成証明ドキュメントの提出に失敗した場合、基本的な一貫性テストの基準では、構成証明は承認されません。 承認後、ドキュメント提出の誤った情報やアプリの失敗が報告または検出された場合、構成証明の確認状態は取り消されます。 いずれの場合も、開発者は、修正プロセスを支援するために関連する詳細情報を受け取る。

### <a name="confirmation-time-frame"></a>確認の時間枠

構成証明は、申請時から 1 年間有効です。 ただし、アプリが暫定的な期間中に更新または変更された場合、開発者は構成証明を修正して再提出する必要があります。

## <a name="reviewing-an-apps-publisher-attestation"></a>アプリの構成証明のPublisherする

開発者は、アプリ用に作成された Microsoft ドキュメント ページで、Publisher構成証明の結果の詳細情報を確認できます。 Publisher 構成証明または Microsoft 365 認定を完了したすべてのアプリが一覧表示され、各リストには、コンプライアンス プログラムで達成されたレベルが明確に表示されます。

**構成証明 [を完了](https://docs.microsoft.com/microsoft-365-app-certification/teams/iglobe-mipa-your-personal-assistant?pivots=mcas)したアプリの例については、MIPA の一覧Publisherしてください。** 

## <a name="learn-more"></a>詳細情報

* [Microsoft 365アプリ コンプライアンス プログラムの概要](~/overview.md)
* [検証のPublisher](https://docs.microsoft.com/azure/active-directory/develop/publisher-verification-overview)
* [完全なPublisher構成証明](~/docs/attestation.md)  
* [認定とはMicrosoft 365ですか?](~/docs/enterprise-app-certification-guide.md)
