# Docker-Laravel-Nginx-Template
Dockerで構築したコンテナ上で、  
Nginx経由でLaravelのプロジェクトが見れるようにした。

下記コマンドでダウンロードしてください
```shell
$ git clone https://github.com/kouhei-github/Docker-Laravel-Nginx-Template.git
```

## Usage(使い方)
dockerを立ち上げる
```shell
$ docker compose up -d
```

Dockerfileを修正した際など、Imageをbuildし直すコマンド
```shell
$ docker compose build
```

dockerコンテナの容量が大部分を占め、一旦削除したいとき
```shell
$ docker prune -a
```