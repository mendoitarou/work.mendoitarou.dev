---
workId: 10
title: CCaslII_DockerImage
description: CCaslII(Linux板)のDockerイメージ
createDate: 2026-02-23
pinned: false
icon: material-symbols-service-toolbox-outline
thumbnail: /images/works/ccaslII-docker-image/CCaslII_DockerImage.png
draft: false
mainCategory: Tools
category:
- icon: material-symbols-service-toolbox-outline
  label: Tools
headerLinks:
- label: 'Docker Hub'
  icon: devicon-docker
  to: 'https://hub.docker.com/r/mendoitarou/ccasl2'
  target: '_blank'
- label: GitHub
  icon: i-simple-icons-github
  to: 'https://github.com/mendoitarou/CCaslII_DockerImage'
  target: '_blank'
---
CCaslIIを手軽に動かすためのDockerイメージです。

CCaslIIは32bit環境で動作するアプリケーションです。そのため、インストールしてそのままのUbuntuでは動作しません。

さくっと使いたい！ということで、動かすためのセットアップとバイナリの配置、権限付与まで行った状態にしています。

授業で使ったのですが、最初の環境構築で手間取っていた様子だったので、より簡単に使える環境を用意しました。

(先生に使ってもらえるかはわかりません。言いにいけよというね。)

CCaslIIとは、アセンブラ言語を動かすためのエミュレータです。

CCaslIIについては、[元のアプリケーションのページ](https://hyamag.sakura.ne.jp/hysoft/ccasl2_linux/)を参照してください。

今後、READMEに簡単に使うための実用的なほぼコピペで動くコマンド例を載せたいと思っています。

::TechCard
---
cards: {
    title: 使用技術,
    items: [
        {
            icon: material-symbols-computer-arrow-up-outline,
            title: OS,
            items: [
                {
                    icon: devicon-ubuntu,
                    title: Ubuntu,
                    description: ベースイメージ、OSとしてUbuntuを採用。
                }
            ]
        },
        {
            icon: mdi-cube-outline,
            title: アプリケーション,
            items: [
                {
                    icon: material-symbols-machine-image,
                    title: CCaslII(Linux版),
                    description: 「COMETII」およびそのアセンブラ言語「CASLII」のシミュレータ。
                }
            ]
        }
    ]
}
---
::
