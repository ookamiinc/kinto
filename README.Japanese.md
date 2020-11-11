# Kinto

[English](README.md)

### 目次

- [はじめに](#はじめに)
- [ダウンロード](#ダウンロード)
- [バグ報告や提案](#バグ報告や提案)
- [開発](#開発)
- [謝辞](#謝辞)

## はじめに

![Demo](https://user-images.githubusercontent.com/3750705/58846844-a06cc500-86bb-11e9-8258-745da818b5fe.gif)

日本語テキストが画面に描画されるとき、グリフのサイズやベースラインのアライメントが不適切で、文字が美しく表示されないことがよくあります。 これは数字やラテン文字が日本語の文字と一緒に表示されるときに顕著になるので、インターフェース要素を読みづらくする原因となります。 インターフェースのデザイン時からリリース時までに対応して、さまざまな画面環境でグリフや文字設定を調整することも、複雑で耐え難いことです。

そこでKintoの出番です。 Kintoは、 _画面およびUI向け_ ラテン文字書体とサイズやバランスがマッチするよう元の書体から調整された日本語フォントファミリーです。 このフォントの日本語グリフは、フォントファミリー内の他のグリフとベースラインを合わせたまま単純縮小されています。 その際に、日本語グリフは4.4%縮小 (100% → 95.6%) されています。 これはiOSがシステムフォントを使用して日本語テキストを描画する方法を真似たものです。 これによって、この書体はiOS用の日本語インターフェースをデザインするのに適したものとなっています。

Kintoは人気のあるサンセリフ書体の多くと合わせて使えます。たとえば、[Apple San Francisco](https://developer.apple.com/fonts/)、[Google Roboto](https://fonts.google.com/specimen/Roboto)、[Segoe UI](https://docs.microsoft.com/en-us/typography/font-list/segoe-ui)、[Inter](https://github.com/rsms/inter)、Arial、Helveticaなどです。

---

Kintoには6種類のウェイトが含まれます。上から順に、Thin、Light、Regular、Medium、Bold、Blackです。
<p align="left">
  <img src="https://user-images.githubusercontent.com/3750705/58760144-e5371580-856e-11e9-89cd-594487442732.png" width="400px">
</p>


## ダウンロード

[最新のmasterをダウンロードしてください](https://github.com/ookamiinc/kinto/archive/master.zip) - TTF、OTF、EOT、WOFF、WOFF2が含まれます。


## バグ報告や提案
Github [イシュー](https://github.com/ookamiinc/kinto/issues)を作成して、バグに関する情報をできる限りたくさん提示してください。たとえば、画像やエラーコードなどです。やり方をできるだけ統一するために、 `ISSUE_TEMPLATE.md` に書かれたガイドラインに従ってください。

## 開発

Github上のリポジトリをあなたのアカウントでフォークして、それをローカルにクローンしてください。

新機能の追加やバグフィックスに関しては、まずメインリポジトリ上にイシューを作成してください（そうすれば私たちは、リリースごとに何を含めているのかを追跡できます）。そして、あなたのフォークからオリジナルの `develop` ブランチにプルリクエストを送ってください。変更に対するレビューをやりやすくするために、プルリクエストの背景をできるだけ簡潔に記載してください。

## 謝辞

本プロジェクトは、[Google Noto Fonts](https://www.google.com/get/noto/)プロジェクトに含まれている[Noto Sans JP](https://fonts.google.com/specimen/Noto+Sans+JP)に基づいています。

→ [Noto Fonts リポジトリ](https://github.com/googlefonts/noto-fonts) <br>
→ [Noto CJK リポジトリ](https://github.com/googlefonts/noto-cjk)

---

English Readme by @riomarmccartney & @nancytru
日本語Readme by @matarillo

## お問い合わせ

→ design@ookamiinc.com
