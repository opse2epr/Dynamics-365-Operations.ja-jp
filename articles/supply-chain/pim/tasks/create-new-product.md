---
title: 新しい製品の作成
description: このタスクは、新しい共有製品を作成する方法を示します。
author: ShylaThompson
manager: AnnBe
ms.date: 08/29/2018
ms.topic: business-process
ms.prod: ''
ms.service: dynamics-ax-applications
ms.technology: ''
ms.search.form: EcoResProductListPage, EcoResProductCreate, EcoResProductDetails, EcoResProductInventoryDimensionGroups
audience: Application User
ms.reviewer: shylaw
ms.search.scope: Core, Operations
ms.search.region: Global
ms.author: shylaw
ms.search.validFrom: 2016-06-30
ms.dyn365.ops.version: Version 7.0.0
ms.openlocfilehash: 7a603d89749242a4c6039ab83da286ec6ab727d8
ms.sourcegitcommit: 9d4c7edd0ae2053c37c7d81cdd180b16bf3a9d3b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/15/2019
ms.locfileid: "1548419"
---
# <a name="create-a-new-product"></a>新しい製品の作成

[!include [task guide banner](../../includes/task-guide-banner.md)]

このタスクは、新しい共有製品を作成する方法を示します。 これは通常、製品デザイナーが実行します。 このタスクの作成に使用するデモ データの会社は USMF です。

1. [製品情報管理] > [製品] > [製品] の順に移動します。

## <a name="create-a-product"></a>製品の作成
1. [新規] をクリックします。
2. [製品番号] フィールドに値を入力します。
    * 番号順序が製品番号に対して設定されていない場合は、手動で入力する必要があります。  
3. [製品名] フィールドに値を入力します。
    * 製品名が検索名の既定値になります。 必要に応じて手動でこれを変更できます。  
4. [OK] をクリックします。

## <a name="set-up-dimension-groups"></a>分析コード グループの設定
1. [分析コード グループ] をクリックすると、ドロップ ダイアログが開きます。
2. [保管分析コード グループ] フィールドで、値を入力または選択します。
    * 保管分析コード グループにより、製品の各トランザクションに入力する必要がある保管分析コードと、在庫で追跡される方法が決まります。  
3. [追跡用分析コード グループ] フィールドで、値を入力または選択します。
    * 追跡用分析コード グループにより、製品の各トランザクションに入力する必要がある追跡用分析コードと、在庫で処理される方法が決まります。  
4. [OK] をクリックします。

