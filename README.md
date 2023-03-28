# dvc-fastai-fastdup

This repo documents how to use [fastdup](https://github.com/visual-layer/fastdup) to clean and curate a visual dataset, [DVC](https://github.com/iterative/dvc) to version data, and [fastai](https://github.com/fastai/fastai) to train a model.

DVC versions the data and model produced and syncs them a Google Drive folder.

Initialize dvc repo
```
dvc init
```

Add data to watch
```
dvc add data/
dvc add models/
```

Add remote Google Drive
```
dvc remote add -d visuallayergdrive gdrive://1u3nWN53Tp1ZqDEc5VFimu86EjpJ13zrk
```

Checkout dataset

```
git checkout <..>
dvc checkout
```

Push dataset

```
dvc push
```