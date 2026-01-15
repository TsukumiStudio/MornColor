# MornColor

## 概要

色とグラデーション情報をScriptableObjectで管理し、エディタで可視化・編集するカラー管理システム。

## 依存関係

| 種別 | 名前 |
|------|------|
| 外部パッケージ | なし |
| Mornライブラリ | なし |

## 使い方

### カラー情報の作成

1. Projectウィンドウで右クリック → `Create > Color/MornColorInfo` を作成
2. 色を設定

### グラデーション情報の作成

1. Projectウィンドウで右クリック → `Create > Color/MornGradientInfo` を作成
2. グラデーションを設定

### スクリプトでの使用

```csharp
public MornColorInfo colorInfo;

void Start()
{
    // 色を取得
    Color color = colorInfo.Color;
}
```

### カラー一覧ウィンドウ

`Tools > MornColorWindow` でプロジェクト内の全カラー・グラデーション情報を一覧表示できます。
