#Increase your application's performance by reducing the number of queries it makes

The Bullet gem is designed to help you increase your application's performance by reducing the number of queries it makes. It will watch your queries while you develop your application and notify you when you should add eager loading (N+1 queries), when you're using eager loading that isn't necessary and when you should use counter cache.

```ruby
gem "bullet", :group => "development"

```