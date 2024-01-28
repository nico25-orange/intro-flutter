# Chapter 2

## 01 画面の構築

- `appBar`
    - `title`
- `body`
    - `Column`
        - `Text`
        - `TextButton`
        - `Row`
            - `Icon`
- `floatingActionsButton`
- `Drawer`
- `endDrawer`

## 02 画面の更新

### StatefulWidget

状態を持つ。動的で変化する。状態によって同じ入力でも出力が変わることがある。

### StatelessWidget

状態を持たない。静的で変化しない。どんな時でも同じ入力に対して同じ出力になる。

> **Warning**
>
> StatelessWidgetは画面が表示された後に画面の要素を書き換えることはできない。

## 03 パッケージの活用

Add packages

```bash
flutter pub add font_awesome_flutter
```

pubspec.yaml

```diff
dependencies:
  flutter:
    sdk: flutter


  # The following adds the Cupertino Icons font to your application.
  # Use with the CupertinoIcons class for iOS style icons.
  cupertino_icons: ^1.0.2
+  font_awesome_flutter: ^10.7.0
```
