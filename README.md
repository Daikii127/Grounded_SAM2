## 1. SAM 2 の事前学習済みチェックポイントをダウンロード:

```bash
cd checkpoints
bash download_ckpts.sh
```

# 2. Grounding DINO の事前学習済みチェックポイントをダウンロード:

```bash
cd gdino_checkpoints
bash download_ckpts.sh
```

# 3. Dockerを使用したインストール:
# Dockerイメージをビルドしてコンテナを実行:

```bash
cd Grounded-SAM-2
make build-image
make run
``` Grounded_SAM2
