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

## 参考

- [【超初心者向け】DockerでWordPressをサクッと構築 | DevelopersIO](https://dev.classmethod.jp/articles/beginner-docker-wordpress/)

- [【docker】wordpressをローカルに構築](https://zenn.dev/persona/articles/50f87da99c92af)

- [Dockerfile と docker-compose を利用すると何がうれしいのか？ - Qiita](https://qiita.com/sugurutakahashi12345/items/0b1ceb92c9240aacca02)

- [Docker Composeとは？使い方やコマンドを紹介（Rails,MySQL,Nginx） | キツネの惑星](https://kitsune.blog/docker-compose)

- [Dockerで作ったWordPress環境にWP-CLIを追加する方法](https://samurai-project.com/articles/3413)
