---
workId: 11
title: ブラウザチャイム
description: ブラウザで学校などのチャイムを鳴らせるツール
createDate: 2025-06-02
pinned: false
icon: material-symbols-service-toolbox-outline
thumbnail: /images/works/browser-chime/browser_chime.png
draft: false
mainCategory: Tools
category: [
    { icon: material-symbols-service-toolbox-outline, label: Tools }
]
headerLinks: [
    { label: GitHub, icon: i-simple-icons-github, to: 'https://github.com/mendoitarou/browser_chime', target: '_blank' }
]
---
2020年、世界的な流行り病によるパンデミックが発生し、学校がオンライン授業になるなど様々な影響がありました。

私もオンライン授業を受けていた時期があります。

そのとき、とある困りごとがありました。学校ではチャイムが鳴りますが、家ではチャイムは鳴らないのです。

チャイムが鳴らないので、授業の開始・終了が分かりづらいというのが私の困りごとです。

ということで、作りました。

GitHubに出したのは、この時作ったものを改良したバージョンです。

前は動けばいいやの精神なので時間を直書きしてましたが、JSONで時間を設定できるようにしました。

ブラウザチャイムという名の通り、ブラウザでチャイムを鳴らすことのできるツールです。

当時、私はChromebookを利用していたのでブラウザで動作するものを作りました。

純粋なJavaScriptで実装されています。それ故、時刻はコンピュータの設定時刻に依存しています。仕方ないですね。

なお、このWebページのソースコードはGitHubで公開しています。

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
        }
    ]
}
---
::

::ImageGalary
---
images: [
    '/images/works/browser-chime/sample.png'
]
---
::
