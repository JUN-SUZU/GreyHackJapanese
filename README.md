GreyHackは日本語フォントに対応していません。
そのため、XUnity.AutoTranslatorを用いて、日本語フォントをTextMeshProのフォローバックに設定する必要があります。
以下の手順で設定してください。
1. 'PlaceTheseFilesInGreyHackRoot'フォルダ内のファイルを全てGreyHackのルートディレクトリにコピーしてください。
    GreyHackのルートディレクトリは、'SteamLibrary\steamapps\common\Grey Hack'です。
2. 'SetupReiPatcherAndAutoTranslator.exe'を実行してください。
    トロイの木馬が心配な場合は、[GitHub](https://github.com/bbepis/XUnity.AutoTranslator)からXUnity.AutoTranslator-ReiPatcher-x.x.x.zipをダウンロードしてください。
3. 'SetupReiPatcherAndAutoTranslator.exe'を実行すると、ReiPatcherがインストールされ、AutoTranslatorフォルダとReiPatcherフォルダが作成されます。
4. 'AutoTranslator'フォルダ内の'Config.ini'を開いてください。
    38行目あたりの`FallbackFontTextMeshPro`の値を`sourcehansansjp-regular_sdf`に変更してください。これはTextMeshProというフォントのアセットバンドルファイル名です。源ノ角ゴシックのフォントを同梱しています。源ノ角ゴシックLICENSE.txtを参照してください。
5. 'Grey Hack (Patch and Run)'というショートカットを実行してください。
    ReiPatcherが起動し、フォントの設定が適用されます。
6. 次回以降は、フォントが設定されているので、Steamから起動して大丈夫です。
    ReiPatcherを起動する必要はありません。
