<div align="center">
# Torrent2store
**[简体中文](./README.md)|[English](./README_en.md)|[日本語](./README_jp.md)**
</div>

# 倉庫の紹介
このウェブサイトは、自作またはネットワークから取得したtorrentファイルやマグネットリンクを保存し、リソースに基づいて分類して共有することを目的としています。個人が関連するリソースを保存したり、他者にリソースを提供するための利便性を提供することを目的としています。

# リソースの目的
このウェブサイトで共有されているすべてのリソース（torrentファイルやマグネットリンクを含むがこれらに限定されない）は、自作またはネットワーク上のリソースです。リソースの内容がお住まいの地域の法律や関連規定に違反している場合、当ウェブサイトは一切の責任を負いません。利用者は、リソースが合法かどうかを自己の判断で確認し、違反しているコンテンツを速やかに削除してください。
このリポジトリでは、すべてのユーザーがリソースの内容を共同で維持または改善することを歓迎します。問題がある場合や改善の提案がある場合は、issueやpull requestを提出してください。

# リソーストラッカーサーバー
この倉庫内の自作リソースは、[TrackersListCollection](https://github.com/XIU2/TrackersListCollection)プロジェクトが提供するトラッカーサーバーのリストを使用しています。

# リソース分類
リソースの種類|英語の分類|リソースの内容
---|---|---
番剧|Anime|中国のアニメ、日本のアニメなどのコンテンツ
电影|Movie|中国映画などのコンテンツ
影剧|TV|世界各国の映画・テレビ番組などのコンテンツ

# 命名規則
- フォルダ名：英語分類|中国語分類
- アニメ|番剧：
  - 公開年 公式名称/(中国語訳名) [tmdbid=******] (里/性)
  - 例:2001 顔のない月/無顔の月 [tmdbid=96624] (里)
- 映画|电影：
  - 公開年 公式名称/(中国語訳名) [tmdbid=******] (国/地域)
  - 例：2016 君の名は。/你的名字。[tmdbid=372058] (日本)
- TV|影剧：
  - 公開年 公式名称/(中国語訳名) [tmdbid=******] (国/地域)
  - 例:2023 三体 [tmdbid=204541] (中国)
- 注釈：
  - 上記の命名規則で、()内は任意であり、実際の状況に合わせて記入してください。
  - リソースが中国大陸地域のリソースまたは中国語の翻訳がない場合は、()内の内容を省略できます
  - リソースの命名規則を統一するため、すべてのリソース情報は[TMDB]（https://www.themoviedb.org/）サイトから取得されます。該当する情報がない場合は、tmdbid項目に記入しないでください。
  - 初公開年はリソース地域の初公開時間の節点であり、他国での上映時間は含まれていません。
  - アニメ資料の中で（里/性）で**里**は**里番資料**を表し、つまり性行為の描写が含まれています。**性**はアニメ資料の中に性器の描写や暗喩がありますが、実際の性行為の描写はありません。
  - このリポジトリのリソースには簡体字の字幕が含まれています。もしリソースに簡体字の字幕がない場合は、リソース名の後に[無字幕/繁体]と表示されます
  - トレントファイルの名前の最後に、特別な内容がある場合には注釈を付ける

# License
MIT License

Copyright (c) 2025 Jason Shane

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
