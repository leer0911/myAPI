# 领取果树奖品

::: tip

领取奖品接口

> `POST` /trees/prize

:::

## Request

### 请求头

| 参数名        | 类型   | 是否必填 | 备注       | 示例             |
| ------------- | ------ | -------- | ---------- | ---------------- |
| Authorization | string | 是       | 请求授权头 | dfsdfasdfsdfasdf |

### body

| 参数名     | 类型   | 是否必填 | 备注 | 示例 |
| ---------- | ------ | -------- | ---- | ---- |
| gift_id    | number | 是       | 无   | 无   |
| address_id | number | 是       | 无   | 无   |

## Response

```json
{
  "code": 3523,
  "data": "value",
  "message": "value"
}
```