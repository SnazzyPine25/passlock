# passlock
A gem that makes ideal passwords in various ways.
## Dependencies
  * (ruby-hmac)[https://github.com/topfunky/ruby-hmac]
## Examples
Installing PassLock is very easy!
```ruby
gem install passlock
```
PassLock provides many encryptions...
```ruby
require 'passlock'
PassLock.base64 'hello'
PassLock.base64hash 'world!'
PassLock.sha1 'how'
PassLock.sha256 'do'
PassLock.sha384 'you'
PassLock.sha512 'do?'
```
PassLock also makes modules into String...
```
'liven'.to_sha1
'up'.to_sha256
'some!'.to_basehash
```
