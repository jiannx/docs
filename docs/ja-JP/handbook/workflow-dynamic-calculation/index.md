# 概要

<PluginInfo name="workflow-dynamic-calculation" link="/handbook/workflow-dynamic-calculation"></PluginInfo>

通常の演算ノードは固定の式を用いて計算を行いますが、動的式ノードはデータに関連する式に基づいて異なる計算を行うことができます。この機能の核心は、通常の数式フィールドがデータテーブル内のすべてのデータ行に対して同一の固定数式を適用するのに対し、動的式はデータ行ごとに異なる計算方法を扱い、ワークフロー内で動的計算を実現する点です。

例えば、注文データは異なる製品カテゴリに応じて異なる統計数式を使用し、特定のレポートデータを算出します。

## インストール

このプラグインは内蔵されているため、インストールは不要です。

## 使用マニュアル

動的式の使用は以下のいくつかのセクションに分かれています：

- [「式」テンプレート表](./collection.md)
- [ノード](./node.md)

また、[例](./example.md)を参照して、実際のシナリオにおける使用方法を理解してください。

