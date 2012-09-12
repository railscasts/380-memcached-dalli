# RailsCasts Episode #380: Memcached & Dalli

http://railscasts.com/episodes/380-memcached-dalli

Requires Ruby 1.9.2 or higher.


### Commands used in this episode

```
memcached -h | head -1
brew install memcached
/usr/local/bin/memcached
ssh deployer@198.58.98.181
sudo apt-get install memcached
vim /etc/memcached.conf
```


### Commands used in this console

```
Rails.cache
Rails.cache.write(:foo, 1)
Rails.cache.read(:foo)
Rails.cache.fetch(:bar) { sleep 1; 2 }
Rails.cache.multi_read(:foo, :bar)
Rails.cache.stats
y _
Rails.cache.write(:foo, 1, expires_in: 5.seconds)
```
