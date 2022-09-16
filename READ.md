### 参考記事
- https://zenn.dev/nagakuta/articles/bea80b17f315bd069a90
- https://zenn.dev/nagakuta/scraps/39449e6c92b8f3

### やったこと
docker-compose でflutterの環境を作りたい

### やらないこと
- google-chrome-stableのインストール
- android-studioのインストール
    => vscodeの拡張で補完できるため

### TODO
- docker-compose.ymlのコマンドの意味
- dockerに設定したvolumes等の設定の煮詰め
- ファイル構成
- 実際に動かす
- もっと汎用性の高いdockerの構築をする

### 環境構築
1. git clone https://github.com/hiro-551010/yamabico-dev.git
2. cd docker
3. docker-compose build
4. docker-compose up -d
5. docker-compose exec yamabico bash
6. fvm install 3.3.2 (いらないかもです)
7. fvm use 3.3.2
8. fvm flutter create yamabico
