---
workId: 12
title: 簡単に拡張可能な診断システム
description: 学校の授業で作成したWebアプリケーション
createDate: 2025-10-08
pinned: false
icon: material-symbols-two-pager
thumbnail: /images/works/school-work-project/top.png
draft: false
mainCategory: WebSite
category:
- icon: material-symbols-two-pager
  label: WebSite
---
テンプレート方式を採用することで、簡単に拡張可能な選択肢方式の診断システムです。

SPAで、構成ファイルを参照しページテンプレートに対しテキストや画面推移を適用させることで、柔軟性を確保しています。

百聞は一見にしかず。ギャラリーにいくつかテンプレートを表示しているので見てみてください。

また、テキストは言語ごとに構成ファイルを分けることで多言語化も可能としています。

構成ファイルはJSON形式なので、編集しやすくツールを用いればGUIによるグラフィカルな編集も可能です。

このアプリケーションはシンプルなHTML, CSS, JavaScriptのみで構成されているため、一般的なWebサーバでも公開可能です。

これは、企業が既存のホームページを公開している基盤をそのまま利用できるようにするためです。

コストを抑えることもできるようにしています。

テンプレートやUI/UXを工夫することで直感的に操作できるようにしているほか、実際に利用するユーザの声を反映することでより使いやすいアプリケーションを開発しました。

しかし、まだまだ改善点が多いのは事実です。来年度、引き継ぎが行われ、よりよいアプリケーションになることを期待しています。

開発は共同開発で行いました。一緒に設計から開発までしてくれた友人二人には感謝しています。本当にありがとうございました。

共同開発では、GitHubを用いたコード管理、GitHub Projectを用いたタスク管理を行いました。

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
            icon: mdi-library-shelves,
            title: ライブラリ,
            items: [
                {
                    icon: devicon-tailwindcss,
                    title: 'Tailwind CSS',
                    description: 'CSSフレームワークを用いることで、モダンなUIを実現。'
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
    '/images/works/school-work-project/top.png',
    '/images/works/school-work-project/long-text.png',
    '/images/works/school-work-project/select-dropdown.png',
    '/images/works/school-work-project/select-assets.png',
    '/images/works/school-work-project/assets-zoom.png',
    '/images/works/school-work-project/select-twoButton.png',
    '/images/works/school-work-project/result-textAndAsset.png',
    '/images/works/school-work-project/show-log.png',
    '/images/works/school-work-project/change_lang.png'
]
---
::
