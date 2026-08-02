# Atelier Ryza 2 - PS4 Button Icon Fix (Updated)

[English](#english) | [日本語](#日本語)

---

## English

Special K textures that change the Xbox button prompts to PS4 (DualShock 4) style in **Atelier Ryza 2: Lost Legends & the Secret Fairy**.

This is a re-hashed version of Monterossa's 2021 "PS4 Buttons V9" pack, updated to match the current game build. V9 was built against the game's v1.03 texture hashes, so on the current build almost none of the original files were being picked up by Special K anymore.

### Requirements

- [Special K](https://special-k.info/)

### Installing Special K

1. Go to [special-k.info](https://special-k.info/) and download the installer
2. Run `SpecialK.exe` and follow the setup steps
3. After installation, locate `SpecialK64.dll` (usually in `C:\Users\<your username>\AppData\Local\Programs\Special K`)
4. In Steam, right-click Atelier Ryza 2 → **Manage → Browse local files** to open the game folder
5. Copy `SpecialK64.dll` into that game folder, then rename the copy to `dxgi.dll`
6. Launch the game once through Steam as usual

### Installation

1. Launch Atelier Ryza 2 through Steam once (with `dxgi.dll` in place, Special K loads automatically)
2. Open the overlay with `Ctrl + Shift + Backspace`
3. `File → Install Wrapper DLL`
4. `File → Initialize Texture Mods`
5. `File → Browse Texture Assets → Injectable Textures` to open the folder
6. Copy the 8 `.dds` files from this repo's `textures` folder directly into that folder
7. Restart the game

### Tested on

- Game version: Ver 1.08 (2024/10/11)
- Controller: DualShock 4

Future game updates may shift texture hashes again and break this fix.

### Credits

- Original icon artwork: [Monterossa](https://steamcommunity.com/id/Monterossa/) ("PS4 Buttons V9")

---

## 日本語

"ライザのアトリエ２ ～失われた伝承と秘密の妖精～" で、Xboxのボタン表記をPS4（DualShock 4）表記に変更するSpecial K用テクスチャです。

Monterossa氏が2021年に公開した「PS4 Buttons V9」を、その後の複数回のゲームアップデートに合わせてハッシュ値を更新し直したものです。V9はゲームv1.03時点のテクスチャハッシュを前提に作られていたため、現在のビルドではほとんどのファイルが反映されない状態でした。

### 必要なもの

- [Special K](https://special-k.info/)

### Special Kのインストール

1. [special-k.info](https://special-k.info/) にアクセスし、インストーラーをダウンロード
2. `SpecialK.exe` を実行し、手順に従ってインストール
3. インストール完了後、`SpecialK64.dll` を探す（通常は `C:\Users\ユーザー名\AppData\Local\Programs\Special K` にある）
4. Steamでライザのアトリエ2を右クリック → **管理 → ローカルファイルを閲覧** でゲームフォルダを開く
5. `SpecialK64.dll` をそのゲームフォルダにコピーし、コピーした方を `dxgi.dll` にリネームする
6. 一度、いつも通りSteamからゲームを起動する

### 導入方法

1. ライザのアトリエ2をSteamから起動する（`dxgi.dll`が置いてあれば自動でSpecialKが読み込まれる）
2. `Ctrl + Shift + Backspace` でオーバーレイを開く
3. `File → Install Wrapper DLL` を実行
4. `File → Initialize Texture Mods` を実行
5. `File → Browse Texture Assets → Injectable Textures` でフォルダを開く
6. このリポジトリの `textures` フォルダの中身（`.dds`ファイル8個）を、そのフォルダに直接コピーする
7. ゲームを再起動

### 動作確認環境

- ゲームバージョン: Ver 1.08(2024/10/11)
- コントローラー: DualShock 4

ゲームが今後アップデートされた場合、再びハッシュ値がズレて反映されなくなる可能性があります。

### クレジット

- オリジナルアイコン素材: [Monterossa](https://steamcommunity.com/id/Monterossa/)（「PS4 Buttons V9」）
