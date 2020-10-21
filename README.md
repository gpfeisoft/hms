# hms
预定义HTTP请求Method和返回状态码


##使用方法：

```
class RequestClass implements RequestMethodInterface`
{
    public function index()
    {
        return self::METHOD_GET;
    }
}
```

```
class ResponseClass implements ResponseCodeInterface`
{
    public function index()
    {
        return self::STATUS_OK;
    }
}
```

