# vscode_markdown_preview

## cssの配置

- `/Users/{home_dir}/.vscode/markdown_preview.css` に配置する。
- {home_dir} は置き換える

## settings.json

`Command` + `,` で `settings.json` ファイルを開く

```settings.json
    // マークダウン プレビューから使用する CSS スタイル シートの URL またはローカル パスの一覧。相対パスは、エクスプローラーで開かれているフォルダーへの絶対パスと解釈されます。開かれているフォルダーがない場合、マークダウン ファイルの場所を基準としていると解釈されます。'\' はすべて '\\' と入力する必要があります。
    "markdown.styles": ["/Users/{home_dir}/.vscode/markdown_preview.css"],
    // マークダウン プレビューで YAML front matter がレンダリングされる方法を設定します。'hide' の場合、front matter が削除されます。その他の場合には、front matter はマークダウン コンテンツとして処理されます。
    "markdown.previewFrontMatter": "hide",
    // マークダウン プレビューで使用されるフォント ファミリを制御します。
    "markdown.preview.fontFamily": "Source Han Code JP",
    // マークダウン プレビューで使用されるフォント サイズ (ピクセル単位) を制御します。
    "markdown.preview.fontSize": 12,
    // マークダウン プレビューで使用される行の高さを制御します。この数値はフォント サイズを基準とします。
    "markdown.preview.lineHeight": 1.2,
    // エディターの現在の選択行を示すため、マークダウンのプレビューがスクロールします。
    "markdown.preview.scrollPreviewWithEditorSelection": true,
    // マークダウンのプレビューに、エディターの現在の選択範囲を示すマークが付きます。
    "markdown.preview.markEditorSelection": true,
    // マークダウンのプレビューをスクロールすると、エディターのビューが更新されます。
    "markdown.preview.scrollEditorWithPreview": true,
    // マークダウンのプレビューでダブルクリックすると、エディターに切り替わります。
    "markdown.preview.doubleClickToSwitchToEditor": true,
    // [試験的]拡張機能にマークダウン プレビューへの拡張を許可します。
    "markdown.enableExperimentalExtensionApi": false,
    // マークダウン拡張機能のデバッグログを有効にします。
    "markdown.trace": "off"
```

## プレビューの確認

- `.md` ファイルを開く
- `Command` + `Shift` + `V`
  - `Command` + `K` > `V`
