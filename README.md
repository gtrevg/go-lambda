## go-lambda

![go-lambda](http://cl.ly/3V331k34160Z/go-lamda-small.png)

### Example

```
$ go-lambda list
$ go-lambda create --role arn:aws:iam::account-id:role/lambda_basic_execution handler github.com/xlab/go-lambda/example

... make changes ...

$ go-lambda update example-handler handler github.com/xlab/go-lambda/example
$ go-lambda list
```

### License

MIT
