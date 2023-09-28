# wp-test

## 目的

DockerでWordpressを構築する方法が載っている記事を見つけたため、
検証するためのリポジトリを作成しました。

## 環境構築

### Docker起動

```
docker-compose up -d
```

### Docker停止

```
docker-compose down --volumes
```

### WP-CLI動作確認

- WordPress設定確認
    ```
    docker-compose run --rm wpcli --info
    ```

- WordPress CLI バージョン
    ```
    docker-compose run --rm wpcli core version
    ```

## 参考

- [【超初心者向け】DockerでWordPressをサクッと構築 | DevelopersIO](https://dev.classmethod.jp/articles/beginner-docker-wordpress/)

- [【docker】wordpressをローカルに構築](https://zenn.dev/persona/articles/50f87da99c92af)

- [Dockerfile と docker-compose を利用すると何がうれしいのか？ - Qiita](https://qiita.com/sugurutakahashi12345/items/0b1ceb92c9240aacca02)

- [Docker Composeとは？使い方やコマンドを紹介（Rails,MySQL,Nginx） | キツネの惑星](https://kitsune.blog/docker-compose)

- [Dockerで作ったWordPress環境にWP-CLIを追加する方法](https://samurai-project.com/articles/3413)

- [ZIP形式で配布されているプラグインをインストールする](https://www.javadrive.jp/wordpress/plugin/index2.html)

- [Docker Composeで簡単便利な砂場作り | サイドスリーブログ | 神戸のWeb制作会社 株式会社サイドスリー](https://www.sidethree.co.jp/blog/memo/202109-1.html)

- [DockerfileのCOPYでファイルやディレクトリごとコンテナにコピーする - ライトリ](https://litely.net/post/tech/docker/reference/dockerfile_copy/)

- [ローカル開発環境を作り易いDockerfileのフォルダ構成 - Qiita](https://qiita.com/sgswtky/items/01650a041b581ffd83f7)

- [Docker ComposeでDockerfileをビルドする際に親ディレクトリのファイルをコピーする](https://zukucode.com/2020/08/docker-compose-parent-directory.html)

- [第167回　M1搭載MacのDockerでMySQLを動かしてみる | gihyo.jp](https://gihyo.jp/dev/serial/01/mysql-road-construction-news/0167)  

- [Dockerでコンテナ起動後に「Error establishing a database connection 」と出てデータベースに接続できない時の対処法：Warning: mysqli_real_connect(): php_network_getaddresses: getaddrinfo failed:](https://prograshi.com/platform/docker/dokcer-wp-db-connection-error/)  

