---
title: app Compliance Automation Tool for Microsoft 365を使用してMicrosoft 365認定を自動化する
description: Microsoft 365用アプリ コンプライアンス 自動化ツール (ACAT) を使用して、Microsoft 365認定を自動化します。
author: yjin81
ms.author: yajin1
manager: zhshang
ms.service: certification
ms.topic: how-to
ms.date: 04/13/2022
ms.custom: template-how-to
ms.openlocfilehash: c81ccf3626d6039333f52a487e98233364f7174e
ms.sourcegitcommit: 785d1c5d829e44e0ad696b85c92be81f549b989e
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/17/2022
ms.locfileid: "65433500"
---
# <a name="automate-microsoft-365-certification-with-app-compliance-automation-tool-for-microsoft-365"></a>app Compliance Automation Tool for Microsoft 365を使用してMicrosoft 365認定を自動化する

Microsoft 365用アプリ コンプライアンス 自動化ツール (ACAT) は、Microsoft 365 アプリ コンプライアンス プログラムと連携して、Microsoft 365認定に必要なコントロールの一部を満たします。 この記事では、ACAT の使用を開始し、Microsoft 365認定のコンプライアンス評価を使用するのに役立ちます。

> [!IMPORTANT]
> ACAT は現在プライベート プレビュー段階です。 プライベート プレビュー プログラムに参加する場合は、 [ここで](https://aka.ms/acat/private/signup)サインアップしてください。

## <a name="create-your-first-compliance-report-to-onboard-acat"></a>ACAT をオンボードするための最初のコンプライアンス レポートを作成する

ACAT を使用すると、アプリケーションのコンプライアンスやアプリケーションの特定の環境 (運用環境、ステージングなど) に集中できます。 これにより、アプリケーションのクラウド インフラストラクチャまたはアプリケーションの特定の環境に基づいてコンプライアンス境界を定義できるコンプライアンス **レポート** を作成できます。

> [!IMPORTANT]
> ACAT はプライベート プレビュー段階であるため、直接検索 *https://portal.azure.com* することはできません。 ACAT を起動するには、次のオプションを使用してください。

- [Azure portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D&microsoft_azure_marketplace_ItemHideKey=Microsoft_Azure_AppComplianceAutomationHidden)で ***Microsoft 365用の App Compliance Automation Tool*** を検索して起動するか、[ACAT のディープ リンクを](https://portal.azure.com/#blade/Microsoft_Azure_AppComplianceAutomation/AcatMenuBlade/overview)直接使用して起動します。
- 左側の ***[レポート]*** に移動します。

:::image type="complex" source="../media/ACAT/getstarted-create-report-inline.png" lightbox="../media/ACAT/getstarted-create-report.png" alt-text="コンプライアンス レポートを作成する":::
   レポートに移動して新しいコンプライアンス レポートを作成する :::image-end:::

- [ ***新しいレポートの作成*** ] を選択して、適切な構成で最初のコンプライアンス レポートの作成を開始します。 
    - **基本**
        - **レポート名**: コンプライアンス レポートの名前は必須であり、テナント内で複製することはできません。 数字、アルファベット、アンダースコアの組み合わせである可能性があります。 コンプライアンス レポートにはわかりやすい名前を使用することをお勧めします。たとえば、特定のアプリケーションや環境を示します。
        - **トリガー時間**: ACAT は、コンプライアンス レポートのコンプライアンス評価を毎日生成します。 この構成は、生成をトリガーするタイミングを指定するために使用されます。 
        - **サブスクリプションの選択**: プライベート プレビューでは、ACAT を使用すると、特定のサブスクリプションの Azure リソースを選択して、コンプライアンス レポートの範囲を定義できます。 クラウド インフラストラクチャに基づいて適切なサブスクリプションを選択できます。 アプリケーションのサブスクリプションが一覧にない場合は、管理者にアクセス許可を要求する必要があります。 
        - **リソースの選択**: サブスクリプションが指定されたら、クラウド インフラストラクチャに基づいて適切なリソースを選択します。 既定では、すべてのリソースが自動的に選択されます。 また、フィルター (リソース グループ、タグなど) でリソースを検索し、リソースを選択することもできます。 
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-basic-inline.png" lightbox="../media/ACAT/getstarted-report-config-basic.png" alt-text="基本構成":::
       コンプライアンス レポートの基本構成 :::image-end:::

    - **Microsoft 365認定**: Microsoft 365認定の構成は、作成時に省略可能です。  アプリの発行を開始したら、後で構成できます。
        - **オファー GUID**: オファー GUID は [、Microsoft パートナー ネットワーク](https://partner.microsoft.com/dashboard)のマーケットプレース オファーの一意の識別子です。 [ *詳細情報* ] を選択して、一意の識別子を取得する方法について詳しく説明します。
    
    :::image type="complex" source="../media/ACAT/getstarted-report-config-m365-inline.png" lightbox="../media/ACAT/getstarted-report-config-m365.png" alt-text="Microsoft 365認定の構成":::
       Microsoft 365認定に関する構成:::image-end:::

構成を確認してコンプライアンス レポートを作成すると、ACAT は次のソースからコンプライアンス関連のデータを自動的に収集します。 

- サブスクリプションの[Microsoft Defender for Cloud](https://azure.microsoft.com/services/defender-for-cloud/) (Free レベル) を有効にします。 
- サブスクリプションの一部のカスタム ポリシーを有効にします。 

> [!NOTE]
> 作成が成功した場合、ACAT は翌日からコンプライアンス レポートのコンプライアンス評価の収集と生成を開始します。 

## <a name="audit-the-compliance-assessments-with-your-compliance-report"></a>コンプライアンス レポートを使用してコンプライアンス評価を監査する

ACAT を使用すると、コンプライアンス レポートの実行時の状態を学習し、コンプライアンス評価を簡単に監査できます。 

- 左側の ***[レポート]*** に移動します。 既存のコンプライアンス レポートの概要を簡単に確認できます。
    - **実行時の状態**: 実行時の状態は、ACAT が最後の世代でコンプライアンス レポートを正しく管理するかどうかを示します。 実行時の状態には 3 つの状態があります。 
        - **アクティブ**: コンプライアンス レポートは継続的かつ正常に実行されています。 
        - **失敗:** ACAT は、最後の世代のこのコンプライアンス レポートのコンプライアンス評価を生成できませんでした。 この状態は、複数の理由で発生する可能性があります。たとえば、ACAT にルーティングされたコンプライアンス データをブロックするサブスクリプションの構成が正しくない、ACAT でシステム障害や停止が発生したなどです。 
        - **無効**: このコンプライアンス レポートは、手動で無効 (一時停止) されます。 この機能は、プライベート プレビューでは有効になっていません。 
    - **最終トリガー時刻** と **次のトリガー時刻**: ACAT は、コンプライアンス レポートのコンプライアンス評価を毎日生成します。 *最後のトリガー時刻* は、最後の世代がトリガーされたタイミングを示し、 *次のトリガー時刻* は今後の世代のトリガー時間を示します。 
    - **Microsoft 365認定**: Microsoft 365認定管理のコンプライアンス レポートの状態を把握します。 Microsoft 365認定コンプライアンスの状態には、次の 3 つの状態があります。
        - **合格**: 完全に自動化されたMicrosoft 365認定コントロールに関するエラーはありません。
        - **失敗:** 完全に自動化されたMicrosoft 365認定コントロールに対する顧客の責任が検出されました。
        - **手動**: この状態には、ACAT によって部分的に自動化され、まだコンプライアンス証拠を収集するための手動作業が必要な *部分自動化手動制御* と、コンプライアンス証拠を収集するための完全な手動作業が必要な *手動制御* の 2 種類の制御が含まれます。 ACAT は、部分的に自動化された制御に対する顧客の責任の一部を自動化します。 参照にはコンプライアンス状態を使用できますが、Microsoft 365認定監査に直接使用することはできません。
    
    :::image type="complex" source="../media/ACAT/getstarted-report-list-inline.png" lightbox="../media/ACAT/getstarted-report-list.png" alt-text="コンプライアンス レポートの一覧":::
       既存のコンプライアンス レポートの一覧。
    :::image-end:::

既存のコンプライアンス レポートの概要を学習するだけでなく、ACAT のチームでコンプライアンス評価の詳細を監査することもできます。 レポート名をクリックして、特定のコンプライアンス レポートのコンプライアンス評価の詳細を取得します。 ACAT では、次のように詳細が表示されます。

- **設定**: 設定 *を使用して* コンプライアンス レポートの構成を変更できます。 プライベート プレビューでは、Microsoft 365認定関連の構成を変更できます。 
- **レポートのダウンロード**: ACAT を使用すると、コンプライアンス レポートの評価を csv ファイルとして、共同作業のためにパートナーと共有できる形式でダウンロードできます。
    - **クラウド インフラストラクチャ インベントリ**: このファイルには、このコンプライアンス レポートのリソースの詳細が含まれています。 アプリケーションのクラウド インベントリを記述するために使用できます。 
    - **Microsoft 365認定コンプライアンス評価**: このファイルには、Microsoft 365認定管理の観点から、コンプライアンス レポートのコンプライアンス評価が含まれます。 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-toolbar-inline.png" lightbox="../media/ACAT/getstarted-report-detail-toolbar.png" alt-text="コンプライアンス レポート ツール バー":::
    コンプライアンス レポートのツール バー。
:::image-end:::

- **要点**: このセクションでは、コンプライアンス レポートの状態と構成を示します。 

:::image type="complex" source="../media/ACAT/getstarted-report-detail-essential-inline.png" lightbox="../media/ACAT/getstarted-report-detail-essential.png" alt-text="コンプライアンス レポートの要点":::
    コンプライアンス レポートの要点。
:::image-end:::

- **評価結果**
    - Microsoft 365認定管理のコンプライアンス状態は、5 つのカテゴリに分類されます。 
        - **合格**: 完全に自動化されたMicrosoft 365認定コントロールに関するエラーはありません。
        - **失敗:** 完全に自動化されたMicrosoft 365認定コントロールに対する顧客の責任が検出されました。
        - **合格 - 追加の証拠が必要です**。部分的に自動化されたMicrosoft 365認定コントロールに関するエラーはありません。 コントロールの追加の証拠を手動で収集する必要があります。
        - **失敗 - 追加の証拠が必要** です。部分的に自動化されたMicrosoft 365認定コントロールに対して、顧客の責任が検出されました。
        - **手動制御**: ACAT は、Microsoft 365認定管理に対する顧客の責任を自動化しません。 
    - コンプライアンス評価は、Microsoft 365認定管理ファミリと管理によって編成されます。 
        - コンプライアンス制御の詳細と、コントロール名をクリックして手動制御のコンプライアンス証拠を収集する方法について説明します。 
        - 完全に自動化された制御と部分的に自動化された制御を拡張すると、そのコントロールに対する顧客の責任に関するコンプライアンスの詳細を学習できます。 
        - 顧客の責任ごとに、アクション ボタンをクリックして、関連するリソースのコンプライアンス状態と失敗したリソースの修復手順を検出することもできます。 
            - **異常なリソース: 異常なリソース** を修正するには、修復手順をフォローアップする必要があります。 
            - **該当しないリソース**: リソースを設定する N/A の理由をフォローアップする必要があります。その後、ACAT はリソースのコンプライアンス評価を収集できます。

:::image type="complex" source="../media/ACAT/getstarted-report-detail-assessment-inline.png" lightbox="../media/ACAT/getstarted-report-detail-assessment.png" alt-text="コンプライアンス レポートの評価":::
    コンプライアンス レポートのコンプライアンス評価。
:::image-end:::

## <a name="use-your-first-compliance-report-with-microsoft-r365-certification-audit"></a>Microsoft r365 認定監査で最初のコンプライアンス レポートを使用する

コンプライアンス レポートをMicrosoft 365認定と共に使用する前に、コンプライアンス レポートをマーケットプレース オファーに関連付けるようにオファー GUID を構成する必要があります。 次のような 2 つのオプションがあります。 

- コンプライアンス レポートの作成プロセス中に、*Microsoft 365認定* タブでオファー GUID を構成します。 
- コンプライアンス レポートが既に作成されている場合は、このコンプライアンス レポートの *設定* に移動して、オファー GUID を構成します。

オファー GUID が構成されたら、 [Microsoft パートナー ネットワーク](https://partner.microsoft.com/dashboard) に移動してアプリのコンプライアンスを開始します。 *初期ドキュメント* は、Microsoft 365認定の最初のフェーズです。 このフェーズでは、ACAT を使用しているかどうかに関して *[はい* ] を選択した場合は、この監査の適切なコンプライアンス レポートを選択できます。 Microsoft 365認定は、完全に自動化されたコントロールのコンプライアンス評価を監査者に自動的に送信し、時間と労力を節約します。 

## <a name="get-high-level-overview-of-your-compliance-reports"></a>コンプライアンス レポートの概要を確認する 

***概要*** では、コンプライアンス レポートの高レベルの状態について理解を深めます。 

- **コンプライアンス レポートの実行時の状態**: この概要では、コンプライアンス レポートの実行時の状態の統計情報が表示されます。
    - **アクティブ**: コンプライアンス レポートは継続的かつ正常に実行されています。 
    - **失敗:** ACAT は、最後の世代のこのコンプライアンス レポートのコンプライアンス評価を生成できませんでした。 この状態は、いくつかの理由で発生する可能性があります。たとえば、ACAT にルーティングされたコンプライアンス データをブロックする構成がサブスクリプションに正しくない場合や、ACAT でシステム障害や停止が発生した場合などです。 
    - **無効**: このコンプライアンス レポートは、手動で無効 (一時停止) されます。 この機能は、プライベート プレビューでは有効になっていません。 

:::image type="complex" source="../media/ACAT/getstarted-overview-runtime-inline.png" lightbox="../media/ACAT/getstarted-overview-runtime.png" alt-text="実行時の状態の概要":::
    コンプライアンス レポートの実行時の状態の概要。
:::image-end:::

- **アクティブな規制コンプライアンス レポート**: この概要では、 *アクティブ* なコンプライアンス レポートごとに、コンプライアンス結果の統計を示します。
    - **合格**: 完全に自動化されたMicrosoft 365認定コントロールに関するエラーはありません。
    - **失敗:** 完全に自動化されたMicrosoft 365認定コントロールに対する顧客の責任が検出されました。
    - **手動**: この状態には、ACAT によって部分的に自動化され、まだコンプライアンス証拠を収集するための手動作業が必要な *部分自動化手動制御* と、コンプライアンス証拠を収集するための完全な手動作業が必要な *手動制御* の 2 種類の制御が含まれます。 ACAT は、部分的に自動化された制御に対する顧客の責任の一部を自動化します。 参照にはコンプライアンス状態を使用できますが、Microsoft 365認定監査に直接使用することはできません。

:::image type="complex" source="../media/ACAT/getstarted-overview-compliance-inline.png" lightbox="../media/ACAT/getstarted-overview-compliance.png" alt-text="コンプライアンス状態の概要":::
    アクティブなコンプライアンス レポートのコンプライアンス状態の概要。
:::image-end:::

## <a name="troubleshooting"></a>トラブルシューティング 

### <a name="why-is-the-compliance-report-created-failed-due-to-authorization-error"></a>承認エラーが原因で作成されたコンプライアンス レポートが失敗するのはなぜですか? 

コンプライアンス レポートを作成するときに、ACAT は、コンプライアンス データを自動的に収集するサブスクリプションを使用して環境を設定します。このアクションには、サブスクリプションの特定のアクセス許可が必要です。 次のように、サブスクリプションのアクセス許可を確認できます。 

- [Azure portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)で **サブスクリプションを** 検索して起動します。
- コンプライアンス レポートの作成に使用するサブスクリプションに移動します。 
- 左側の **アクセス制御 (IAM)** に移動します。 
- [ **アクセス許可の表示** ] を選択して、アクセス許可を確認します。
    - 組織が [Azure 組み込みロール](/azure/role-based-access-control/built-in-roles)を使用している場合、ロールの割り当てには、次のロールの少なくとも 1 つが含まれている必要があります。
        - [リソース ポリシー共同作成者](/azure/role-based-access-control/built-in-roles#resource-policy-contributor) と [セキュリティ管理者](/azure/role-based-access-control/built-in-roles#security-admin)
        - より高いアクセス許可を持つ他のロール[](/azure/role-based-access-control/built-in-roles#owner)の割り当て (所有者など)

### <a name="how-to-report-an-acat-issue-or-warning"></a>ACAT の問題または警告を報告する方法 

ACAT で問題が発生し、 [ACAT プライベート プレビュー プログラム](mailto:acatprivatepreview@microsoft.com) に問い合わせてサポートを受けたい場合は、シナリオをよりよく理解するために証拠を収集するための支援が必要です。

- ACAT エラーまたは警告の詳細を取得する
    - Azure portalの上にある **[通知]** に移動 [します](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)。
    - **アクティビティ ログで [その他のイベント] を選択する** 
    
    :::image type="complex" source="../media/ACAT/getstarted-troubleshoot-activitylog.png" alt-text="ACAT 通知":::
        アクティビティ ログに移動して、ACAT 通知を確認します。
    :::image-end:::
    
    - タイム **スパン** を適切に変更して、アクティビティ ログで ACAT エラーまたは警告を除外します。 
    - ACAT エラーまたは警告を確認し、選択して詳細を取得し、詳細をファイルとして保存します。
    
- サブスクリプションが ACAT によって正しく設定されているかどうかを確認します。 
    - [Azure portal](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)で **サブスクリプションを** 検索して起動します。
    - コンプライアンス レポートの作成に使用するサブスクリプションに移動します。 
    - **リソース プロバイダー** を選択して、これらのプロバイダーの状態が *登録済* みかどうかを確認します。
        - Microsoft.Security
        - Microsoft.ResourceGraph
    - Azure portalに [戻る](https://portal.azure.com/?microsoft_azure_appcomplianceautomation_assettypeoptions=%7B%22AppComplianceAutomation%22:%7B%22options%22:%22%22%7D%7D)し、**エクスプローラー Resource Graph起動します**。
    - **[新しいクエリ]** を選択する
    - このクエリを実行してポリシーの割り当てを確認し、結果を CSV としてダウンロードします。 

    ```kusto
    resourcecontainers
    | where type == "microsoft.resources/subscriptions/resourcegroups"
    | where name contains "acat"
    ```

    - このクエリを実行して自動化を確認し、結果を CSV としてダウンロードします。

    ```kusto
    resources
    | where type == "microsoft.security/automations"
    | where name contains "acat"
    ```

    - このクエリを実行して評価を確認し、結果を CSV としてダウンロードします。 プレースホルダー ***your-subscriptionId*** を、クエリを実行する特定のサブスクリプションに置き換える必要があります。

    ```kusto
    SecurityResources
      | where type == 'microsoft.security/assessments'
      | where subscriptionId == "your-subscriptionId"
      | extend metadata=properties.metadata,
      status=properties.status,
      links=properties.links,
      displayName=properties.displayName,
      resourceDetails=properties.resourceDetails,
      description=properties.metadata.description
      | project type, id, name, description, metadata, status, resourceDetails, links, displayName
    ```