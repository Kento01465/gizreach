# gizreach

本システムは以下の目的に沿って開発します。
- 社員プロフィールの閲覧：会社として結束を高めることを目的とした社員交流の懸け橋となる社員プロフィールの作成・閲覧
- スキルシートの管理：スキルシートの管理を一括で行えるシステムを作成し、業務効率の向上を図る
- 案件管理：スキルシートを一元管理することで案件管理や商談の成約率を高めることに貢献する

## ディレクトリ構成

```
─┬ README.MD
 ├ docs ─┬ 01_業務ドメイン
 │       └ 02_システム設計 ─┬ er_diagram.md // 初版 ER図
 │                         └ ph1_er_diagram.md // Ph1用 ER図
 └.github ── PULL_REQUEST_TEMPLATE ─┬ bugfix.md // バグ修正用テンプレート
                                    └ feature.md // プルリク用テンプレート
```

## 環境構築
環境構築は以下の手順で行ってください。

1. このリポジトリをフォークする
GitHub上で「Fork」ボタンをクリックして、自分のアカウントにコピーします。


2. フォークしたリポジトリをローカルにクローンする

```
$ git clone https://github.com/your-username/your-repo.git
$ cd your-repo
```

3. Docker コンテナをビルド・起動する

```
$ docker compose --build
```

## コミット
初回コミット前に以下を実行
```
git config --local commit.template .gitmessage
```

コミットする際は以下を打ち込むことにより、テンプレートが表示されます。
```
git commit
```
