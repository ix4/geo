---
pageClass: routes
---

# social media

## bilibili

### 番剧

<Route author="DIYgod" example="/bilibili/bangumi/media/9192" path="/bilibili/bangumi/media/:mediaid" :paramsDesc="['fan drama media id, get from the drama homepage URL' ]"/>

### User tracking list

<Route author="wdssmq" example="/bilibili/user/bangumi/208259" path="/bilibili/user/bangumi/:uid" :paramsDesc="['userid']"/>

### UP Main Contribution

<Route author="DIYgod" example="/bilibili/user/video/2267573" path="/bilibili/user/video/:uid" :paramsDesc="['userid, can be found in the UP main homepage'] " radar="1"/>

### UP Main column

<Route author="lengthmin" example="/bilibili/user/article/334958638" path="/bilibili/user/article/:uid" :paramsDesc="['userid, can be found in the UP main homepage'] "/>

### UP Main News

<Route author="DIYgod" example="/bilibili/user/dynamic/2267573" path="/bilibili/user/dynamic/:uid" :paramsDesc="['userid, can be found in the UP main homepage'] " radar="1"/>

### UP Main Channel

<Route author="HenryQW" example="/bilibili/user/channel/142821407/49017" path="/bilibili/user/channel/:uid/:cid" :paramsDesc="['userid, available in UP main Find ', 'channel id in the home page, find ']"/> in the channel's URL

### UP Main default favorites

<Route author="DIYgod" example="/bilibili/user/fav/2267573" path="/bilibili/user/fav/:uid" :paramsDesc="['userid, can be found in the UP main homepage'] "/>

### UP Main non-default favorites

<Route author="Qixingchen" example="/bilibili/fav/756508/50948568" path="/bilibili/fav/:uid/:fid" :paramsDesc="['userid, can be found in the UP main homepage' , 'Favorite ID, which can be found in the URL of the favorites. The default favorites suggest using the UP main default favorites function']"/>

### UP Main Coin Video

<Route author="DIYgod" example="/bilibili/user/coin/2267573" path="/bilibili/user/coin/:uid" :paramsDesc="['userid, can be found in the UP main homepage'] "/>

### UP Main fan

<Route author="Qixingchen" example="/bilibili/user/followers/2267573" path="/bilibili/user/followers/:uid" :paramsDesc="['userid, can be found in the UP main homepage'] "/>

### UP Main user

<Route author="Qixingchen" example="/bilibili/user/followings/2267573" path="/bilibili/user/followings/:uid" :paramsDesc="['userid, can be found in the UP main homepage'] "/>

### Partition video

<Route author="DIYgod" example="/bilibili/partion/33" path="/bilibili/partion/:tid" :paramsDesc="['partition id']" radar="1">

Animation

MAD·AMV | MMD·3D | Short Films·Handbooks·Dubbing | General |
| ------- | ------ | -------------- | ---- |
| 24 | 25 | 47 | 27 |

Fan drama

| Serial Animation | Ending Animation | News | Official Extension |
| -------- | -------- | ---- | -------- |
| 33 | 32 | 51 | 152 |

Guochuang

| Domestic animation | Domestic original related | Puppet show | Information |
| -------- | ------------ | ------ | ---- |
| 153 | 168 | 169 | 170 |

music

Original music | Cover | VOCALOID·UTAU | Performance | Three-dimensional music | OP/ED/OST |
| -------- | ---- | ------------- | ---- | ---------- | ----- ---- | -------- |
| 28 | 31 | 30 | 59 | 29 | 54 |

dance

| House Dance | Three Yuan Dance | Dance Tutorial |
| ---- | ---------- | -------- |
| 20 | 154 | 156 |

game

Single game | eSports | Mobile Games | Online Games | Board Games | GMV |
| -------- | -------- | -------- | -------- | -------- | --- | ---- | ----- |
| 17 | 171 | 172 | 65 | 173 | 121 | 136 | 19 |

Technology

| Fun Science Popular Science | Wild Technology Association | Speech · Open Class | Xinghai | Digital | Machinery |
| ------------ | ------------ | ----------- | ---- | ---- | --- | ---- |
| 124 | 122 | 39 | 96 | 95 | 98 | 176 |

life

Funny | Daily | Food Circle | Animal Circle | Handmade | Painting | ASMR |
| ---- | ---- | ------ | ------ | ---- | ---- | ---- | ---- | ---- |
138 | 21 | 76 | 75 | 161 | 162 | 175 | 163 | 174 |

Ghost animal

Ghost Animal Training | Sound MAD | Human VOCALOID | Tutorial Demo |
| -------- | ------ | ------------- | -------- |
| 22 | 26 | 126 | 127 |

fashion

Beauty | Clothing | Fitness | Information |
| ---- | ---- | ---- | ---- |
| 157 | 158 | 164 | 159 |

ad

| Advertising |
| ---- |
| 166 |

entertainment

| Variety | Star | Korea Related |
| ---- | ---- | ---------- |
| 71 | 137 | 131 |

Movie

| Movie & TV Talk | Movie Clips | Short Films | Previews | News |
| -------- | -------- | ---- | --------- | ---- |
| 182 | 183 | 85 | 184 | 86 |

Documentary

| All | Humanities · History | Science · Exploration · Nature | Military | Society · Food · Travel |
| ---- | --------- | -------------- | ---- | -------------- |
| 177 | 37 | 178 | 179 | 180 |

the film

| All | Chinese Movies | European and American Movies | Japanese Movies | Other Countries |
| ---- | -------- | -------- | -------- | -------- |
| 23 | 147 | 145 | 146 | 83 |

TV series

| All | Domestic drama | Overseas drama |
| ---- | ------ | ------ |
| 11 | 185 | 187 |

</Route>

### Partition Video Leaderboard

<Route author="lengthmin" example="/bilibili/partion/ranking/171/3" path="/bilibili/partion/ranking/:tid/:days?" :paramsDesc="['Partition id, see table above ', 'The default is 7, which refers to the hot sort in the most recent days']"/>

### Video Collection List

<Route author="sxzz" example="/bilibili/video/page/39732828" path="/bilibili/video/page/:aid" :paramsDesc="[' can be found in the video page URL']"/>

### Video Review

<Route author="Qixingchen" example="/bilibili/video/reply/21669336" path="/bilibili/video/reply/:aid" :paramsDesc="[' can be found in the video page URL']"/>

### Video Barrage

<Route author="Qixingchen" example="/bilibili/video/danmaku/21669336/1" path="/bilibili/video/danmaku/:aid/:pid?" :paramsDesc="['Video AV number, available at Find the ',' sub-P number in the video page URL. Do not fill the default 1']"/>

### link Announcement

<Route author="Qixingchen" example="/bilibili/link/news/live" path="/bilibili/link/news/:product" :paramsDesc="['Announcement classification, including live broadcast: live small video: vc phase Book: wh']"/>

### Video Search

<Route author="Symty" example="/bilibili/vsearch/藤原千花" path="/bilibili/vsearch/:kw/:order?" :paramsDesc="['Search Keyword', 'Sort by, Synthetic: Totalrank Most clicks: click Latest release: pubdate (default) Maximum barrage: dm Maximum collection: stow']"/>

### User attention video dynamics

<Route author="LogicJake" example="/bilibili/followings/video/2267573" path="/bilibili/followings/video/:uid" :paramsDesc="['userid']">
::: warning Note

The user dynamic needs the cookie value after the b station logs in, so it can only be built by itself. For details, see the configuration module of the deployment page.

:::
</Route>

### User attention column

<Route author="woshiluo" example="/bilibili/followings/article/99800931" path="/bilibili/followings/article/:uid" :paramsdesc="['userid']">
::: warning Note

The user dynamic needs the cookie value after the b station logs in, so it can only be built by itself. For details, see the configuration module of the deployment page.

:::
</Route>

### Live broadcast

See [#哔哩哔哩直播直播](/live.html#哔哩哔哩直播)

### Live Search

See [#哔哩哔哩直播直播](/live.html#哔哩哔哩直播)

### Live Partition

See [#哔哩哔哩直播直播](/live.html#哔哩哔哩直播)

### Master station topic list

<Route author="Qixingchen" example="/bilibili/blackboard" path="/bilibili/blackboard" />

### Member buys new products

<Route author="DIYgod" example="/bilibili/mall/new" path="/bilibili/mall/new" />

### Member purchase works

<Route author="DIYgod" example="/bilibili/mall/ip/1_5883" path="/bilibili/mall/ip/:id" :paramsDesc="['Work id, which can be found in the work listing page URL' ]"/>

### Leaderboard

<Route author="DIYgod" example="/bilibili/ranking/0/3/1" path="/bilibili/ranking/:tid/:days?/:arc_type?" :paramsDesc="['Leader partition id , default 0', 'time span, can be 1 3 7 30', 'submission time, can be 0 (all submissions) 1 (recent submission), default 1']">

| All Stations | Animation | Guochuang Related | Music | Dance | Games | Technology | Life | Ghosts | Fashion | Entertainment |
| ---- | ---- | -------- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
0 | 1 | 168 | 3 | 129 | 4 | 36 | 160 | 119 | 155 | 5 | 181 |

</Route>

### Topic (channel/label)

<Route author="Qixingchen" example="/bilibili/topic/2233" path="/bilibili/topic/2233" :paramsDesc="['Topic name (also known as channel name or label) such as 2233 or COSPLAY']" />

### song list

<Route author="LogicJake" example="/bilibili/audio/10624" path="/bilibili/audio/10624" :paramsDesc="['The song list id can be found in the song page URL']"/>

## Dcard

### Home Post

<Route author="DIYgod" example="/dcard/posts/popular" path="/dcard/posts/:type?" :paramsDesc="['sort, popular popular; latest latest, default is latest']"/ >

### Plate Posts

<Route author="HenryQW" example="/dcard/funny/popular" path="/dcard/:section/:type?" :paramsDesc="['block name, get in URL', 'sort, popular hot'; Latest latest, default is latest']"/>

## Disqus

### Comments

<Route author="DIYgod" example="/disqus/posts/diygod-me" path="/disqus/posts/:forum" :paramsDesc="['The website's disqus name']"/>

## Dribbble

### Popular

<Route author="DIYgod" example="/dribbble/popular/week" path="/dribbble/popular/:timeframe?" :paramsDesc="['Time dimension, support week month year ever']"/>

### User (team

<Route author="DIYgod" example="/dribbble/user/google" path="/dribbble/user/:name" :paramsDesc="['username, found in the user's homepage URL']"/>

### Key words

<Route author="DIYgod" example="/dribbble/keyword/player" path="/dribbble/keyword/:keyword" :paramsDesc="['Keywords to subscribe to']"/>

## Facebook

### Fan page

<Route author="maple3142" example="/facebook/page/SonetPCR" path="/facebook/page/:id" :paramsDesc="['page id']" anticrawler="1"/>

## Instagram

### 用户

<Route author="DIYgod" example="/instagram/user/diygod" path="/instagram/user/:id" :paramsDesc="['userid']" anticrawler="1"/>

### 标签

<Route author="widyakumara" path="/instagram/tag/:tag" example="/instagram/tag/urbantoys" :paramsDesc="['tagname']" anticrawler="1"/>

## Matters

### Latest Sorting

<Route author="xyqfer Cerebrater" example="/matters/latest" path="/matters/latest" />

### popular articles

<Route author="Cerebrater" example="/matters/hot" path="/matters/hot" />

### 标签

<Route author="Cerebrater" example="/matters/tags/VGFnOjk3Mg" path="/matters/tags/:tid" :paramsDesc="['tag id, found at the URL where the tag is located]]]/>

### Author

<Route author="Cerebrater" example="/matters/author/az" path="/matters/author/:uid" :paramsDesc="['Author id, found at the author's homepage URL']"/>

## NGA

### Partition Posts

<Route author="xyqfer" example="/nga/forum/485" path="/nga/forum/:fid" :paramsDesc="['Partition id, found in the partition home page URL']"/>

### Posts

<Route author="xyqfer" example="/nga/post/15939161" path="/nga/post/:tid" :paramsDesc="['post id, can be found at the post URL']"/>

## pixiv

### User Collection

<Route author="EYHN" example="/pixiv/user/bookmarks/15288095" path="/pixiv/user/bookmarks/:id" :paramsDesc="['userid, can be found in the user's homepage URL'] " radar="1"/>

### User Dynamics

<Route author="DIYgod" example="/pixiv/user/11" path="/pixiv/user/:id" :paramsDesc="['userid, can be found in the user's homepage URL']" radar=" 1"/>

### Leaderboard

<Route author="EYHN" example="/pixiv/ranking/week" path="/pixiv/ranking/:mode/:date?" :paramsDesc="['sitboard type', 'date, value as `2018-4-25`']" radar="1">

Pixiv Daily Ranking | pixiv Weekly Ranking | pixiv Monthly Ranking | pixiv Popular Ranking by Men | pixiv Popular Ranking by Female | pixiv Original Works Ranking | pixiv Newcomer Ranking |
| ------------ | ------------ | ------------ | ---------- ---------- | -------------------- | ------------------ | -------------- |
| day | week | month | day_male | day_female | week_original | week_rookie |

Pixiv R-18 日排行| pixiv R-18 Popular with men|pixiv R-18 Popular female rankings | pixiv R-18 Week ranking| pixiv R-18G Ranking |
| ----------------- | ------------------------- | ----- -------------------- | ----------------- | ----------- ----- |
Day_r18 | day_male_r18 | day_female_r18 | week_r18 | week_r18g |

</Route>

### Key words

<Route author="DIYgod" example="/pixiv/search/麻衣/popular" path="/pixiv/search/:keyword/:order?" :paramsDesc="['keyword', 'sort by, popular Popularity sort, empty or any other value sorted by time ']" radar="1"/>

## Saraba1st

### Posts

<Route author="zengxs" example="/saraba1st/thread/1789863" path="/saraba1st/thread/:tid" :paramsDesc="['post id']">

If the post URL is <https://bbs.saraba1st.com/2b/thread-1789863-1-1.html> then the post id is `1789863`.

</Route>

## Telegram

### Channel

<Route author="DIYgod" example="/telegram/channel/awesomeDIYgod" path="/telegram/channel/:username" :paramsDesc="['channel username']"/>

### Sticker pack

<Route author="DIYgod" example="/telegram/stickerpack/DIYgod" path="/telegram/stickerpack/:name" :paramsDesc="['sticker pack id, can be found in the URL obtained by sharing the sticker']" />

## Twitter

### User timeline

<Route author="DIYgod" example="/twitter/user/DIYgod" path="/twitter/user/:id" :paramsDesc="['user twitter name']" radar="1"/>

### User attention timeline

<Route author="DIYgod" example="/twitter/followings/DIYgod" path="/twitter/followings/:id" :paramsDesc="['user twitter name']" radar="1">

::: warning Note

The user pays attention to the timeline and needs to correspond to the user's Twitter token, so it can only be built by itself. For details, see the configuration module of the deployment page.

:::

</Route>

### List timeline

<Route author="xyqfer" example="/twitter/list/ladyleet/javascript" path="/twitter/list/:id/:name" :paramsDesc="['user twitter name', 'list name']" Radar="1"/>

### User like list

<Route author="xyqfer" example="/twitter/likes/DIYgod" path="/twitter/likes/:id" :paramsDesc="['user twitter name']" radar="1"/>

## VueVlog

### 用户

<Route author="kt286" example="/vuevideo/971924215514" path="/vuevideo/:userid" :paramsDesc="['User ID, can be found in the URL of the corresponding page']"/>

## Youtube

### 用户

<Route author="DIYgod" example="/youtube/user/JFlaMusic/" path="/youtube/user/:username/:embed?" :paramsDesc="['username', 'default is to enable inline video , any value is off ']" radar="1"/>

### Channel

<Route author="DIYgod" example="/youtube/channel/UCDwDMPOZfxVV0x_dz0eQ8KQ" path="/youtube/channel/:id/:embed?" :paramsDesc="['Channel id', 'Default is to enable inline video, Any value is off ']" radar="1"/>

### playlist

<Route author="HenryQW" example="/youtube/playlist/PLqQ1RwlxOgeLTJ1f3fNMSwhjVgaWKo_9Z" path="/youtube/playlist/:id/:embed?" :paramsDesc="['playlist id', 'default is to enable inline video , any value is off ']" radar="1"/>

##币

### User Dynamics

<Route author="LogicJake" example="/bihu/activaties/1478342200" path="/bihu/activaties/:id" :paramsDesc="['userid']"/>

## just sing

### 用户

<Route author="kt286" example="/changba/34108440" path="/changba/:userid" :paramsDesc="['User ID, can be found in the URL of the corresponding page']" supportPodcast="1"/ >

## 豆瓣

### The movie being released

<Route author="DIYgod" example="/douban/movie/playing" path="/douban/movie/playing"/>

### High score movie being released

<Route author="DIYgod" example="/douban/movie/playing/7.5" path="/douban/movie/playing/:score" :paramsDesc="['returns a movie greater than or equal to this score']"/>

### The upcoming movie

<Route author="DIYgod" example="/douban/movie/later" path="/douban/movie/later"/>

### North American Box Office

<Route author="DIYgod" example="/douban/movie/ustop" path="/douban/movie/ustop"/>

### Douban Group

<Route author="DIYgod" example="/douban/group/camera" path="/douban/group/:groupid" :paramsDesc="['Douban group id']"/>

### Browse and discover

<Route author="clarkzsd" example="/douban/explore" path="/douban/explore"/>

### Browse to find sub-sections

<Route author="LogicJake" example="/douban/explore/column/2" path="/douban/explore_column/:id" :paramsDesc="['column id']"/>

### 新书快递

<Route author="fengkx" example="/douban/book/latest" path="douban/book/latest"/>

### The latest added music

<Route author="fengkx xyqfer" example="/douban/music/latest/chinese" path="/douban/music/latest/:area?" :paramsDesc="['region type, default all']">

| Chinese | Europe and America | Japan and South Korea |
| ------- | ------- | ----------- |
| chinese | western | japankorean |

</Route>

### Popular city activities

<Route author="xyqfer" example="/douban/event/hot/118172" path="/douban/event/hot/:locationId" :paramsDesc="['location id, [city homepage] (https:// Www.douban.com/location) Open the console and execute `window.__loc_id__` get ']"/>

### Commercial Press New Book Courier

<Route author="xyqfer" example="/douban/commercialpress/latest" path="/douban/commercialpress/latest"/>

### Douban Bookstore

<Route author="xyqfer" example="/douban/bookstore" path="/douban/bookstore"/>

### Top Book Ranking

<Route author="xyqfer" example="/douban/book/rank/fiction" path="/douban/book/rank/:type" :paramsDesc="['Book Type']">

| Fiction | Non-fiction |
| ------- | ---------- |
| fiction | nonfiction |

</Route>

### 豆列

<Route author="LogicJake" example="/douban/doulist/37716774" path="douban/doulist/:id" :paramsDesc="['Bean column id']"/>

### User Broadcast

<Route author="alfredcai" example="/douban/people/62759792/status" path="douban/people/:userid/status" :paramsDesc="['integer user id']">

::: tip prompt

- ** Currently only supports integer id**
- The id of the letter type, you can find its integer id through the avatar image link, the picture naming rule `ul[userid]-*.jpg`
- For example: User id: `MovieL` his avatar image link: `https://img1.doubanio.com/icon/ul1128221-98.jpg` His integer id: `1128221`

:::

</Route>

### Topics

<Route author="LogicJake" example="/douban/topic/48823" path="/douban/topic/:id/:sort?" :paramsDesc="['topic id', 'sort method, hot or new, The default is new']"/>

## 摇音

### User Dynamics

<Route author="DIYgod" example="/douyin/user/93610979153" path="/douyin/user/:id" :paramsDesc="['userid, can be found in the user's homepage URL obtained by sharing'] "/>

### Favorite video

<Route author="xyqfer" example="/douyin/like/93610979153" path="/douyin/like/:id" :paramsDesc="['userid, can be found in the user's homepage URL obtained by sharing'] "/>

##方格子

### Publishing topic

<Route author="Maecenas" example="/vocus/publication/bass" path="/vocus/publication/:id" :paramsDesc="['Publishing topic id, can be found at the URL of the publication topic homepage]]/ >

### User personal article

<Route author="LogicJake" example="/vocus/user/tsetyan" path="/vocus/user/:id" :paramsDesc="['userid, can be found at the URL of the user's homepage']"/>

## it's wired

### Home

<Route author="HenryQW" example="/qdaily/notch/posts" path="/qdaily/notch/posts" />

### Explore

<Route author="HenryQW" example="/qdaily/notch/explore/1" path="/qdaily/explore/:id" :paramsDesc="['Explore id, you can find it by a strange app copy share link'] "/>

## Curiosity Daily

### Tags, columns, classification

<Route author="WenhuWee emdoe SivaGao HenryQW" example="/qdaily/column/59" path="/qdaily/:type/:id" :paramsDesc="['type, see table below, 'corresponding id, can Find ']"> at the URL

| Tags | Columns | Categories |
| ---- | ------ | ---------- |
| tag | column | researcach |

</Route>

##虎扑

###虎扑BBS Forum

<Route author="LogicJake" example="/hupu/bbs/bxj/2" path="/hupu/bbs/:id/:order?" :paramsDesc="['tile id, found in the section URL', 'Sort by, 1 latest reply (default), 2 latest posts, 3 essence posts ']"/>

## 即刻

### Circles - Featured

<Route author="DIYgod" example="/jike/topic/54dffb40e4b0f57466e675f0" path="/jike/topic/:id" :paramsDesc="['circle id, a circle that can be shared at the instant web page or app Find ']" anticrawler="1"/> in the page URL

::: tip prompt

Some circles like what wakes up: 553870e8e4b0cafb0a1bef68` provides plain text content, <a href="#/jike/topic/text/:id">circles-plain text/jike/topic/text/:id</ a> may provide a better experience.

:::

### Circle - Square

<Route author="DIYgod" example="/jike/topic/square/54dffb40e4b0f57466e675f0" path="/jike/topic/square/:id" :paramsDesc="['circle id, available in the web side circle page or app Find ']" anticrawler="1"/> in the shared circle page URL

### Circles - plain text

<Route author="HenryQW" example="/jike/topic/text/553870e8e4b0cafb0a1bef68" path="/jike/topic/text/:id" :paramsDesc="['circle id, available in the web side circle page or app Find ']" anticrawler="1"/> in the shared circle page URL

### User Dynamics

<Route author="DIYgod" example="/jike/user/82D23B32-CF36-4C59-AD6F-D05E3552CBF3" path="/jike/user/:id" :paramsDesc="['userid, available on the web side ']" anticrawler="1"/> found in the user page URL

### Instant tabloid

<Route author="Andiedie" example="/jike/daily" path="/jike/daily" anticrawler="1"/>

##简书

### Home

<Route author="DIYgod HenryQW" example="/jianshu/home" path="/jianshu/home"/>

### Hot

<Route author="DIYgod HenryQW" example="/jianshu/trending/weekly" path="/jianshu/trending/:timeframe" :paramsDesc="['by week`weekly` or by month`monthly`'""/ >

### Special Topics

<Route author="DIYgod HenryQW" example="/jianshu/collection/xYuZYD" path="/jianshu/collection/:id" :paramsDesc="['The topic id, can be found in the feature page URL']"/>

### Author

<Route author="DIYgod HenryQW" example="/jianshu/user/yZq3ZV" path="/jianshu/user/:id" :paramsDesc="['author id, can be found in the author's homepage URL']"/>

##龙空

### Partition

<Route author="ma6254" example="/lkong/forum/60" path="/lkong/forum/:id?" :paramsDesc="['Partition id, can be found in the URL of the partition ']"/>

### Posts

<Route author="ma6254" example="/lkong/thread/2356933" path="/lkong/thread/:id?" :paramsDesc="['post id, can be found in the URL of the post']"/>

##龙腾网

### Translation Network Stickers

<Route author="sgqy" example="/ltaaa" path="/ltaaa/:type?" :paramsDesc="['hot type.']">

| Latest | Weekly | Monthly | Full Year |
| ---- | ---- | ----- | ---- |
| (empty) | week | month | year |

</Route>

## 美拍

### User Dynamics

<Route author="ihewro" example="/meipai/user/56537299" path="/meipai/user/:id" :paramsDesc="['userid, can be found in the user's homepage URL obtained by sharing'] "/>

##贴吧吧

### Post list

<Route author="u3u" example="/tieba/forum/female map" path="/tieba/forum/:kw" :paramsDesc="['吧名']"/>

### Boutique Posts

<Route author="u3u" example="/tieba/forum/good/female map" path="/tieba/forum/good/:kw/:cid?" :paramsDesc="['吧名', '精品分类If you do not pass `cid` then get all the categories ']"/>

### Post dynamic

<Route author="u3u" example="/tieba/post/5853240586" path="/tieba/post/:id" :paramsDesc="['postID']"/>

### 楼主动态

<Route author="u3u" example="/tieba/post/lz/5853240586" path="/tieba/post/lz/:id" :paramsDesc="['postID']"/>

##微博

### 博主

<Route author="DIYgod iplusx" example="/weibo/user/1195230310" path="/weibo/user/:uid/:displayVideo?" :paramsDesc="['userid, blogger homepage opens console execution` $CONFIG.oid` Get ', ' Whether to directly display the Weibo video, the default `0` is not displayed, if necessary, fill in `1` ']" anticrawler="1" radar="1"/>

### Key words

<Route author="DIYgod" example="/weibo/keyword/DIYgod" path="/weibo/keyword/:keyword" :paramsDesc="['You want to subscribe to the microblogging keyword']" anticrawler="1" />

### 热搜榜

<Route author="xyqfer" example="/weibo/search/hot" path="/weibo/search/hot" anticrawler="1"/>

###超话

<Route author="zengxs" example="/weibo/super_index/1008084989d223732bf6f02f75ea30efad58a9" path="/weibo/super_index/:id" :paramsDesc="['超话ID']" anticrawler="1"/>

## WeChat

::: tip prompt

The public number directly grasps the difficulties, so currently provide both indirect and gas indirect capture programs, please choose

:::

### Public Number (immediate source)

<Route author="DIYgod" example="/jike/topic/584b8ac671a288001154a115" path="/jike/topic/:id" :paramsDesc="['Reference [immediate-circle-selection](#/jike/topic/ :id)']" anticrawler="1"/>

### Public Number ( wemp.app source)

<Route author="HenryQW" example="/wechat/wemp/36836fbe-bdec-4758-8967-7cc82722952d" path="/wechat/wemp/:id" :paramsDesc="['wemp public number id, available in search The engine uses `site:wemp.app` to search for the public number (for example: People's Daily site:wemp.app), open the public number page, find id']"/> in the URL

### Public Number (Portal Source)

<Route author="HenryQW" example="/wechat/csm/huxiu_com" path="/wechat/csm/:id" :paramsDesc="['public number id, open public page, find id' in URL] "/>

### Public Number (Telegram Channel Source)

<Route author="LogicJake" example="/wechat/tgchannel/lifeweek" path="/wechat/tgchannel/:id" :paramsDesc="['public number binding channel id']">

::: warning Note

This method requires channel binding via efb. For details, see [https://github.com/DIYgod/RSSHub/issues/2172] (https://github.com/DIYgod/RSSHub/issues/2172)
:::
</Route>

### Public Number (Excellent Source)

<Route author="kt286" example="/wechat/uread/shensing" path="/wechat/uread/:userid" :paramsDesc="['The public signal's micro-signal, available on WeChat - public number - more information Found in. Not all of them are supported, can you use the following ']"/>

### Public Number (20 power source)

<Route author="sanmmm" example="/wechat/ershicimi/59" path="/wechat/ershicimi/:id" :paramsDesc="['public number id, open public page, find id' in URL] "/>

### Public Platform System Bulletin

<Route author="xyqfer" example="/wechat/announce" path="/wechat/announce" />

### Small program plugin

<Route author="xyqfer" example="/wechat/miniprogram/plugins" path="/wechat/miniprogram/plugins" />

##雪球

### User Dynamics

<Route author="imlonghao" example="/xueqiu/user/8152922548" path="/xueqiu/user/:id/:type?" :paramsDesc="['userid, can be found in the user's homepage URL', 'Dynamic type, leave all defaults by default']">

| Original Release | Long Text | Q&A | Hot |
| ------ | ---- | ---- | ---- | ---- |
| 0 | 2 | 4 | 9 | 11 |

</Route>

### User Collection News

<Route author="imlonghao" example="/xueqiu/favorite/8152922548" path="/xueqiu/favorite/:id" :paramsDesc="['userid, can be found in the user's homepage URL']"/>

### User-selected dynamics

<Route author="hillerliao" example="/xueqiu/user_stock/1247347556" path="/xueqiu/user_stock/:id" :paramsDesc="['userid, found in the user's homepage URL']"/>

### Fund Net Value Update

<Route author="HenryQW" example="/xueqiu/fund/040008" path="/xueqiu/fund/:id" :paramsDesc="['The fund code can be found in the fund home page URL. The data for this route is Off-exchange fund (starting with `F`)']"/>

### Combine the latest position information

<Route author="ZhishanZhang" example="/xueqiu/p/ZH1288184" path="/xueqiu/snb/:id" :paramsDesc="['Combined code, can be found in the combined homepage URL.']"/>

### Stock Information

<Route author="YuYang" example="/xueqiu/stock_info/SZ000002" path="/xueqiu/stock_info/:id/:type?" :paramsDesc="['Stock code (need to bring the exchange)', ' Dynamic type, without filling in the stock announcement ']">

| Announcement | News | Research Report |
| ------------ | ---- | -------- |
| announcement | news | research |

</Route>

## 一亩三分地

### Theme posts

<Route author="Maecenas" example="/1point3acres/user/1/threads" path="/1point3acres/user/:id/threads" :paramsDesc="['userid, the homepage URL available on the Instant version of the site Find ']"/>

### Reply

<Route author="Maecenas" example="/1point3acres/user/1/posts" path="/1point3acres/user/:id/posts" :paramsDesc="['userid, the homepage URL available on the Instant version of the site Find ']"/>

## Live broadcast

### 子论坛

<Route author="LogicJake" example="/zhibo8/forum/8" path="/zhibo8/forum/:id" :paramsDesc="['Sub-session id, found in the sub-forum URL']"/>

### Reply

<Route author="LogicJake" example="/zhibo8/post/2601615" path="/zhibo8/post/:id" :paramsDesc="['post id, can be found at the post URL']"/>

## Know almost

### Favorites

<Route author="huruji" example="/zhihu/collection/26444956" path="/zhihu/collection/:id" :paramsDesc="['Favorite id, can be found in the Favorites page URL']" anticrawler ="1" radar="1"/>

### User Dynamics

<Route author="DIYgod" example="/zhihu/people/activities/diygod" path="/zhihu/people/activities/:id" :paramsDesc="['author id, found in the user's homepage URL'] " anticrawler="1" radar="1"/>

### User response

<Route author="DIYgod" example="/zhihu/people/answers/diygod" path="/zhihu/people/answers/:id" :paramsDesc="['author id, found in the user's homepage URL'] " anticrawler="1" radar="1"/>

### column

<Route author="DIYgod" example="/zhihu/zhuanlan/googledevelopers" path="/zhihu/zhuanlan/:id" :paramsDesc="['column id, can be found in the column homepage URL]] anticrawler=" 1" radar="1"/>

### 知乎日报

<Route author="DHPO" example="/zhihu/daily" path="/zhihu/daily" anticrawler="1" radar="1"/>

### Know the hot list

<Route author="DIYgod" example="/zhihu/hotlist" path="/zhihu/hotlist" anticrawler="1" radar="1"/>

### Know the idea hot list

<Route author="xyqfer" example="/zhihu/pin/hotlist" path="/zhihu/pin/hotlist" anticrawler="1" radar="1"/>

### question

<Route author="xyqfer" example="/zhihu/question/59895982" path="/zhihu/question/:questionId" :paramsDesc="['issue id']" anticrawler="1" radar="1"/ >

### Topics

<Route author="xyqfer" example="/zhihu/topic/19828946" path="/zhihu/topic/:topicId" :paramsDesc="['topicid']" anticrawler="1" radar="1"/ >

### User Ideas

<Route author="xyqfer" example="/zhihu/people/pins/kan-dan-45" path="/zhihu/people/pins/:id" :paramsDesc="['author id, available at the user's homepage URL Found ']" anticrawler="1" radar="1"/>

###知书书店-New book

<Route author="xyqfer" example="/zhihu/bookstore/newest" path="/zhihu/bookstore/newest" anticrawler="1" radar="1"/>

### Knowing the idea - 24 hours news summary

<Route author="xyqfer" example="/zhihu/pin/daily" path="/zhihu/pin/daily" anticrawler="1" radar="1"/>

###知知书店-知乎周刊

<Route author="LogicJake" example="/zhihu/weekly" path="/zhihu/weekly" anticrawler="1" radar="1"/>
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjAyOTcwMjYxOF19
-->