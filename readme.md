# PDF自動スケーリングツール

## 主な機能
PDFファイルの各ページを、A4以下はA4縦に、それ以上はA3横に揃えるツールです

## 動作環境
Windows10・Windows11

## 下準備
1. 実行ファイルのあるフォルダの下に、空の「temp」フォルダを作成しておきます(別のフォルダにしたい場合は、pdf_scaling.exeの設定からパスを変更してください)
2. cpdf.exeをダウンロードし、pdf_scaling.exeと同じフォルダにコピーします(別のフォルダにしたい場合は、pdf_scaling.exeの設定からパスを変更してください)

## 使い方
1. pdf_scaling.exeにPDFファイルをドラッグ＆ドロップするか、pdf_scaling.exeを起動してファイル選択ダイアログでPDFファイルを開きます
2. 解析結果が表示されるので、問題なければ「スケーリング実行」を選択し、保存先を選択します
3. スケーリングが自動で行われ、完了するとスケーリング結果を表示します

## 注意
同時起動には対応していません。tempフォルダにファイルを展開するため、同時に実行するとエラーや違うファイルと混ざってしまう場合があります。

## ライセンス
このソフトウェアには、以下のプログラムやライブラリを使用しています

CPDF  https://community.coherentpdf.com/

hspext  https://hsp.tv/



このソフトウェアは、AGPL(GNU AFFERO GENERAL PUBLIC LICENSE)3.0に基づいて製作されたものです

このソフトウェアを改変するなどして使用する場合、ソースコードの開示が必要となります

AGPLについて、詳しくはLICENSE.txtをご覧ください(英語です)
