#設定方法

```
$ cd ~/projects
$ git clone https://github.com/mkoma414/master_pictweet.git
$ cd master_pictweet
$ bundle install
$ bundle exec rake db:create
$ bundle exec rake db:migrate
$ bundle exec rake db:seed
```
#問題
##エラーを解決し、以下の状態にしてください
・ビューの表示がされること
・ログインができること
　　アカウントは下記を使用する
　　　　　　email: karimen@karimen.com
　　　　　　password: 12345678
・ログアウトができること
・ツイートの新規投稿画面が表示できること
