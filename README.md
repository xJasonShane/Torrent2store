# Torrent2store
**[简体中文](./README.md)|[English](./README_en.md)|[日本語](./README_jp.md)**

# 仓库介绍
本仓库用于存储自制或源自网络的torrent文件或磁力链接，并根据资源进行分类共享;旨在为个人存储相关资源或为他人提供资源提供便利

# 资源宗旨
本仓库内所分享的所有资源(包含但不限于torrent文件和磁力链接)均为自制或网络资源，若资源内容不符合您所在当地法律或相关规定，本仓库不承担任何责任，使用者请自行判断资源是否合法合规，并对违规内容及时进行删除
本仓库欢迎所有用户共同维护或完善资源内容，若发现任何问题或有改进建议，欢迎提交issue或pull request

# 资源Tracker服务器
本仓库内的自制资源均采用[TrackersListCollection](https://github.com/XIU2/TrackersListCollection)项目提供的Tracker服务器清单

# 资源分类
资源类型|英文分类|资源内容
---|---|---
番剧|Anime|中国动漫、日本番剧等内容
电影|Movie|中国电影等内容
影剧|TV|全球各国家影剧等内容

注：若番剧存在电影资源则划分为电影分类，若影剧存在电影资源同步划分为电影分类

# 命名规则
- 文件夹名称：英文分类|中文分类
- Anime|番剧：
  - 首映年份 官方名称/(中文译名) [tmdbid=******] (里/性)
  - 如:2001 颜のない月/无颜之月 [tmdbid=96624] (里)
- Movie|电影：
  - 首映年份 官方名称/(中文译名) [tmdbid=******] (国家/地区)
  - 如：2016 君の名は。/你的名字。 [tmdbid=372058] (日本)
- TV|影剧：
  - 首映年份 官方名称/(中文译名) [tmdbid=******] (国家/地区)
  - 如:2023 三体 [tmdbid=204541] (中国)
- 注释：
  - 上述命名规则中()内为可选，根据实际情况填写
  - 若资源为中国大陆地区资源或无中文译名，可省略()内内容
  - 为统一资源命名规范，所有资源资料默认取自[TMDB](https://www.themoviedb.org/)站点，若该站点没有相关资料，则不填写tmdbid词条
  - 首映年份为资源地区首映时间节点，不包含其他国家上映时间
  - Anime资源中(里/性)中**里**代表番剧资源为**里番资源**即内容包含性行为描写，**性**代表番剧资源内包含性器官描写或隐喻但无实际性行为描写
  - 本仓库资源默认包含简体中文字幕，若资源无简体中文字幕，将在资源名称后添加[无字幕/繁体]标注
  - 若资源含有特殊内容需要备注，将在torrent文件命名的最后进行标注

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
