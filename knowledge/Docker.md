Dockerfileを元にDockerイメージが作られる
Dockerfileを更新したら、イメージを再構築しないと行けない
docker compose build

ビルドしたらすでにあるコンテナはどうなるの？

docker-compose.ymlファイルではインデントやスペースも大事
それが間違っているとエラーになったりする
validating /Users/kosukeyoshida/crh/beee_backend_api/docker-compose.yml: networks.name must be a mapping or null