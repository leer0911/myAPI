# 园丁日志 

::: tip

获取园丁日志

> `GET` /trees/record

:::

## Request

### 请求头

| 参数名        | 类型   | 是否必填 | 备注       | 示例             |
| ------------- | ------ | -------- | ---------- | ---------------- |
| Authorization | string | 是       | 请求授权头 | dfsdfasdfsdfasdf |

## Response

```json
{
  "message": "",
  "data": [
    {
      "type": 1,
      "content": "您的柚子树长大成树啦~ 在多给我点营养，我就要结果啦~。",
      "created_at": "2018-12-27 15:02:31"
    },
    {
      "type": 2,
      "content": "您的柚子树长成树苗啦~ 在多给我点营养，我就变成参天大树。",
      "created_at": "2018-12-27 14:54:00"
    }
  ],
  "code": 0
}
```