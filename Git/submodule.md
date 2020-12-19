# Git submodule
## git submodule とは
git submodule は、外部の git リポジトリを、自分の git リポジトリのサブディレクトリとして登録し、特定の commit を参照する仕組みです。
> [Qiita / Git submodule の基礎](https://qiita.com/sotarok/items/0d525e568a6088f6f6bb) から引用

## git submoduleの追加
```shell
git submodule add https://github.com/[username]/[reponame]
```

## git submoduleの更新
```shell
git submodule foreach git pull origin main
```

## 参考資料
- [Qiita / Git submodule の基礎](https://qiita.com/sotarok/items/0d525e568a6088f6f6bb)
