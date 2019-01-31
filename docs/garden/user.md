# 获取用户信息 

::: tip

获取用户信息

> `GET` /trees/user

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
    "created_at": "2018-12-25 10:17:05",
    "updated_at": "2018-12-27 09:25:33",
    "tree_num": 0,
    "level": 0, // 等级:0 初始用户 1:初级园丁 2:中级园丁 3:高级园丁
    "water_num": 9, // 水滴数
    "name": "测试环境",
    "avatar": "",
    "user_id": 000000000,
    "id": 2
  },
  "code": 0
}
```