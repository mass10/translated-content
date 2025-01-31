---
title: GamepadHapticActuator
slug: Web/API/GamepadHapticActuator
tags:
  - API
  - Experimental
  - Gamepad
  - GamepadHapticActuator
  - Interface
  - Reference
  - VR
  - Virtual Reality
  - WebVR
translation_of: Web/API/GamepadHapticActuator
---
{{APIRef("Gamepad API")}}{{SeeCompatTable}}

[Gamepad API](/ja/docs/Web/API/Gamepad_API) の **`GamepadHapticActuator`** インターフェイスは、ユーザーに触覚フィードバックを提供するように設計されたコントローラー内のハードウェア (可能な場合) を表し、最も一般的には振動ハードウェアです。

このインターフェイスには、 {{domxref("Gamepad.hapticActuators")}} プロパティからアクセスできます。

## プロパティ

- {{domxref("GamepadHapticActuator.type")}} {{readonlyInline}}
  - : 触覚ハードウェアのタイプを表す列挙型を返します。

## メソッド

- {{domxref("GamepadHapticActuator.pulse()")}} {{readonlyInline}}
  - : 指定した期間、特定の強度でハードウェアパルスを作成します。

## 例

TBD.

## 仕様書

| 仕様                                                                                                                         | ステータス                               | 備考     |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- | -------- |
| {{SpecName('GamepadExtensions', '#gamepadhapticactuator-interface', 'GamepadHapticActuator')}} | {{Spec2('GamepadExtensions')}} | 初回定義 |

## ブラウザーの互換性

{{Compat("api.GamepadHapticActuator")}}

## 関連情報

- [Gamepad API](/ja/docs/Web/API/Gamepad_API)
