# 果树浇水 

::: tip

返回浇水后的果树状态

> `POST` /trees/watering 

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
    "created_at": "2018-12-26 07:40:27",
    "updated_at": "2018-12-27 09:25:33",
    "need_watering": "13", // 总需要浇水次数
    "had_watered": 6, // 已浇水次数
    "status": 2, // 果树状态:1:种子 2:树苗 3:树木 4:开花 5:结果 6:成熟 7:已采摘
    "user_id": 0000000, 
    "id": 1
  },
  "code": 0
}
```