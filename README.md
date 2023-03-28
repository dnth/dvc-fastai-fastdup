# dvc-fastai-fastdup

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