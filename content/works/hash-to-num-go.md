---
workId: 6
title: ハッシュ値を数値に変換するプログラム
description: SHA-256のハッシュ値を6ビットずつに区切り、数値に変換するプログラム。
createDate: 2025-12-20
pinned: false
icon: material-symbols-service-toolbox-outline
thumbnail: /images/gist-og-image.png
draft: false
mainCategory: Tools
category:
- icon: material-symbols-service-toolbox-outline
  label: Tools
headerLinks:
- label: GitHub
  icon: i-simple-icons-github
  to: 'https://gist.github.com/mendoitarou/7582ab69c8014129ea9f03d556276a00'
  target: '_blank'
---
文字列を数値の配列に変換するプログラム。

文字列をSHA-2556ハッシュ値に変換し、それを6ビットずつに区切り、それを数値データとして扱うことで変換している。

## このプログラムをなぜ作ったのか

ある程度自分の意思にかかわらないいくつかの数値を得たいが、再現性がほしいと考えていた。

そこで、再現性のあるハッシュ値をビットで区切りそれを数値として捉えることで上記の要件を満たせるのではないかと考えた。

その結果生まれたプログラム。

なぜそのような数値を得たかったのか、それは実にシンプルで掃除当番の割り振りを行うために出席番号を選ぶためである。

上から順番に区切る、乱数生成にて得られる数値を用いる、など方法は様々あるがこれでは私が自由に割り振りを行えてしまう可能性がある。

そこで、ハッシュ値という一般的に人間が暗算で予想することのできそうにない値を用いることにした。

また、ハッシュ値であれば再現性があるためプログラムを公開すれば誰でも同じ値を得ることができる。

これにより、自身の潔白を示すことができるのである。

.....実際には誰もそのようなことは気にしていないため、心配は無用である。

Go言語ではビットシフトなどの操作を行いやすいと考えているため、Go言語の練習に適していると考えたことも実装した理由の一つである。

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
                    icon: devicon-go,
                    title: 'Go',
                    description: 'Go言語の練習も兼ねて実装。'
                }
            ]
        }
    ]
}
---
::
