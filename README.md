# Vintage-Optimizations-For-RTM（廃止）
・RealTrainMod 1.12.2と公式ランチャーに対応する軽量化modpack。  
・多数のModを簡単に導入することが出来ます。
## 推奨環境
・Java 8.0.462+8（Eclipse Temurin）  
https://adoptium.net/temurin/releases?version=8&mode=filter&os=any&arch=any  
・Forge 14.23.5.2860  
・RTM 2.4.24-43
## 非互換性
VoxelMap：VoxelMapFixesを入れる。https://www.curseforge.com/minecraft/mc-mods/voxelmap-fixes  

Spark：Flareに変える。https://modrinth.com/mod/flare/versions  

FarPlaneTwo：Nothiriumと互換性が無い。  

VanillaFix、TexFix：CensoredASM（LoliASM）が置き換える。

FoamFix：VintageFixが置き換える。

Phosphor、Hesperus：Alfheimが置き換える。
## 注意事項
・OptiFineは自分で入れてください。

・OptiFineの「パフォーマンスの設定」は全てオフが望ましいです。「チャンク読み込み方法」の変更も不要です。
## 導入方法
・ReleaseからZipをダウンロードして、解凍する。  
・「Config」フォルダを既存のConfigフォルダに上書きする。  
・OptiFine以外の既存の軽量化modを前提modも含めて削除。軽量化mod以外でMixinBooterを要求するmodは一旦抜く。  
・FileDirectorをダウンロードし、modsに入れる。  
https://modrinth.com/mod/filedirector/versions?g=1.12.2  
・起動するとmodのダウンロード画面が出てくるので、「NEXT」を押してダウンロード。  
・警告画面が出たら✕ボタンでMinecraftを終了。クラッシュしたらそのまま次へ。  
・FileDirectorはもう要らないので削除。一旦抜いたmodも入れる。  
・Minecraftを再起動。  
・導入完了。  

・Configだけ使用し、modを自分でダウンロードするのも良い。
## Modリスト、Config変更
https://madoha-4862.hatenablog.jp/entry/2025/10/25/120306
## ライセンス
LGPL3。ライセンスの全文はmodpackのZip内のreadme.txtにあります。
## クレジット（Configファイル）
VintageFix by Embeddedt  
https://github.com/embeddedt/VintageFix?tab=License-1-ov-file#  
https://github.com/embeddedt/VintageFix?tab=MIT-2-ov-file#  
