# 签到

::: tip

签到

> `POST` /trees/sign

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
  "data": {
    "signCount": "2", // 累积签到天数
    "had_signed": true // 今天是否已签到
  },
  "code": 0
}
```