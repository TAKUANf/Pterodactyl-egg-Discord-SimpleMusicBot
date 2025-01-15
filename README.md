# Pterodactyl Discord-SimpleMusicBOT Egg

このEggは、Pterodactylパネル上で[Discord-SimpleMusicBot](https://github.com/mtripg6666tdr/Discord-SimpleMusicBot)のインスタンスを簡単に作成するものです。
インストールプロセスを自動化し、全ての機能が正常に動作することを保障します。

## 機能

-   **自動インストール:** Discord SimpleMusicBotを簡単にインストールできます。
-   **BOTの更新:** バージョンを変更し、再インストールを実行するだけでBOTが更新されます。
-   **バージョン変更:** 好きなバージョンでBotを実行することができます。

## 使用方法

1.  **Eggのインポート:** リリースからJsonファイルをPterodactylパネルにインポートします。
2.  **Eggの設定:**
    -   **GIT_VERSION:** 使用するBOTのバージョンを入力します。例: `v4.3.10` [バージョン一覧](https://github.com/mtripg6666tdr/Discord-SimpleMusicBot/releases/)
3.  **新しいサーバーの作成:** このEggを使用して新しいサーバーを作成します。
5.  **Botの設定:** Discord-SimpleMusicBotの[公式ドキュメント](https://web.usamyon.moe/Discord-SimpleMusicBot/)に従って、初期設定を行ってください。
6.  **サーバーの起動** これでインストールプロセスは終了です。

## インストール詳細
-   **インストール方法:** 公式ドキュメントの[クローンして実行する](https://web.usamyon.moe/Discord-SimpleMusicBot/docs/setup/installation/normal)を参考に実行されます。
-   **環境:** インストールスクリプトは、Node.js v20を搭載したDebianベースのコンテナを使用します。
-   **Gitリポジトリ:** BOTコードは、[公式GitHubリポジトリ](https://github.com/mtripg6666tdr/Discord-SimpleMusicBot)からクローンされます。
-   **Node.js:** Node.jsは`nvm`経由でインストールされます。
-   **依存関係:** すべての依存関係は`npm`経由でインストールされます。

## 重要な注意事項

-   **再インストール:** ディレクトリにファイルが残っている場合、再インストールではなくコードの更新を実行します。これにより、既存の設定を保持しながら、指定された`GIT_VERSION`に更新されます。
-   **設定:** TOKENなどは適切な設定ファイルに設定する必要があります。手順については、Botの[公式ドキュメント](https://web.usamyon.moe/Discord-SimpleMusicBot/)を参照してください。

## 設定変数

| 変数          | 説明                                                                     | デフォルト値 | ユーザー編集 |
| ------------- | ------------------------------------------------------------------------ | ------------ | ------------- |
| `GIT_VERSION` | インストールするDiscord SimpleMusicBotのバージョン（[こちら](https://github.com/mtripg6666tdr/Discord-SimpleMusicBot/releases/)を参照し、記載してください。） | `v4.3.10`   | 可         |

## サポート

Discord-SimpleMusicBot自体に関する問題については、Botの[公式ドキュメント](https://web.usamyon.moe/Discord-SimpleMusicBot/)を参照してください。このEggに関する問題については、（takuan.tn@gmail.com）にお問い合わせください。