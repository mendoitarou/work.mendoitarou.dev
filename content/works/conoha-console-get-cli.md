---
workId: 9
title: 'ConoHa Console Get Tool'
description: ConoHa VPSサーバのサーバコンソールへのアクセスURLをCLIでサクッと取得するためのツール
createDate: 2025-12-04
pinned: false
icon: material-symbols-service-toolbox-outline
thumbnail: /images/works/conoha-console-get-cli/ConoHa-Console-Get-Tool.png
draft: false
mainCategory: Tools
category:
- icon: material-symbols-service-toolbox-outline
  label: Tools
headerLinks:
- label: Qiita
  icon: simple-icons-qiita
  to: 'https://qiita.com/mendoitarou_/items/b72f060b8b211b127ef5'
  target: '_blank'
- label: GitHub
  icon: i-simple-icons-github
  to: 'https://github.com/mendoitarou/ConoHa-Console-Get-Tool'
  target: '_blank'
---
ConoHa VPSサーバのサーバコンソールへのアクセスURLをCLIでサクッと取得するためのツール。

外でSSHするのもいいが、ポート制限のある環境ではSSHができないときもある。

このツールで取得できるアクセスURLはWeb経由でコンソールへアクセスできるため、その心配はいらないのである。

Qiita Advent Calendarの別記事を書いている時に参照していたConoHa APIのリファレンスに気になるエンドポイントがあった。

ConoHa VPSサーバのサーバコンソールへのアクセスURLを取得するためのエンドポイントである。

コントロールパネルで取得できそうになかったが、APIを毎回叩くのもだるいのでCLIツールとして作ってみた。

といいつつ、実はカレンダーのネタにするために作ったプログラムです。

実際便利ではありますが、基本SSHするからあんまり使わないよね()

しかも、エラーハンドリングを実装してないので実用性はあんまりないです。使わないので放置されてしまっている。

CLIツールとAPIを叩く練習にはなりました。これもいつか改良してあげたいところ。

もしGitHubのリポジトリがアーカイブされていたら.....そういうことです。

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
                    icon: devicon-nodejs,
                    title: Node.js,
                    description: 普段使っている言語なので実装しやすいため選定
                }
            ]
        }
    ]
}
---
::
