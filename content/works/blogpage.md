---
workId: 16
title: ブログ
description: めんどい太郎のブログ
createDate: 2026-03-30
pinned: false
icon: material-symbols-two-pager
thumbnail: /images/works/blogpage/top.png
draft: false
mainCategory: WebSite
category:
- icon: material-symbols-two-pager
  label: WebSite
headerLinks:
- label: WebSite
  icon: material-symbols-two-pager
  to: 'https://blog.mendoitarou.com/'
  target: '_blank'
---
私のブログ。

work.mendoitarou.comを作ったことにより、Nuxt.jsの扱いに慣れてきたため完全再構築。

このページのコードを多々流用しているため、結構UIが似ている。似ているどころかほぼ同じ。

ブログの中身は結構少ない。今後増やしていく予定。

記事の検索機能を追加しようと目論んでいるが、可能かどうかは不明。

::TechCard
---
cards: {
    title: 使用技術,
    items: [
        {
            icon: material-symbols-code-xml,
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
            icon: mdi-library-shelves,
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

::ImageGalary
---
images: [
    '/images/works/blogpage/top.png'
]
---
::
