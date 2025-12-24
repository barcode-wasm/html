# Barcode.WASM

**WebAssembly バーコード生成ライブラリ**

ブラウザだけで18種類のバーコードを生成できます。サーバー不要。

---

## 🚀 まずはこれを試してください

### Step 1: コードを理解する

**[Easy-8-Steps.html](Easy-8-Steps.html)** を開いて、ボタンを押してみてください。

バーコードが生成されたら、そのHTMLファイルのソースコードを見てください。  
**たった8ステップ**でBarcode.WASMの使い方がわかります。

### Step 2: 全機能を体験する

**[All-in-One.html](All-in-One.html)** で、Barcode.WASMのすべての機能を体験できます。

HTML + JavaScript + CSS だけで、これだけのバーコード機能を実現できます。  
18種類のバーコード、PNG/SVG出力、色・サイズ・テキストのカスタマイズ、PDF出力まで。  
まずはお試しください。

---

## ⚠️ 起動方法（重要）

HTMLファイルを直接ダブルクリックしても動作しません。  
**ローカルサーバー経由**でアクセスしてください。

### VS Code + Live Server（推奨）

1. VS Codeで「Live Server」拡張機能をインストール
2. `Easy-8-Steps.html` を右クリック → 「Open with Live Server」

### Python

```bash
python -m http.server 8080
# http://localhost:8080/Easy-8-Steps.html を開く
```

### Node.js

```bash
npx http-server -p 8080
# http://localhost:8080/Easy-8-Steps.html を開く
```

---

## 📁 ファイル構成

```
├── Easy-8-Steps.html   ← 使い方を理解する（動くドキュメント）
├── All-in-One.html     ← 全機能を体験する（18種類のバーコード）
├── barcode.js          ← WASMローダー
├── barcode.wasm        ← WASMバイナリ
├── barcode.wasm.md     ← 詳細リファレンス
└── README.md           ← このファイル
```

---

## 🔲 対応バーコード（18種類）

### 1次元バーコード（15種類）

Code39, Code93, Code128, GS1-128, NW-7,  
Matrix 2of5, NEC 2of5, JAN-8, JAN-13, UPC-A, UPC-E,  
GS1 DataBar (標準/限定/拡張), 郵便カスタマバーコード

### 2次元バーコード（3種類）

QRコード, DataMatrix, PDF417

---

## 📦 npmパッケージ

```bash
npm install @pao-at-office/barcode-wasm
```

https://www.npmjs.com/package/@pao-at-office/barcode-wasm

---

## 📝 ライセンス

Barcode.WASM は有限会社パオ・アット・オフィスの製品です。

- **試用版**: 「SAMPLE」透かしが表示されます
- **製品版**: 透かしなし

---

**有限会社 パオ・アット・オフィス**  
https://www.pao.ac/barcode.wasm/