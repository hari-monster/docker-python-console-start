# docker-python-console-start

docker-compose.yml　配下に移動する

'cd docker-python-console-start'

コンテナを立ち上げる


'docker-compose up -d'

コンテナに入る

'docker-compose exec app bash'

workdirがsrc/　配下に設定されている為pythonを実行できる

'python test.py'

使い終わったら

'docker-compose down'
