# 种植果树 

::: tip

返回种植后植物状态

> `POST` /trees/plant

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
    "need_watering": "3",
    "created_at": "2018-12-27 01:35:11",
    "updated_at": "2018-12-27 01:35:11",
    "had_watered": 0,
    "status": 1, // 果树状态:1:种子 2:树苗 3:树木 4:开花 5:结果 6:成熟 7:已采摘
    "user_id": 000000,
    "id": 4
  },
  "code": 0
}
```