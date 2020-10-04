# my env ansible

## 環境

```
miro@DESKTOP-COPPFIB ~> uname  -a
Linux DESKTOP-COPPFIB 4.4.0-19041-Microsoft #488-Microsoft Mon Sep 01 13:43:00 PST 2020 x86_64 x86_64 x86_64 GNU/Linux

miro@DESKTOP-COPPFIB ~> cat /etc/lsb-release 
DISTRIB_ID=Ubuntu
DISTRIB_RELEASE=18.04
DISTRIB_CODENAME=bionic
DISTRIB_DESCRIPTION="Ubuntu 18.04.5 LTS"
```

## 構成

- original 単体で入れるパッケージ群これはパスして実行しても問題ありません
- power-shell-core パワーシェルコアを入れます
- python3 Python3入れます
- gatsby gatsby-cliをインストールします、尚インストールの途中でnodejs npmを入れています。
- ansible ansibleホストのためにansibleとlinterをインストールします。

## 注意

- role/gatsbyでnpmを操作していますがコミュニティのモジュールをインストールしなければいけないため代わりに、commandで書いています。

gatsby-cliは手動でサイトのテンプレを引っ張て来て

```
npm install
gatsby develop
```
してください、npm istallが引っ張て来たソースによって動作が変わるためです。

