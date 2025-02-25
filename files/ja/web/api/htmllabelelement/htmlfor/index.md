---
title: HTMLLabelElement.htmlFor
slug: Web/API/HTMLLabelElement/htmlFor
---

{{APIRef("HTML DOM")}}

**`HTMLLabelElement.htmlFor`** プロパティは [`for`](/ja/docs/Web/HTML/Element/label#for) コンテンツプロパティの値を反映します。つまり、このスクリプトでアクセス可能なプロパティは、ラベルに関連付けられたコントロール要素の ID である `for` コンテンツプロパティの値を設定したり読み取ったりするために使用されます。

## 構文

```js
controlId = HTMLLabelElement.htmlFor

HTMLLabelElement.htmlFor = newId
```

### 値

{{domxref("DOMString")}} で、このコントロールに関連する要素の ID 文字列が入ります。

> **メモ:** このプロパティに値がある場合 {{domxref("HTMLLabelElement.control")}} プロパティも同じコントロールになります。

## 仕様書

{{Specifications}}

## ブラウザーの互換性

{{Compat}}

## 関連情報

- {{domxref("HTMLLabelElement")}}
- {{domxref("HTMLLabelElement.control")}}
- {{domxref("HTMLElement")}}
- {{HTMLElement("label")}}
- [HTML フォームガイド](/ja/docs/Learn/Forms)
