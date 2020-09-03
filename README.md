你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# Go Flipper

Go Flipper is a port of [Flipper](https://github.com/jnunemaker/flipper) to Go.

It's designed to be compatible at the storage level with the Ruby gem, so you can toggle features using any of them and access them with the other.

This project is in an early stage and doesn't include all the features that the Ruby gem includes at the moment.

Caveats:

- This implementation assumes that all actors have a FlipperID method that returns a string. It doesn't work with other id types at the moment.

## Installation

```
go get github.com/calavera/go-flipper
```

## Usage

See the Godoc for examples and API information:

https://godoc.org/github.com/calavera/go-flipper

## License

[MIT](LICENSE)
