---
title: 制約付き計画の生成
description: この手順では、材料制約と能力制約の両方を考慮した計画の作成方法を示します。
author: ShylaThompson
manager: AnnBe
ms.date: 08/29/2018
ms.topic: business-process
ms.prod: ''
ms.service: dynamics-ax-applications
ms.technology: ''
ms.search.form: DefaultDashboard, ReqCreatePlanWorkspace, ReqTransPlanCard, ReqPlanSched
audience: Application User
ms.reviewer: shylaw
ms.search.scope: Core, Operations
ms.search.region: Global
ms.author: shylaw
ms.search.validFrom: 2016-06-30
ms.dyn365.ops.version: Version 7.0.0
ms.openlocfilehash: 0e2265f7788fd2a4a37f6fb96d7562649dbc5b1c
ms.sourcegitcommit: 9d4c7edd0ae2053c37c7d81cdd180b16bf3a9d3b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/15/2019
ms.locfileid: "1556026"
---
# <a name="generate-a-constrained-plan"></a>制約付き計画の生成

[!include [task guide banner](../../includes/task-guide-banner.md)]

この手順では、材料制約と能力制約の両方を考慮した計画の作成方法を示します。 計画により、材料が利用可能でないうちに生産が開始しないように、またリソースが予約超過にならないようにします。 

この手順の作成に使用するデモ データの会社は USMF です。 この手順は、生産の計画者を対象としています。


## <a name="set-up-a-constrained-plan"></a>制約付き計画の設定
1. [マスター プラン] をクリックします。
2. [マスター プラン] をクリックします。
3. 一覧で、目的のレコードを見つけ、選択します。
    * 例: StaticPlan  
4. [有限能力] フィールドで [はい] を選択します。
5. [有限能力タイム フェンス] フィールドに「30」と入力します。
6. [タイム フェンス (日)] セクションを展開します。
7. [能力] フィールドで [はい] を選択します。
8. [能力スケジューリング タイム フェンス (日)] フィールドに、数値を入力します。
    * 例: 60  
9. [計算済遅延] フィールドで、[はい] を選択します。
10. [遅延の計算タイム フェンス (日)] フィールドに、数値を入力します。
    * 例: 60  
11. [計算済遅延] セクションを展開します。
12. [計算済遅延を要求日に追加] フィールドで「はい」を選択します。
13. [計算済遅延を要求日に追加] フィールドで「はい」を選択します。
14. [計算済遅延を要求日に追加] フィールドで「はい」を選択します。
15. ページを閉じます。

## <a name="create-a-constrained-plan"></a>制約付き計画の作成
1. [実行] をクリックします。
2. [マスター プラン] フィールドで、値を入力または選択します。
    * 制約を設定した計画を選択します。  
3. [OK] をクリックします。
    * しばらく時間がかかる場合があります  
4. [計画オーダー] をクリックします。

