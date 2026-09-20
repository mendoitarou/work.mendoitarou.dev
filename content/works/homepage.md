---
workId: 15
title: ホームページ
description: めんどい太郎のホームページ
createDate: 2026-04-25
pinned: false
icon: material-symbols-two-pager
thumbnail: /images/works/homepage/top.png
draft: false
mainCategory: WebSite
category:
- icon: material-symbols-two-pager
  label: WebSite
headerLinks:
- label: WebSite
  icon: material-symbols-two-pager
  to: 'https://home.mendoitarou.com'
  target: '_blank'
- label: GitHub
  icon: i-simple-icons-github
  to: 'https://github.com/mendoitarou/home-page/'
  target: '_blank'
---
私のホームページ。

もともとは手書きのHTML,PHPで構成されていたが、Nuxt.jsを使ってモダンなページへ刷新。

多言語対応も実現。

ただし、内容がほぼありません。今後ちゃんと書いていく予定です。

自己紹介だけは書いてます。

ソースコードはGitHubで公開予定です。

::TechCard
---
cards: {
    title: 使用技術,
    items: [
        {
            icon: material-symbols-code-xml,
            title: フロントエンド,
            items: [
                {
                    icon: i-logos-nuxt-icon,
                    title: Nuxt.js,
                    description: モダンなページを実現するためにNuxt.jsを採用
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
                    title: Nuxt I18n,
                    description: 多言語対応を容易に可能なライブラリ。多言語対応の負担を減らすことで、モチベーションを向上。
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
    '/images/works/homepage/top.png'
]
---
::
