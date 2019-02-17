# rails-docker

## how to install
```
  git clone https://github.com/naoto67/rails-docker.git #{workdir}
  cd #{workdir}
  docker-compose build
  docker-compose up
```

# How to use the rubocop
```
  docker-compose run app bundle exec rubocop
```

## How to use the pry byebug
```
  docker-compose run --service-ports app
```
