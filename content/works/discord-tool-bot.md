---
workId: 8
title: Discord_Tool_Bot
description: '自分用に作っているいろんなツールが詰まったDiscord BOT'
createDate: 2025-04-15
pinned: false
icon: simple-icons-discord
thumbnail: /images/works/discord-tool-bot/Discord_Tool_Bot.png
draft: false
mainCategory: 'Discord BOT'
category:
- icon: simple-icons-discord
  label: 'Discord BOT'
headerLinks:
- label: GitHub
  icon: i-simple-icons-github
  to: 'https://github.com/mendoitarou/Discord_Tool_Bot'
  target: '_blank'
---
自分と身内用に作成しているDiscord BOT。

主に以下の機能を持っている。

- ボイスチャンネル入退室通知
- テキストチャット読み上げ

未だにいくつか未対応の機能・仕様やバグがあります。修正しなくては。

テキストチャット読み上げには、VOICE VOXを用いています。

自分用に使っているので、実装の多くが不親切なものが多い。

コア機能が完成次第、別途分離してオープンソースなDiscord BOTとして公開予定。特にテキストチャット読み上げ機能など。

詳しくはGitHubのREADMEを参照してください。

なお、このプログラムのソースコードはGitHubで公開しています。

::TechCard
---
cards: {
    title: 使用技術,
    items: [
        {
            icon: mdi-library-shelves,
            title: ライブラリ,
            items: [
                {
                    icon: devicon-discordjs,
                    title: Discord.js,
                    description: 'Node.jsでDiscord BOTを作成することのできるライブラリ。'
                }
            ]
        },
        {
            icon: mdi-cube-outline,
            title: ソフトウェア,
            items: [
                {
                    icon: material-symbols-voice-chat-outline,
                    title: 'VOICE VOX',
                    description: テキストチャット読み上げの音声合成に使用。
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
                }
            ]
        }
    ]
}
---
::
