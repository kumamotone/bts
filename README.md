こまどりおねえちゃんしすてむ（鉄）
----

「こまどりおねえちゃんしすてむ（鉄）」はTOJO K-ONのセッティング表を作るシステムだよっ☆

# Usage

```bash
git clone git@github.com:nownabe/bts.git
cd bts
bundle install --path vendor/bundle
bundle exec ruby bts.rb
```

Open `http://localhost:3000/`.

# Docker usage

```bash
docker pull nownabe/bts:latest
docker run --name="bts" -d -p 80:80 -v /var/pdf:/usr/src/app/public/pdf nownabe/bts
```

