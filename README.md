# README

Test project to test [sidekiq alive](https://github.com/arturictus/sidekiq_alive) 

sidekiq signals:
https://github.com/mperham/sidekiq/wiki/Signals

## Testing sidekiq alive

__Run sidekiq instaces:__

```
bin/init 1
```
```
bin/init 2
```
```
bin/init 3
```

__Test liveness:__

```
curl localhost:7431
curl localhost:7432
curl localhost:7433
```

__Review sidekiq UI:__

```
bundle exec rails s
```

go to localhost:3000/sidekiq
