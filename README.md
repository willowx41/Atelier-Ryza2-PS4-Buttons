# Atelier Ryza 2 - PS4 Button Icon Fix (Updated)

[English](#english) | [日本語](#日本語)

---

## English

Special K textures that change the Xbox button prompts to PS4 (DualShock 4) style in **Atelier Ryza 2: Lost Legends & the Secret Fairy**.

This is a re-hashed version of Monterossa's 2021 "PS4 Buttons V9" pack, updated to match the current game build. V9 was built against the game's v1.03 texture hashes, so on the current build almost none of the original files were being picked up by Special K anymore.

### What's fixed

- Battle screen (command menu, HUD)
- Synthesis screen (clipboard UI)
- Shared icon sheet (face buttons ○×□△, D-pad, L1/R1/L2/R2/L3/R3/ZL/ZR, Options, etc.)
- Other menus (inventory, equipment, map, etc.) are **not** covered — out of scope for the original mod

### Requirements

- [Special K](https://special-k.info/)

### Installation

1. Install Special K and launch Atelier Ryza 2 through it once
2. Open the overlay with `Ctrl + Shift + Backspace`
3. `File → Install Wrapper DLL`
4. `File → Initialize Texture Mods`
5. `File → Browse Texture Assets → Injectable Textures` to open the folder
6. Copy the 8 `.dds` files from this repo's `textures` folder directly into that folder (no subfolder)
7. Restart the game

### Tested on

- Game buildid: 15949491 (current as of August 2026)
- Controller: DualShock 4

Future game updates may shift texture hashes again and break this fix.

### Credits

- Original icon artwork: [Monterossa](https://steamcommunity.com/id/Monterossa/) ("PS4 Buttons V9")
- Ryza 1 derivative this was based on: [Skyyblaze](https://github.com/Skyyblaze/Atelier-Ryza-PS4-Switch-Button-Replacement)
- Rehash/patch for the current build: this repo

---

## 日本語

Atelier Ryza 2: Lost Legends & the Secret Fairy で、Xboxのボタン表記をPS4（DualShock 4）表記に変更するSpecial K用テクスチャです。

Monterossa氏が2021年に公開した「PS4 Buttons V9」を、その後の複数回のゲームアップデートに合わせてハッシュ値を更新し直したものです。V9はゲームv1.03時点のテクスチャハッシュを前提に作られていたため、現在のビルドではほとんどのファイルが反映されない状態でした。

### 対応状況

- 戦闘画面（コマンドメニュー・HUD）: 対応済み
- 調合画面（クリップボードUI）: 対応済み
- 共通アイコン一覧シート（顔ボタン○×□△、十字キー、L1/R1/L2/R2/L3/R3/ZL/ZR、Optionsなど）: 対応済み
- その他一部のメニュー画面（アイテム欄・装備・マップなど）: **未対応**（元MODの対象外のため）

### 必要なもの

- [Special K](https://special-k.info/)

### 導入方法

1. Special Kをインストールし、ライザのアトリエ2を一度SpecialK経由で起動する
2. `Ctrl + Shift + Backspace` でオーバーレイを開く
3. `File → Install Wrapper DLL` を実行
4. `File → Initialize Texture Mods` を実行
5. `File → Browse Texture Assets → Injectable Textures` でフォルダを開く
6. このリポジトリの `textures` フォルダの中身（`.dds`ファイル8個）を、そのフォルダに直接コピーする（サブフォルダを作らず、ファイルを直接置く）
7. ゲームを再起動

### 動作確認環境

- ゲームバージョン: buildid 15949491（2026年8月時点の最新ビルド）
- コントローラー: DualShock 4

ゲームが今後アップデートされた場合、再びハッシュ値がズレて反映されなくなる可能性があります。

### クレジット

- オリジナルアイコン素材: [Monterossa](https://steamcommunity.com/id/Monterossa/)（「PS4 Buttons V9」）
- ライザ1版の派生元: [Skyyblaze](https://github.com/Skyyblaze/Atelier-Ryza-PS4-Switch-Button-Replacement)
- 現行ビルドへの再対応: このリポジトリ
