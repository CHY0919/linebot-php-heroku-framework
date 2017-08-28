# linebot-php-heroku-framework

a tiny PHP framework to deploy your linebot on heroku

just comebine the [heroku/php-getting-started](https://github.com/heroku/php-getting-started) and [linebot-php-sdk](https://github.com/line/line-bot-sdk-php)

## Getting Started

1.Register linebot service [lineservice](https://business.line.me/services/bot).

2.Turn on the [bot service](https://admin-official.line.me/) .

3.Enable Webhook sending and disable auto-sending setting.

4.Remember your ChannelSecret and issued ChannelAccessToken as parameters.

5.Deploy your linebot with the under button.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

6.Fill Webhook URL in developers page with 	https://[your app name].herokuapp.com:443/callback

7.Done.

See detail with picture at [my web](http://www.chy.tw/2017/08/phpherokulinebot.html).

## License

the original code owned by LINE Corporation


```
Copyright 2016 LINE Corporation

LINE Corporation licenses this file to you under the Apache License,
version 2.0 (the "License"); you may not use this file except in compliance
with the License. You may obtain a copy of the License at:

  https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations
under the License.
```


