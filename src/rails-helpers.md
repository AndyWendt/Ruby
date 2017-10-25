# Rails Helpers


## Log to a File

```ruby
    @my_logger ||= Logger.new("#{Rails.root}/log/my.log")
    @my_logger.debug "params: #{params.inspect}"
```
