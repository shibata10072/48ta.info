---
title: "Manjaro Gnome環境の構築"
date: 2019-05-04T13:13:04+09:00
draft: false
---

![ManjaroのGnome版](/images/manjaro-gnome.png)

## やったこと

1. 使ってない SSD フォーマット。
2. [Manjaro Gnome Edition](https://manjaro.org/download/gnome/)をインストール。
3. Manjaro Setting Tool と Gnome の設定ツールを使ってなんか色々整える。
4. [Gnome Shell Extensions](https://extensions.gnome.org/)で足りない機能ぶっこむ。
5. Pacman で適当にパッケージを突っ込む。

## 使ってるやつ

### Gnome Shell Extensions

- Activities Configurator
  - アクティビティ非表示と Topbar 透明化。
- Applications menu
  - アプリ一覧。Arc Menu ほど機能はいらない。
- Coverflow alt-tab
  - AltTab がオシャレになる。
- Dash to Dock
- Workspace to dock
  - ど定番２種。
- Kstatusnotifieritem/appindicator support
- Topicons plus
  - Topbar に通知追加。
- openweather
  - 天気予報。
- Pamac update indicator
  - パッケージ更新通知。
- Native window placement
- Removable drive menu
- User theme

### Gnome Theme

- Window Theme:Qogir
- Shell Theme:Qogir
- Icon:Papirus

## 所感

### Arch or Manjaro,Gnome or deepin

いつも Arch を使っていたのですが、アップデートで Network Manager、X Window、Linux Kernel のどれかがぶっ壊れる感じに疲れたので、安定する Manjaro にしてみました。
インストール馬鹿楽だし、最初から Pamac 入ってるし、Manjaro がよく使われる理由が少しわかったような気がします。

デスクトップ環境はいつもの Gnome と deepin で結構悩む。悩んで、安定を取って Gnome にしたのですが、試しに使ってみた deepin のほうが綺麗だし使いやすい感有り。なのでそのうちちゃんと deepin を使ってみる予定です。

Gnome の Extensions 前提の設計は、アップデートでバンバン死んだりするから安定しない。拡張の選択肢数は圧倒的に Gnome なんですけど、時代は選択肢数よりも統一された思想設計なんじゃないですかね。

### Windows いらなくね？（いつもの）

ネトゲに飽きてきている → ゲームしないなら Windows いらなくね？→Linux 使うか → ついでになんか作るか  
そんな流れで Blog も蘇生させました、全く続く気はしません。
