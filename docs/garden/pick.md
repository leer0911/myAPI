# 采摘果实

::: tip

采摘果实

> `POST` /trees/pick

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
      "image": "",
      "gift_name": "一车柚子",
      "gift_id": 2
    },
    {
      "image": "",
      "gift_name": "柚子一车",
      "gift_id": 1
    }
  ],
  "code": 0
}
```