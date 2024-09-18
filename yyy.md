# [BizReach Tech Blog](https://tech.bizreach.co.jp/)
![BizReach Tech Blog](https://tech.bizreach.co.jp/img/default_600x314.jpg)

## このリポジトリを見ている人へ
記事ネタのIssueを立てて貰えれば、編集部から記事化のお声掛けします。

## 執筆ガイド

1. 記事ネタの骨子となるIssue作成  
   [Issues](https://github.com/bizreach/engineers-blog/issues/new) を作成して、テンプレートにあわせて記事ネタを書きます。

1. 編集部確認と担当割り当て
   Issueを編集部でレビューし、問題なければ担当編集を割り当てます。  
   参考: [レビューフロー](https://github.com/bizreach/engineers-blog/wiki/レビューフロー)

1. 記事ファイル作成  
   まずはこのリポジトリをcloneします。  
   執筆する記事のタイトルに対応するURLを決め、骨子のIssue番号と合わせて以下のパスで `index.md` を作成します。
   `content/posts/{骨子のIssue番号}/{記事のタイトル}/index.md`  
   画像は `index.md` と同じディレクトリに入れます。  
   記事のURLは `https://tech.bizreach.co.jp/posts/{骨子のIssue番号}/{記事のタイトル}/` になります。

1. 記事を執筆
   作成した `index.md` にMarkdown形式で記事を書きます。  
   Front Matter と呼ばれる下記メタデータをファイルの先頭に記載してください。
...
