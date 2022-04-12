---
ms.author: oromalle
title: Microsoft 365認定 - 初期ドキュメント提出ガイド
author: orionomalley
manager: tonybal
description: 最初のドキュメントの提出は、認定の事前評価フェーズの一部です。
keywords: アプリ認定チームMicrosoft 365セキュリティ コンプライアンス m365 初期ドキュメントの提出
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: 23c3cf7a64025bb7269adb35175e8d87bc64224e
ms.sourcegitcommit: ec1d4f7013722fe672830e3664b0fb8b0f33bd37
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/12/2022
ms.locfileid: "64784506"
---
# <a name="microsoft-365-ceritification---initial-document-submission-guide"></a>Microsoft 365認定 - 初期ドキュメント提出ガイド

最初のドキュメントの提出は、認定の事前評価フェーズの一部です。 提供される情報により、認定アナリストは、評価の対象となるコントロールとシステム コンポーネントを特定するために必要な背景を持つことになります。 このドキュメントは、最初のドキュメントの提出に期待される内容の例としてのみ機能することを目的としています。 提供するドキュメントは、ソリューションの設計、実装、管理方法によって異なります。

## <a name="what-is-the-hosting-environment-or-service-model-used-to-run-your-app"></a>アプリの実行に使用されるホスティング環境またはサービス モデルは何ですか?
- サービスとしてのインフラストラクチャ (IaaS) は、クラウド サービス プロバイダーがインフラストラクチャ コンポーネントをホストするクラウド サービス モデルですが、ISV は、Virtual Machines/オペレーティング システム、データ ストア、ネットワーク コンポーネントなどのコンポーネントを個別にデプロイおよび管理する役割を引き続き担います。 この例は、Azure Virtual Machine と Azure Disk Storageです。
- サービスとしてのプラットフォーム (PaaS) は、インフラストラクチャ コンポーネントがクラウド サービス プロバイダーによって管理されるクラウド サービス モデルです。 ISV は、独自のアプリケーションとサービスのデプロイのみを担当します。 この例は、Azure アプリ サービス、Azure Functions、およびAzure CDNです。
- このコンテキストでホストされる ISV は、クラウド サービス プロバイダーが使用されていないことを意味します。 ISV は、独自のサーバー、ディスク、ネットワークをオンプレミスで個別に物理的に管理します。
- このコンテキストでのハイブリッドは、上記のモデルの 1 つが使用されることを意味します。 たとえば、一部の ISV は、IaaS Services と PaaS サービスの組み合わせの使用を選択してアプリをサポートしたり、一部のオンプレミス ISV ホスト型コンポーネントを持ち、他のコンポーネントをクラウド サービス プロバイダーにアウトソーシングしたりする場合があります。 その他のサービス モデルのいずれかを使用する場合は、ハイブリッドを選択します。

## <a name="penetration-test-report"></a>侵入テスト レポート

過去 12 か月以内に完了した日付の完全な侵入テスト レポートを含めてください。 
-   このレポートは手動の侵入テストから生成する必要があります。自動スキャン/テスト ツールの出力にすることはできません。
-   このレポートには、アプリ/アドインのデプロイをサポートする環境と、アプリ/アドインの操作をサポートする追加の環境を含める必要があります。


## <a name="system-component-inventory"></a>システム コンポーネント インベントリ

サポートするインフラストラクチャで使用されるすべてのシステム コンポーネントの最新の発明。 これは、評価フェーズを実行するときにサンプリングに役立ちます。 環境に PaaS が含まれている場合は、消費されたすべての PaaS サービスの詳細を提供できる場合に役立ちます。

**メモ：** IaaS/PaaS には、ISV の制御下にあるハードウェアはありません。  この場合は、すべてのウイルスリソースの一覧またはスクリーンショットを指定してください。

**例:** 

|資産名|資産の種類|説明|製造元|モデル|
|---|---|---|---|---|
|D212|Windows マシン|仮想コンピューター|N/A|N/A|
|LT101|ノート PC|ワークステーション|Microsoft|Surface 3|
|C2938|スイッチ|スイッチ|該当なし|該当なし|
|LXM2|Linux マシン|テスト マシン|N/A|N/A|


## <a name="software-inventory"></a>ソフトウェア インベントリ

スコープ内環境内で使用されるすべてのソフトウェアとバージョンを含むすべてのソフトウェア資産の最新のインベントリ。

**例:** 

|ソフトウェア|発行者|バージョン|用途|
|---|---|---|---|
|Windows Server|Microsoft 2016 |ビルド 14393|運用環境のサーバー オペレーティング システム|
|Linux Ubuntu|該当なし|16.04 (Xenial)|DMZ 内で使用中のサーバー オペレーティング システム。|
|Esxi|Vmware|6.5.0 (ビルド 13004031)|仮想サーバーをサポートするために使用されます。|
|Mysql (Windows)|該当なし|8.0.2.1|チャット履歴を格納するデータベース サーバー。|
|Tomcat|Apache|7.0.92|カスタマー ポータル。|
|IIS|Microsoft|10.0|API をサポートします。|


## <a name="third-party-dependencies"></a>サード パーティの依存関係

現在実行中のバージョンでアプリ/アドインによって使用されるすべての依存関係を示すドキュメント。

**例:** 

|Web 依存関係|使用中の現在のバージョン|
|----|----|
|Jquery|3.5.1|
|React|16.13.1|
|ブートス トラップ|.4.5.2 |
|Express|4.17.1|
|Angular|10.0.14|
|AngularJS|1.8.0|


## <a name="public-ip-addresses"></a>パブリック IP アドレス

サポートするインフラストラクチャで使用されるすべてのパブリック IP アドレスと URL を詳しく説明します。 これには、使用中の範囲を分割するために適切なセグメント化が実装されていない限り、環境に割り当てられたルーティング可能な完全な IP 範囲を含める必要があります (セグメント化の十分な証拠が必要になります)。

**例:** 

|URL|IP アドレス|
|-|-|
|https://portal.contoso.com |40.113.200.201 |
|https://filesapi.contoso.com|40.113.200.201|
|https://customerapi.contoso.com|40.113.200.202|
|https://bot.contoso.com|40.113.200.202|
|N/A (ジャンプ サーバー)|40.113.200.200|


## <a name="resource-endpoints"></a>リソース エンドポイント

API Name Endpoint Address Contoso Customer API https://customerapi.contoso.com Contoso Bot Service https://bot.contoso.com Contoso Files APIhttps://filesapi.contoso.com

内部的に開発された外部リソース エンドポイントを含む、アプリによって使用されるすべての API エンドポイントの完全な一覧。 環境のスコープを理解するために、環境内の API エンドポイントの場所を指定します。

**例:** 

|API 名|  エンドポイント アドレス|
|-|-|
|Contoso Customer API|  https://customerapi.contoso.com|
|Contoso Bot Service|   https://bot.contoso.com|
|Contoso Files API| https://filesapi.contoso.com|
|Microsoft Graph| https://graph.microsoft.com/v1.0/|


## <a name="architectural-diagram"></a>アーキテクチャ図

アプリ/アドインのサポート インフラストラクチャの概要を表す論理アーキテクチャ図。 これには、すべてのホスティング環境と、アプリ/アドインをサポートするインフラストラクチャのサポートが含まれている必要があります。 この図は、認定アナリストがスコープ内のシステムを理解し、サンプリングを決定するのに役立つよう、環境内のすべてのサポート システム コンポーネントを示す必要があります。 使用されるホスティング環境の種類も指定してください。ISV ホステッド、IaaS、PaaS、またはハイブリッド。 PaaS が使用されている場合は、環境内でサポート サービスを提供するために使用されるさまざまな PaaS サービスを指定してください。

![アーキテクチャ図](../media/Architecturaldiagram.png)

## <a name="data-flow-diagram"></a>Data Flow図

次の詳細を示す図をFlowします。
-   アプリ/アドインとの間で送受信されるデータ (顧客データを含む)。
-   サポートインフラストラクチャ内のデータ フロー (該当する場合)
-   格納される場所とデータ、外部のサード パーティにデータを渡す方法 (サード パーティの詳細を含む)、およびオープン/パブリック ネットワークおよび保存時の転送中のデータの保護方法を示す図。

![Data Flow図](../media/Dataflowdiagram.png)



