

# Middleman Template

[![deps][deps]][deps-url]

### Get to start

1. このリポジトリをフォークしてください
2. フォークしたリポジトリの名前を `your-project`（任意）に変更
3. `package.json` 内の `repository` > `url` に設定された `<your-name>` と `<your-project>` を適切なものに変更
4. 下記コマンドを実行

```sh
git clone --recursive https://github.com/<your-name>/<your-project>.git
cd <your-project>
yarn setup
```

5. buildディレクトリのリポジトリ設定が適切か確認（originとブランチが適切か）

適切な設定の例↓

```sh
cd build
git remote -v
origin	git+ssh://git@github.com/<your-name>/<your-project>.git (fetch)
origin	git+ssh://git@github.com/<your-name>/<your-project>.git (push)
git branch
* staging
```

6. この `README.md` は必要ないので削除
7. `README-TEMPLATE.md` を `README.md` にリネームして、必要な箇所を編集
8. 以上で、完了です。Have a nice coding!!

```sh
yarn start
```

[deps]: https://img.shields.io/david/naokazuterada/middleman-template.svg
[deps-url]: https://david-dm.org/naokazuterada/middleman-template
