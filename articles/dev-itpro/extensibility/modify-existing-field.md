---
title: 拡張機能を使用したテーブル内の既存のフィールドの変更
description: このトピックでは、テーブル内の既存のフィールドを変更する方法について説明します。
author: ivanv-microsoft
manager: AnnBe
ms.date: 04/24/2019
ms.topic: article
ms.prod: ''
ms.service: dynamics-ax-platform
ms.technology: ''
audience: Developer
ms.reviewer: robinr
ms.search.scope: Operations
ms.custom: 268724
ms.assetid: ''
ms.search.region: Global
ms.author: ivanv
ms.search.validFrom: 2017-02-28
ms.dyn365.ops.version: Platform update 4
ms.openlocfilehash: c7a52e6a84e201bcc610c1e5d99c6e576a1d3e4f
ms.sourcegitcommit: 2b890cd7a801055ab0ca24398efc8e4e777d4d8c
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/07/2019
ms.locfileid: "1537398"
---
# <a name="modify-existing-fields-in-a-table-through-extension"></a>拡張機能を使用したテーブル内の既存のフィールドの変更

[!include [banner](../includes/banner.md)]

テーブル内の既存のフィールドのプロパティを変更するには、まずテーブルの拡張を作成する必要があります。 次のプロパティを変更することができます。

- **ラベル**
- **ヘルプ テキスト**
- **国地域コード**
- **拡張データ型** - 現在選択されている EDT から派生した拡張データ型 (EDT) のみを選択できます。 プロパティ シートのルックアップはフィルタリングされ、それらの EDT のみが表示されます。 たとえば、InventTable 上のテーブルの **幅** フィールドで EDT を編集する場合は、 **BOMMeasureWidth** を基にして EDT を作成することができます。次に、 **InventTable** 拡張子の **幅** フィールドで、 **拡張データ型** プロパティを変更します。 この方法で、新しいパッケージが配置されるときに、ユーザー インターフェイスで**幅**フィールドの外観を変更できます。

![既存のフィールドの変更](media/modify-table-property.jpg) 
