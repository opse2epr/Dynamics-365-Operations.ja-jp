---
title: 税エンジン インポート コンフィギュレーション
description: このトピックでは、輸入税エンジンのコンフィギュレーションについて説明します。
author: yijialuan
manager: AnnBe
ms.date: 10/15/2018
ms.topic: article
ms.prod: ''
ms.service: dynamics-ax-applications
ms.technology: ''
ms.search.form: ERSolutionTable, ERDataModelDesigner, ERModelMappingTable, GTE
audience: IT Pro
ms.reviewer: shylaw
ms.search.scope: Core, Operations
ms.search.region: India
ms.author: riluan
ms.search.validFrom: 2017-12-31
ms.dyn365.ops.version: 7.2999999999999998
ms.openlocfilehash: e6b963eb00027da73bd89791ef9f22e7472a9657
ms.sourcegitcommit: 9d4c7edd0ae2053c37c7d81cdd180b16bf3a9d3b
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/15/2019
ms.locfileid: "1571572"
---
# <a name="import-tax-engine-configurations"></a>輸入税エンジン コンフィギュレーション

[!include [banner](../includes/banner.md)]

このトピックでは、輸入税エンジンのコンフィギュレーションについて説明します。

### <a name="create-a-lifecycle-services-lcs-configuration-repository"></a>Lifecycle Services (LCS) のコンフィギュレーション リポジトリの作成
1. **組織管理** > **ワークスペース** > **電子申告**の順に移動します。
2. **コンフィギュレーション プロバイダー**セクションで、**Microsoft** プロバイダー タイルの**リポジトリ**をクリックします。

![コンフィギュレーションの読み込み](media/gte-extension-repositories.png)

3. **追加** をクリックします。 
4. **LCS** オプションを選択します。 
5. **リポジトリの作成**をクリックして、LCS コンフィギュレーション リポジトリを作成します。
6. リポジトリの名前と説明を入力し、**OK** をクリックします。

### <a name="import-configurations-from-lcs"></a>LCS からコンフィギュレーションをインポートする
1. **組織管理** > **ワークスペース** > **電子申告**の順に移動します。
2. **コンフィギュレーション プロバイダー**セクションで、**Microsoft** プロバイダー タイルの**リポジトリ**をクリックします。
3. 作成したコンフィギュレーション リポジトリを選択します。 
4. **開く** をクリックします。
5. ツリーで、最新の税務書類を選択します (たとえば、**税 (インド GST)** を選択)。
6. **バージョン**セクションで、**インポート**をクリックします。

![コンフィギュレーションの読み込み](media/gte-extension-import-configurations.png)

7. **はい**をクリックして、インポートを確認します。
