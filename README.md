# extract-pdf

ページごとにPDFを読み込みテキストを抽出し、内容をgptに送って要約してもらう。  
あくまで、テキストのみが抽出される。  
前のページの要約を常に一緒に送り続ける。

## usage
- cred.jsonの作成
cred.json.templateをもとに、openaiのorgとapi_keyを設定する。

- コマンド実行
``` sh
$ ./extractPDF.py <pdf_file_name> 2>/dev/null
```
