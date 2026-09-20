---
workId: 5
title: 文化祭で用いる会計システム
description: 文化祭の出し物で用いる会計システム
createDate: 2025-07-03
pinned: false
icon: material-symbols-two-pager
thumbnail: /images/works/schoolFes-2025/staff-top.png
draft: false
mainCategory: WebSite
category:
- icon: material-symbols-two-pager
  label: WebSite
headerLinks:
- label: Qiita
  icon: simple-icons-qiita
  to: 'https://qiita.com/mendoitarou_/items/6cfefd1a0e54e2866382'
  target: '_blank' 
---
文化祭の出し物で用いる会計システムを自作した。

Qiitaの記事は作成後数ヶ月以内に書いたものですので、そちらのほうが詳しく記載されている可能性が高い。

バックエンドは自身で、フロントエンドはAIにぶん投げという開発方法を取り入れた。

フロントエンドではSPA方式を採用。シンプルなUIにすることで、操作するスタッフが困惑しないように注意した。

また、このアプリケーションへのアクセスにはCloudflare Accessによるアクセス制限を用いることで第三者がアクセスする可能性を減らした。

アプリケーション側でもユーザ認証を行っており、会計スタッフは会計処理のみを、模擬店管理者は商品の管理や会計処理履歴の閲覧が行えるようにした。

文化祭の出し物で用いるシステムのように、多くのユーザが実際に利用するシステムを作成すると毎回学びがある。

特に今回は、テストの重要性を改めて感じることとなった。

来年度(2026年)には、別システムとの連携や一部未実装項目の実装、バグ修正などを行うことでより使いやすく便利なアプリケーションを作成することを目標としている。

特に、商品完成時に購入者がなかなか見つからないということは大きな課題であるため、スマートフォンへのプッシュ通知を行えるようにすることも目標の一つである。

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
                    icon: devicon-nextjs,
                    title: Next.js,
                    description: Webフレームワークとして有名なNext.jsを採用
                }
            ]
        },
        {
            icon: material-symbols-code-xml,
            title: バックエンド,
            items: [
                {
                    icon: devicon-express,
                    title: Express.js,
                    description: APIサーバの開発で多く利用されているExpress.jsを採用
                }
            ]
        },
        {
            icon: mdi-server,
            title: デプロイ環境,
            items: [
                {
                    icon: mdi-server,
                    title: VPS,
                    description: VPS上にデプロイ
                },
                {
                    icon: devicon-docker,
                    title: Docker,
                    description: デプロイにDockerを活用。環境構築の手間を削減
                },
                {
                    icon: devicon-cloudflare,
                    title: Cloudflare,
                    description: '公開にはCloudflare Tunnel・Accessを利用し、セキュアなアプリ公開を実現'
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
    '/images/works/schoolFes-2025/login.png',
    '/images/works/schoolFes-2025/manager-top.png',
    '/images/works/schoolFes-2025/product_manage-top.png',
    '/images/works/schoolFes-2025/sale_cart.png',
    '/images/works/schoolFes-2025/sale_confirm.png',
    '/images/works/schoolFes-2025/sale_top.png',
    '/images/works/schoolFes-2025/staff-top.png'
]
---
::

