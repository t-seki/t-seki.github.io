---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "2020/03/31 日記"
subtitle: ""
summary: ""
authors: [tseki]
tags: [diary]
categories: [Diary]
date: 2020-03-31T16:54:01+09:00
lastmod: 2020-03-31T16:54:01+09:00
featured: false
draft: true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
こんばんは。tsekiです。  


1. [Hugo とは]({{< ref "#1-hugo-とは" >}})
2. [Hugo サイトを作成する]({{< ref "#2-hugo-サイトを作成する">}})
3. GitHub でリポジトリを作成する
4. サイトをリポジトリに push する

---

## 1. Hugo とは

Hugo は Go 言語で作られたオープンソースの静的サイトジェネレーターです。

{{< blogcard url="https://gohugo.io" >}}
 
非常にビルドが速く、  
細かいデザインを気にしなくてもテーマを使ってある程度のサイトを作れます。  
自分の好みにカスタマイズを行いたい場合でもできると思いますが、  
まだテンプレートエンジンの仕組みの理解に加えて、  
HTML,CSS等の知識が乏しいので自分には難しいです。

各OS向けにインストール方法が書かれていますので、  
まずは、インストールを行ってください。

{{< blogcard url="https://gohugo.io/getting-started/installing/" >}}

## 2. Hugo サイトを作成する

適当なディレクトリを作成し、CLIで以下のコマンドを実行します。

```bash
hugo new site my-site
```
