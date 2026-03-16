# NC Tool Suite

FANUC対応 旋盤・マシニングGコード生成・管理システム

## 使い方
`index.html` をブラウザで開くだけで動作します。

## ファイル構成
```
index.html          ← ここを開く
version.json        ← バージョン管理
css/common.css      ← 共通スタイル
js/common.js        ← 共通ライブラリ
pages/
  gcode.html        ← Gコード生成
  compound.html     ← 複合加工ビルダー
  tools.html        ← 工具登録
  log.html          ← 加工実績ログ
  calc.html         ← 計算ツール群
  drawing.html      ← DXF図面読み込み
  preview.html      ← 3Dパスプレビュー
```

## 自己更新の仕組み
1. `index.html` を開く
2. 「🔄 更新確認」ボタンを押す
3. 新バージョンがあれば「⬆ 更新する」が表示される
4. ダウンロードしてフォルダに上書き

## バージョン履歴
- v3.1.0: 工具登録連動強化・3Dプレビュー精度向上・DXF図面読み込み追加
- v3.0.0: 計算ツール群・加工実績ログ・パスプレビュー追加
- v2.0.0: 複合加工ビルダー追加
- v1.0.0: 初回リリース
