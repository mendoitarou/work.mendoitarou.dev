---
workId: 1
title: MyWork(このサイト)
description: めんどい太郎がこれまでにやってきたことを書いたページ
createDate: 2026-03-01
pinned: true
icon: material-symbols-two-pager
thumbnail: /images/works/my-work-page/top-image.png
draft: false
mainCategory: WebSite
category:
- icon: material-symbols-two-pager
  label: WebSite
headerLinks:
- label: WebSite
  icon: material-symbols-two-pager
  to: 'ttps://work.mendoitarou.dev/'
  target: '_blank'
- label: GitHub
  icon: i-simple-icons-github
  to: 'https://github.com/mendoitarou/work.mendoitarou.dev'
  target: '_blank'
---
私、めんどい太郎がこれまでにやってきたことを紹介するWebページです。

公開を終了したもの、身内向けに作ったものなど実物を公開できないもの等も一部紹介しています。

これまで結構多くのプログラム等を作ってきたので、思い出しながら作成しています。

そのため、今後もコンテンツは追加されていくと思われます。

このページは、Nuxt.jsの学習も兼ねて作成しました。実際に様々なことを学ぶことができました。

このページを元に別のページ(特にブログなんかは似ている箇所があるので)を改良する予定です。

なお、このWebページのソースコードはGitHubで公開しています。

::TechCard
---
cards: {
    title: 使用技術,
    items: [
        {
            title: フレームワーク,
            items: [
                {
                    icon: i-logos-nuxt-icon,
                    title: Nuxt.js,
                    description: モダンなWebページの作成を可能にするため採用
                }
            ]
        },
        {
            title: ライブラリ,
            items: [
                {
                    icon: i-logos-nuxt-icon,
                    title: Nuxt UI,
                    description: UIデザインをライブラリに任せることで、ページの内容に集中して開発が可能に
                },
                {
                    icon: i-logos-nuxt-icon,
                    title: Nuxt Content,
                    description: 各ページのレイアウトを統一化、本文をMarkdownで表現可能に
                }
            ]
        }
    ]
}
---
::
