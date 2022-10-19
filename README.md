# Jupyter labベース環境

## 実行環境

Linux GPUマシンを前提に作成しています。
また実行マシン内にnvidia系のソフトがインストールされていることも確認してください。

## 実行

イメージのビルド（これには時間がかかります。）
```
docker compose up build
```

イメージの起動
```
docker compose up -d
```

イメージ内にアクセス
```
docker exec -it ubuntu(ここはコンテナ名) /bin/zsh
```

## 作成者

U-chom