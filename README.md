# 概要
lumenのチュートリアルです。

# 手順

+ composerのインストール
```
curl -s http://getcomposer.org/installer | php
mv composer.phar /usr/local/bin/composer
composer -v
```

+ lumenのインストール
```
composer global require "laravel/lumen-installer=~1.0"
exec $SHELL -l
lumen -v
```

```
lumen new service
```