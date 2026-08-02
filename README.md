# Atelier Ryza 2 - PS4 Button Icon Fix (Updated)

Atelier Ryza 2: Lost Legends & the Secret Fairy で、Xboxのボタン表記をPS4（DualShock 4）表記に変更するSpecial K用テクスチャです。

Monterossa氏が2021年に公開した "PS4 Buttons V9" を、その後の複数回のゲームアップデートに合わせてハッシュ値を更新し直したものです。V9はゲームv1.03時点のテクスチャハッシュを前提に作られていたため、現在のビルドではほとんどのファイルが反映されない状態でした。

## 対応状況

- 戦闘画面（コマンドメニュー・HUD）: 対応済み
- 調合画面（クリップボードUI）: 対応済み
- 共通アイコン一覧シート（顔ボタン○×□△、十字キー、L1/R1/L2/R2/L3/R3/ZL/ZR、Optionsなど）: 対応済み
- その他一部のメニュー画面（アイテム欄・装備・マップなど）: 未対応（元MODの対象外のため）

## 必要なもの

- [Special K](https://special-k.info/)

## 導入方法

1. Special Kをインストールし、ライザのアトリエ2を一度SpecialK経由で起動する
2. `Ctrl + Shift + Backspace` でオーバーレイを開く
3. `File → Install Wrapper DLL` を実行
4. `File → Initialize Texture Mods` を実行
5. `File → Browse Texture Assets → Injectable Textures` でフォルダを開く
6. このリポジトリの `textures` フォルダの中身（`.dds`ファイル8個）を、そのフォルダに直接コピーする（サブフォルダを作らず、ファイルを直接置く）
7. ゲームを再起動

## 動作確認環境

- ゲームバージョン: buildid 15949491（2026年8月時点の最新ビルド）
- コントローラー: DualShock 4

ゲームが今後アップデートされた場合、再びハッシュ値がズレて反映されなくなる可能性があります。

## クレジット

- オリジナルアイコン素材: [Monterossa](https://steamcommunity.com/id/Monterossa/)（"PS4 Buttons V9"）
- ライザ1版の派生元: [Skyyblaze](https://github.com/Skyyblaze/Atelier-Ryza-PS4-Switch-Button-Replacement)
- 現行ビルドへの再対応: このリポジトリ
