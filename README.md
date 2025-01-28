# Tauri + Dioxus

このプロジェクトは、Tauri と Dioxus を使用したアプリケーション開発を始めるためのテンプレートです。

## 推奨IDEセットアップ

以下のツールをインストールすることで、開発環境を快適に整えることができます。

-   [Visual Studio Code](https://code.visualstudio.com/)
    -   [Tauri 拡張機能](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode)
    -   [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)
    -   [Dioxus 拡張機能](https://marketplace.visualstudio.com/items?itemName=DioxusLabs.dioxus)

## 必要な依存関係

開発環境で以下の依存関係が不足している可能性があります。

| 必要なCLIツール | インストールコマンド                                  |
| --------------- | ----------------------------------------------------- |
| Tauri CLI       | `cargo install tauri-cli --version '^2.0.0' --locked` |
| Dioxus CLI      | `cargo install dioxus-cli --locked`                   |

## 必須要件

Tauri アプリケーションを実行するには、OSに応じた依存関係をインストールする必要があります。

-   必要な依存関係については、公式のドキュメントを参照してください: [Tauri Prerequisites](https://tauri.app/start/prerequisites/)

## プロジェクトの初期化

初期化コマンドは以下の通りです。

### Android 開発環境の初期化

```bash
cargo tauri android init
```

### iOS 開発環境の初期化

```bash
cargo tauri ios init
```

## 実行コマンド

### デスクトップアプリの開発サーバーを実行

```bash
cargo tauri dev
```

### Android アプリの開発サーバーを実行

```bash
cargo tauri android dev
```

### iOS アプリの開発サーバーを実行

```bash
cargo tauri ios dev
```

## プロジェクト構成

以下はプロジェクトの一般的な構成です。

```
project-root
├── src/                     # アプリケーションのソースコード
├── tauri.conf.json          # Tauri の設定ファイル
├── Cargo.toml               # Rust の依存関係
└── README.md                # プロジェクトの説明書
```

## その他のリソース

-   [Tauri公式ドキュメント](https://tauri.app/)
-   [Dioxus公式ドキュメント](https://dioxuslabs.com/)
-   [Rust公式ドキュメント](https://www.rust-lang.org/learn)
