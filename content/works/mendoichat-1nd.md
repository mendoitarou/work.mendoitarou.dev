---
workId: 3
title: めんどいチャット(第一世代)
description: めんどいチャットの第一世代。
createDate: 2021-06-26
pinned: true
icon: material-symbols-two-pager
thumbnail: /images/works/mendoichat-1nd/top-image.png
draft: false
mainCategory: WebSite
category:
- icon: material-symbols-two-pager
  label: WebSite
headerLinks:
- label: WebSite
  icon: material-symbols-two-pager
  to: 'https://chat.mendoitarou.com/'
  target: '_blank'
---
当時、スマートフォンを所持していなかった友達と連絡を取り合うために開発した。

Nintendo SwitchでWebブラウザが起動できる点に着目し、シンプルなWebアプリケーションとして設計。

現在は使われていないことや、脆弱性が潜んでいる可能性があることを理由にサービス一時停止中。

WebSocket等のリアルタイム通信は行われておらず、PHPに対するGETやPOSTだけで実装されている。

現在、第二世代の開発計画が進行中。しかし、私生活の多忙などによって2024年からプロジェクトは凍結状態である。

[hub.mendoichat.jp](https://hub.mendoichat.jp/)

ギャラリーにてスクリーンショットを掲載しています。一部のスクリーンショットは簡易的に環境を再現したものですので、当時と異なる可能性がありますがご了承ください。

なお、このWebページのソースコードは非公開です。

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
                    icon: devicon-html5,
                    title: 'HTML, CSS, JavaScript',
                    description: 'ピュアなHTML, CSS, JavaScriptで構成'
                }
            ]
        },
        {
            icon: material-symbols-code-xml,
            title: バックエンド,
            items: [
                {
                    icon: devicon-php,
                    title: PHP,
                    description: 制約の多いレンタルサーバでも動作するPHP
                }
            ]
        },
        {
            icon: mdi-server,
            title: デプロイ環境,
            items: [
                {
                    icon: mdi-server,
                    title: レンタルサーバ,
                    description: レンタルサーバで動かす前提で設計を行いました。
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
    '/images/works/mendoichat-1nd/top-image.png',
    '/images/works/mendoichat-1nd/chatroom1.png',
    '/images/works/mendoichat-1nd/releasenote1.png',
    '/images/works/mendoichat-1nd/metaquest2.png'
]
---
::

