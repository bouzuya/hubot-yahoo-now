# hubot-yahoo-now

A Hubot script that display the latest news in yahoo news feed.

## Installation

    $ npm install git://github.com/bouzuya/hubot-yahoo-now.git

or

    $ # TAG is the package version you need.
    $ npm install 'git://github.com/bouzuya/hubot-yahoo-now.git#TAG'

## Example

    bouzuya> hubot help yahoo-now
      hubot> hubot yahoo-now - display the latest news in yahoo news feed.

    bouzuya> hubot yahoo-now
      hubot> 2014-08-23T21:22:24+09:00 : 大気不安定 24日も大雨に警戒 : http://dailynews.yahoo.co.jp/fc/domestic/weather/?id=6128073
             2014-08-23T19:42:16+09:00 : 3人に2人「生活に不安」 : http://dailynews.yahoo.co.jp/fc/domestic/consumption_tax/?id=6128141
             2014-08-23T13:16:15+09:00 : オスプレイ整備 木更津に誘致 : http://dailynews.yahoo.co.jp/fc/domestic/osprey/?id=6128055
             2014-08-23T20:09:11+09:00 : 氷水 次を指名しなかった理由 : http://dailynews.yahoo.co.jp/fc/computer/internet/?id=6128209
             2014-08-23T03:06:09+09:00 : 「吉田調書」を公開へ 政府 : http://dailynews.yahoo.co.jp/fc/domestic/fukushima_nuclear_plant/?id=6128117
             2014-08-23T03:35:23+09:00 : 石破氏 安保相を辞退する意向 : http://dailynews.yahoo.co.jp/fc/domestic/formation_of_a_cabinet/?id=6128118
             2014-08-23T09:59:24+09:00 : 廃家電の不正輸出 異例の捜索 : http://dailynews.yahoo.co.jp/fc/domestic/improper_export/?id=6128046
             2014-08-23T10:01:36+09:00 : 少子化 代ゼミが20拠点閉鎖へ : http://dailynews.yahoo.co.jp/fc/domestic/decrease_of_children/?id=6128190

## Configuration

See [`src/scripts/yahoo-now.coffee`](src/scripts/yahoo-now.coffee).

## Development

### Run test

    $ npm test

### Run robot

    $ npm run robot

## License

[MIT](LICENSE)

## Author

[bouzuya][user] &lt;[m@bouzuya.net][mail]&gt; ([http://bouzuya.net][url])

## Badges

[![Build Status][travis-badge]][travis]
[![Dependencies status][david-dm-badge]][david-dm]

[travis]: https://travis-ci.org/bouzuya/hubot-yahoo-now
[travis-badge]: https://travis-ci.org/bouzuya/hubot-yahoo-now.svg?branch=master
[david-dm]: https://david-dm.org/bouzuya/hubot-yahoo-now
[david-dm-badge]: https://david-dm.org/bouzuya/hubot-yahoo-now.png
[user]: https://github.com/bouzuya
[mail]: mailto:m@bouzuya.net
[url]: http://bouzuya.net
