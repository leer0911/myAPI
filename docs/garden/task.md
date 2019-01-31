# 任务列表

::: tip

获取任务列表

> `GET` /trees/task

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
      "description": "奖励10g水滴，每天5次，每次间隔10分钟",
      "residue_time": 0,
      "image": "",
      "name": "每日免费领水",
      "status": 1,
      "id": 1
    },
    {
      "description": "每日07:00~09:00,12:00~14:00,18:00~21:00，每次10g水滴",
      "residue_time": 0,
      "image": "",
      "name": "每日三餐福袋",
      "status": 1,
      "id": 2
    },
    {
      "description": "奖励10g水滴，每天3次，每次间隔10分钟",
      "residue_time": 0,
      "image": "",
      "name": "浏览资讯详情",
      "status": 1,
      "id": 3
    },
    {
      "description": "每次获得20g 水，每日2次，回复一次送一次领水",
      "residue_time": 0,
      "image": "",
      "name": "资讯发表回复",
      "status": 1,
      "id": 5
    },
    {
      "description": "每次获得20g 水，每日2次，回复一次送一次领水",
      "residue_time": 0,
      "image": "",
      "name": "她她圈发表帖子",
      "status": 2,
      "id": 6
    }
  ],
  "code": 0
}
```

::: tip

领取任务奖励

> `POST` /trees/task

:::

## Request

### 请求头

| 参数名        | 类型   | 是否必填 | 备注       | 示例             |
| ------------- | ------ | -------- | ---------- | ---------------- |
| Authorization | string | 是       | 请求授权头 | dfsdfasdfsdfasdf |

## Response

```json
{
  "code": "value",
  "data": "value",
  "message": "value"
}
```