# Rails Helpers


## Log to a File

```ruby
  @my_logger ||= Logger.new("storage/logs/rails.log")
  @my_logger.debug "params: #{params.inspect}"
```
