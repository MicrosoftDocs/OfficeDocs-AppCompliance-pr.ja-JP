---
ms.author: oromalle
title: Microsoft 365認定 - 初期ドキュメント提出ガイド
author: orionomalley
description: Microsoft 365認定申請ガイドの詳細ビュー
keywords: アプリ認定チームMicrosoft 365コンプライアンス m365 の初期ドキュメント提出
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 0f879ce6b02fb469b0210500e4706d468ccb4011
ms.sourcegitcommit: 3e72bc447a90cd8b0313dab55f6a9374be8ae358
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 12/01/2021
ms.locfileid: "61261679"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365認定 - 最初のドキュメント提出ガイド

最初のドキュメント提出は、認定の事前評価フェーズの一部です。 提供される情報は、認定アナリストに対して、評価の対象になるコントロールとシステム コンポーネントを特定するために必要なバックグラウンドを提供します。 このドキュメントは、最初のドキュメントの提出に期待される機能の例としてのみ使用することを目的とします。 提供するドキュメントは、ソリューションの設計、実装、および管理方法によって異なります。

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか?
- サービスとしてのインフラストラクチャ (IaaS) は、クラウド サービス プロバイダーがインフラストラクチャ コンポーネントをホストするクラウド サービス モデルですが、ISV は引き続き仮想マシン/オペレーティング システム、データ ストア、ネットワーク コンポーネントなどのコンポーネントを個別に展開および管理する責任があります。 その例として、Azure Virtual Machine と Azure Disk Storage。
- サービスとしてのプラットフォーム (PaaS) は、インフラストラクチャ コンポーネントがクラウド サービス プロバイダーによって管理されるクラウド サービス モデルです。 ISV は、独自のアプリケーションとサービスの展開のみを担当します。 この例は、Azure App Services、Azure Functions、および Azure CDN。
- このコンテキストでホストされる ISV は、クラウド サービス プロバイダーが使用されません。 ISV は、独自のサーバー、ディスク、ネットワークをオンプレミスで個別に物理的に管理します。
- このコンテキストのハイブリッドは、上記のモデルの 1 つが使用されるという意味です。 たとえば、一部の ISV は、IaaS サービスと PaaS サービスの混合を使用してアプリをサポートする場合や、オンプレミスの ISV ホスト型コンポーネントを持ち、他の ISV をクラウド サービス プロバイダーにアウトソーシングする場合があります。 複数のサービス モデルのいずれかを使用する場合は、[ハイブリッド] を選択します。

## <a name="penetration-test-report"></a>侵入テスト レポート

過去 12 か月以内に完了した日付を示す完全侵入テスト レポートを含める必要があります。 
-   このレポートは、手動の侵入テストから作成する必要があります。自動スキャン/テスト ツールの出力にすることはできません。
-   このレポートには、アプリ/アドインの展開をサポートする環境と、アプリ/アドインの操作をサポートする追加の環境が含まれる必要があります。


## <a name="system-component-inventory"></a>System Component Inventory

サポート インフラストラクチャで使用されるすべてのシステム コンポーネントの最新の inventroy。 これは、評価フェーズを実行する際のサンプリングに役立ちます。 環境に PaaS が含まれる場合は、使用されるすべての PaaS サービスの詳細を提供できる場合に役立ちます。

**注:** IaaS/PaaS には、ISV コントロールの下に置くハードウェアは含めかねない。  この場合は、すべてのウイルスリソースのリストまたはスクリーンショットを提供してください。

**例:** 

|アセット名|    アセットの種類| 説明|    製造元|   モデル|
|-|-|-|-|-|
|D212|  Windowsコンピューター|   仮想コンピューター|    該当なし| N/A|
|LT101| ノート PC| ワークステーション|    Microsoft|  Surface 3|
|C2938| スイッチ| スイッチ|該当なし|N/A|     
|LXM2|  Linux マシン|  テスト マシン|該当なし|N/A|       


## <a name="software-inventory"></a>ソフトウェア インベントリ

スコープ内環境内で使用されるすべてのソフトウェアとバージョンを含む、すべてのソフトウェア資産の最新のインベントリ。

**例:**

|ソフトウェア|  発行者|  バージョン|     用途|
|-|-|-|-|
|Windows Server|    Microsoft 2016 | ビルド 14393| 実稼働環境のサーバー オペレーティング システム|.
|Linux Ubuntu|  N/A|    16.04 (Xenial)| DMZ 内で使用されているサーバー オペレーティング システム。|
|ESXi|  VMWare| 6.5.0 (ビルド 13004031)| 仮想サーバーをサポートするために使用します。|
|Mysql (Windows)|   N/A|    8.0.2.1|    チャット履歴を格納するデータベース サーバー。|
|Tomcat|        Apache| 7.0.92| カスタマー ポータル。|
|IIS|   Microsoft|  10.0|   API をサポートします。|


## <a name="third-party-dependencies"></a>サード パーティの依存関係

現在実行中のバージョンとアプリ/アドインで使用される依存関係の一覧を示すドキュメント。

**例:**

|Web 依存関係|  現在のバージョンの使用|
|-|-|
|JQuery|    3.5.1|
|React| 16.13.1|
|ブートストラップ| .4.5.2 |
|Express|   4.17.1|
|Angular|   10.0.14|
|AngularJS| 1.8.0|


## <a name="public-ip-addresses"></a>パブリック IP アドレス

サポート インフラストラクチャで使用されるパブリック IP アドレスと URL の詳細。 これは、使用範囲を分割するために適切なセグメンテーションが実装されていない限り、環境に割り当てられた完全なラウタブル IP 範囲を含める必要があります (セグメンテーションの十分な証拠が必要になります)。

**例:** 

|URL|  IP アドレス|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|  40.113.200.201|
|https://customerapi.contoso.com|   40.113.200.202|
|https://bot.contoso.com|   40.113.200.202|
|N/A (Jump Server)| 40.113.200.200|


## <a name="resource-endpoints"></a>リソース エンドポイント

API 名 エンドポイント アドレス Contoso Customer API    https://customerapi.contoso.com Contoso Bot Service Contoso Files https://bot.contoso.com API   https://filesapi.contoso.com

内部的に開発されたエンドポイント、および外部リソース エンドポイントを含む、アプリで使用されるすべての API エンドポイントの完全な一覧。 環境スコープを理解するために、環境内で API エンドポイントの場所を指定します。

**例:**

|API 名|  エンドポイント アドレス|
|-|-|
|Contoso カスタマー API|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|Contoso Files API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>アーキテクチャ図

アプリ/アドインのサポート インフラストラクチャの概要を表す論理アーキテクチャ図。 これには、すべてのホスティング環境と、アプリ/アドインをサポートするサポート インフラストラクチャが含まれる必要があります。 この図は、認定アナリストがスコープ内のシステムを理解し、サンプリングを決定するのに役立つ環境内のすべてのサポート システム コンポーネントを示す必要があります。 使用するホスティング環境の種類も指定してください。ISV Hosted、IaaS、PaaS、または Hybrid。 PaaS を使用する場合は、環境内でサポート サービスを提供するために使用されるさまざまな PaaS サービスを指定してください。

![アーキテクチャ図](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>データFlow図

Flowの詳細を示す図を示します。
-   アプリ/アドイン (顧客データを含む) に対するデータ フロー。
-   サポート インフラストラクチャ内のデータ フロー (該当する場合)
-   データの保存場所と保存場所、外部サード パーティへのデータの渡し方 (第三者の詳細を含む)、およびオープン/パブリック ネットワークを通して転送中および保存時にデータが保護される方法を強調表示する図。

![データFlow図](../media/Dataflowdiagram.png)



