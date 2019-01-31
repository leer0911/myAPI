# 打开签到宝箱

::: tip

打开签到宝箱

> `POST` /trees/treasure

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
      "data": [],
      "redirect_url": "",
      "image": "",
      "type": 1,
      "name": "60g 水"
    },
    {
      "data": [
        {
          "redirect_url": "",
          "coupon": 1000,
          "price": "128.00",
          "pic": "",
          "title": "吉普盾 男士防风加厚羽绒服"
        },
        {
          "redirect_url": "",
          "coupon": 1000,
          "price": "38.00",
          "pic": "",
          "title": "【孙茜代言】儿童智能机器人玩具语音对话学习故事机小帅人工智能蛋才"
        },
        {
          "redirect_url": "",
          "coupon": 3,
          "price": "26.90",
          "pic": "",
          "title": "三只松鼠乳酸面包800g"
        }
      ],
      "redirect_url": "",
      "image": "",
      "type": 4,
      "name": "柚子街优惠券"
    }
  ],
  "code": 0
}
```