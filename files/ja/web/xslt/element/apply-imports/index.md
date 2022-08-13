---
title: <xsl:apply-imports>
slug: Web/XSLT/Element/apply-imports
tags:
  - XSLT
  - apply-imports
  - リファレンス
  - 要素
translation_of: Web/XSLT/Element/apply-imports
---
{{ XsltRef() }}

`<xsl:apply-imports>` 要素は非常に秘密で、複雑なスタイルシートで主に使用されます。インポートの優先順位では、メインスタイルシートのテンプレートルールは、インポートされたスタイルシートのテンプレートルールより優先される必要があります。ただし、メインスタイルシートの同等のルールではなく、(低い優先順位の) インポートされたスタイルシートからテンプレートルールを使用するようにプロセッサを強制することが可能な場合があります。

### 構文

    <xsl:apply-imports/>

### 必須属性

なし

### 任意属性

なし

### タイプ

命令は、テンプレート内に表示されます。

### 定義

XSLT, section 5.6.

### Gecko のサポート

サポート済み