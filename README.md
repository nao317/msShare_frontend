# msShare_frontend
音源やスコア・TAB譜、作曲したフレーズを簡単に共有できるサービス

# 環境

## next

[公式ドキュメント](https://nextjs.org/docs/app/getting-started/installation)

```bash
npx create-next-app@latest
```

## storybook

storybookのインストール

```bash
npx storybook@latest init
```

# GitHubの使い方

- このリポジトリをローカルにクローンする

```bash
git clone git@github.com:nao317/msShare_frontend.git
```

- いまあるブランチを見る

```bash
git branch
```

- ブランチを切る

```bash
git branch <new branch name>
```
(ex: making a develop branch)

```bash
git branch develop
```

- ファイルに変更を加えた、作業がひと段落終わった（一つコンポーネントを作り終わった）ときステージング

```bash
git add .
```

- ステージングしたファイルをコミット（コミットメッセージにどんな変更を加えたかを書く）

```bash
git commit -m "commit message"
```

- コミットした変更をリモートのブランチにプッシュ

```bash
git push origin ブランチ名
```

（リモートブランチ上でPR（プルリクエスト）出して、間違いやミスがなければMerge）

- マージした後にローカルのメインブランチに変更を反映

（mainブランチに移動）

```bash
git checkout main
```

```bash
git pull
```
