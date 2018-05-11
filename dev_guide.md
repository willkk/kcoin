KCoin Project
========

# Contribute
Pull request is welcome and appreciated. Quick steps to setup dev environment:

- Clone source code: `git clone https://github.com/kaiyuanshe/kcoin.git`
- Initialize project:
```
cd kcoin
bundle install
cp lib/config-sample.rb lib/config.rb
```
- Open config file `lib/config.rb` and update config values like github oauth secret.
- Start the server: `puma config.ru`
- browse [http://127.0.0.1:9292/](http://127.0.0.1:9292/)

# Documentation

KCoin is built on several popular ruby frameworks:
- [Sinatra](http://sinatrarb.com/documentation.html): web framework on top of rack.
- [Sqlite](https://www.sqlite.org/docs.html): database
- [sequel](https://sequel.jeremyevans.net/documentation.html): database toolkit for ruby
- [Haml](http://haml.info/docs/yardoc/): Html template engine ofr presentation layer
- [metroui](https://metroui.org.ua/intro.html): CSS library to build Metro-style UI.

# Author
[Kaiyuanshe](http://www.kaiyuanshe.cn)

# License

# Copyright
Copyright (c) Kaiyuanshe