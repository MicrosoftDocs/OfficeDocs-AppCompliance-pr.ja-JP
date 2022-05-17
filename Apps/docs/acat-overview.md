---
title: Microsoft 365用のアプリ コンプライアンス自動化ツール
author: xu-hong
ms.author: hongxu6
manager: zhshang
description: Microsoft 365の App Compliance Automation ツールの概要
keywords: アプリ認定の自動化Microsoft 365
ms.topic: conceptual
ms.service: certification
ms.openlocfilehash: debd3c9e2ecd1538446d09f5019ea995260345fd
ms.sourcegitcommit: 785d1c5d829e44e0ad696b85c92be81f549b989e
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/17/2022
ms.locfileid: "65433493"
---
# <a name="app-compliance-automation-tool-for-microsoft-365"></a>Microsoft 365用のアプリ コンプライアンス自動化ツール
この記事では、Microsoft 365用アプリ コンプライアンス 自動化ツール (ACAT) の概要と、コンプライアンスの簡略化とMicrosoft 365認定の取得方法について説明します。

> [!IMPORTANT]
> ACAT は現在 *プライベート プレビューに入* っている。 プライベート プレビュー プログラムに参加する場合は、 [acatprivatepreview@microsoft.com](mailto:acatprivatepreview@microsoft.com) にお問い合わせください。

## <a name="what-is-app-compliance-automation-tool-for-microsoft-365"></a>Microsoft 365の App Compliance Automation Tool とは
App Compliance Automation Tool for Microsoft 365 (ACAT) は、顧客データを使用し、パートナー センター経由で発行されるすべてのアプリのコンプライアンス体験を簡略化するのに役立つ Azure Portal のサービスMicrosoft 365。 Microsoft 365用のアプリ コンプライアンス自動化ツールは、アプリケーション中心のコンプライアンス自動化ツールであり、Microsoft 365認定をより簡単かつ便利に完了するのに役立ちます。 プライベート プレビューでは、ACAT は Azure で実行されているアプリで使用できます。

このツールを使用すると、アプリケーションのコンプライアンス境界をすばやく定義し、コンプライアンス結果を自動的に監視し、コンプライアンス監査をより簡単に完了できます。 コンプライアンスの境界は、アプリの配信と、アプリが通信する可能性があるすべてのバックエンド システムをサポートするクラウド インフラストラクチャです。

ACAT は、Microsoft 365認定に向けた迅速な追跡を提供するだけでなく、Microsoft 365 アプリケーションのさまざまなコンプライアンス シナリオで役立ちます。

- Microsoft 365認定の責任に関する詳細なビューと修復手順。
- コンプライアンスの結果を継続的に取得するのに役立つ自動日次レポート。
- アプリケーション ライフサイクルの初期段階のガイダンスとして使用できるセキュリティとコンプライアンスのベスト プラクティス。

## <a name="benefits-of-acat"></a>ACAT の利点
アプリケーション中心のコンプライアンス体験。
- ACAT は、アプリケーションのクラウド環境のコンプライアンス状態を毎日報告します。これにより、現在のクラウド インフラストラクチャ コンプライアンス戦略と統合できます。
- 開発者は、アプリ開発フェーズ中でも ACAT を呼び出すことができます。

Microsoft 365認定を取得するプロセスを高速化します。
- ACAT は、特定のMicrosoft 365認定管理を完全に自動化します。
- Microsoft によって積極的に開発されている自動化リストが継続的に増えています。

Microsoft 365認定ワークフローとのネイティブ統合。
- ACAT は、Microsoft 365認定を目的としてパートナー センターと完全に統合されています。

## <a name="concepts-of-acat"></a>ACAT の概念
### <a name="regulatory-compliance-report"></a>規制コンプライアンス レポート 
ACAT では、アプリケーションのコンプライアンス状態を監査するには、アプリケーションのコンプライアンス レポートを作成します。 アプリケーションをビルドする Azure リソースを指定することで、アプリケーションのコンプライアンス境界を定義できます。 さまざまな開発環境とステージに基づいて、1 つのアプリケーションに対して複数のレポートを作成します。

レポートが作成されると、ACAT は定義済みのトリガー時間に関するコンプライアンス データの収集を開始し、コンプライアンス結果をレポートとして生成します。 一方、ACAT は、レポートを削除するまで、コンプライアンス レポートのコンプライアンス変更を継続的に監視します。

### <a name="microsoft-365-certification-control-results"></a>Microsoft 365認定管理の結果
規制コンプライアンス レポートでは、コンプライアンスの結果は、対応する状態が ACAT によってフラグ付けされたコントロールによって編成されます。
- **合格**: 完全に自動化されたMicrosoft 365認定コントロールに関するエラーはありません。
- **失敗:** 完全に自動化されたMicrosoft 365認定コントロールに対する顧客の責任が検出されました。
- **合格 - 追加の証拠が必要です**。*部分的に自動化された* Microsoft 365認定コントロールに関するエラーはありません。
- **失敗 - 追加の証拠が必要** です。*部分的に自動化された* Microsoft 365認定コントロールに対して顧客の責任が検出されました。
- **手動制御**: ACAT は、Microsoft 365認定管理に対する顧客の責任を自動化しません。

### <a name="customer-responsibility"></a>顧客の責任
各コントロールには、満たす必要がある一連の顧客責任が関連付けられます。 これらは、データ、エンドポイント、アカウント、アクセス管理などの領域で、お客様が保持する責任です。

ACAT は、お客様の責任ごとにデータを収集し、その評価結果を返します。 また、修復アクションも提供されます。これは、Microsoft 365認定基準に合わせるのに役立つガイダンスです。


## <a name="faq"></a>よくあるご質問 (FAQ)
### <a name="what-are-manual-controls-and-partially-automated-controls"></a>手動コントロールと部分的に自動化されたコントロールとは何ですか?
各コンプライアンス制御は、ACAT がコンプライアンス データを収集する一連の顧客責任に関連付けられます。 ただし、現時点では、Microsoft 365認定のすべてのコントロールが ACAT によってカバーされているわけではありません (カバレッジを拡大するための継続的な取り組みがあります)。 部分的に自動化された制御の場合、ACAT は顧客の責任の一部を自動化します。 参照にはコンプライアンス状態を使用できますが、Microsoft 365認定監査に直接使用することはできません。 手動コントロールの場合、ACAT は現在、顧客の責任を自動化しません。

### <a name="i-made-the-suggested-changes-base-on-the-remediation-suggestion-yet-the-control-is-still-failing"></a>修復の提案に基づいて推奨される変更を行いましたが、コントロールはまだ失敗しています
エラーを解決するためのアクションを実行した後、ACAT が更新された評価結果をフェッチして制御状態を更新するのを待つ必要があります。 評価は、事前に設定されたトリガー時間に 24 時間ごとに実行されます。

### <a name="how-is-the-compliance-report-used-in-the-certification-process"></a>認定プロセスでコンプライアンス レポートはどのように使用されますか?
ACAT は[パートナー センター](https://partner.microsoft.com/dashboard)とシームレスに統合され、Microsoft 365認定体験を完了します。 コンプライアンス レポートの作成中に、オファー GUID であるMicrosoft 365認定構成を編集できます。 作成時は省略可能であり、後でアプリケーションの発行を開始するときに構成できます。

## <a name="learn-more"></a>詳細情報

* [ACAT を使用したはじめに](https://aka.ms/acat/getstarted)
* [Microsoft 365認定の詳細を確認する](https://aka.ms/acat/m365cert)
