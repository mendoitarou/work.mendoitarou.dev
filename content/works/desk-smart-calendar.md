---
workId: 7
title: 自作卓上スマートカレンダー
description: 自作した卓上スマートカレンダー
createDate: 2024-12-12
pinned: false
icon: material-symbols-home-iot-device-outline
thumbnail: /images/works/desk-smart-calendar/Desk_Smart_Calendar.png
draft: false
mainCategory: 'IoT Device'
category:
- icon: material-symbols-home-iot-device-outline
  label: 'IoT Device'
headerLinks:
- label: GitHub
  icon: i-simple-icons-github
  to: 'https://github.com/mendoitarou/Desk_Smart_Calendar'
  target: '_blank'
---
日付と天気、ニュースなどの情報を表示する卓上スマートカレンダー。

Raspberry Pi Zeroと電子ペーパーHATが余っていたので作ってみました。

私の机にはAmazonのEcho Show 5がありますが、画面が移り変わり続けるため日付は常時表示されていません。

今日の日付が不意に知りたくなったとき、これは非常に不便です。そのため、今日の日付を表示しておけるオブジェクトがほしいと思っていました。

ただ日付を表示するだけでは面白みがないため、天気やニュースを取得し表示できるようにしてみました。

しかし、実際にはかなり使い勝手が悪いです。また、結構バグが残っています。

最近は使わなくなってしまったのでバグ修正はかなり後回しになってしまっています。

詳しくはGitHubのREADMEを参照してください。

なお、このプログラムのソースコードはGitHubで公開しています。

::TechCard
---
cards: {
    title: 使用技術,
    items: [
        {
            icon: material-symbols-code-xml,
            title: 言語,
            items: [
                {
                    icon: devicon-python,
                    title: Python,
                    description: 'Raspberry Piと相性の良いPythonで実装。'
                }
            ]
        },
        {
            icon: material-symbols-developer-board,
            title: ハードウェア,
            items: [
                {
                    icon: devicon-raspberrypi,
                    title: 'RaspberryPi Zero WH',
                    description: 小型でLinuxも動作するためちょうどよい。実際には余っていたので使用したのだが。
                },
                {
                    icon: material-symbols-edit-document-outline,
                    title: '電子ペーパー HAT',
                    description: '一度描写すればしばらくは変更がないので電子ペーパーが適している。製品名: 「250x122, 2.13inch E-Ink display HAT for Raspberry Pi」'
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
    '/images/works/desk-smart-calendar/Picture.JPG'
]
---
::
