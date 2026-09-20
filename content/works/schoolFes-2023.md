---
workId: 4
title: 文化祭で用いるスタッフ向け業務アプリケーション
description: 文化祭の出し物で用いるスタッフ向けの業務アプリケーション
createDate: 2023-11-11
pinned: false
icon: material-symbols-two-pager
thumbnail: /images/works/schoolFes-2023/userQRShow.png
draft: false
mainCategory: WebSite
category:
- icon: material-symbols-two-pager
  label: WebSite
headerLinks:
- label: Qiita
  icon: simple-icons-qiita
  to: 'https://qiita.com/mendoitarou_/items/8dbc174a6d1b55fb073d'
  target: '_blank'
---
文化祭の出し物でスタッフ向けに作成した業務アプリケーション。

Qiitaの記事は作成後数ヶ月以内に書いたものですので、そちらのほうが詳しく記載されている可能性が高いです。

持っている機能は主に「アカウント登録」と「スコア登録」、「スコアランキング確認」のみ。

「その日のスコアランキングで1位となった方に景品を送る」というニーズが発生したため、開発した。

アカウント登録はGoogleアカウントのみに絞り、メールアドレスを入手した。これにより後日連絡する手段を得ることができた。

以下の理由からGoogleアカウントを選定した。

- 学内の生徒は必ず所持している。
- ログイン実装が容易であった。
- 比較的アカウント所持している可能性が高いと予想される。

スコアランキングはWebページでいつでも閲覧可能な状態とし、模擬店の出店場所でもプロジェクターによる投影を行った。

スコアランキングという特性上、リアルタイムで更新を行う必要がある。そのため、WebSocketによる通信を行いランキング更新時に自動で更新するようにした。

プロジェクターではランキング以外にもお知らせやアカウントページまでのQRコードを表示し、WebSocketにより動的に内容を変更できるようにした。

スコア登録の際、ユーザ側で生成した期限付きQRコードをスキャンすることで不正を防止することにしたが、効果やそもそも不正をする可能性があるかは不明である。しかし、QRコードでユーザを識別することは利便性をに繋がったと考えている。

念の為、識別番号を色付き大きめのテキストで表示した。念の為確認するダイアログも表示したためミスに気づくことができるようにしている。

寝不足状態で作成したため非常に作りが悪く、バグまみれな恐ろしいプログラムが出来上がった。

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
                },
                {
                    icon: devicon-nodejs,
                    title: Node.js,
                    description: WebSocketでの通信を行うために採用
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
                    description: フロントエンド・PHPはこっちで動かす
                },
                {
                    icon: mdi-server,
                    title: VPS,
                    description: WebSocketはどうしてもレンタルサーバでは動かないのでVPSで稼働
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
    '/images/works/schoolFes-2023/top.png',
    '/images/works/schoolFes-2023/input.png',
    '/images/works/schoolFes-2023/input_3.png',
    '/images/works/schoolFes-2023/input_2.png',
    '/images/works/schoolFes-2023/area_select.png',
    '/images/works/schoolFes-2023/userQRShow.png',
    '/images/works/schoolFes-2023/FrontInfoPanel.png',
    '/images/works/schoolFes-2023/GoogleLogin.png'
]
---
::
