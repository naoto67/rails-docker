# rails-docker

## how to install
```
  git clone https://github.com/naoto67/rails-docker.git #{workdir}
  cd #{workdir}
  docker-compose build
  docker-compose up
```

## rubocop
```
  docker-compose run app bundle exec rubocop
```

## using pry.
```
  docker-compose run --service-ports web
```
