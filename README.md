# SSA
学习通座位签到、预约、退座、暂离、综合信息查询（包含座位楼层位置、所有座位的使用信息、签到地理位置范围等）

## 具体用法请看注释，日后有时间更新详细。


## 部分功能已经开通接口

### 签到

``` python
 # url:https://o.nvidia.fun:12345/sign
 # method:post
 # parmas:
{
    "phonenums": "手机号",
    "key":"密码"
}

 # return
{
    "msg": "不在签到时间内无法签到",
    "value": "True"
}
```

### 离开、退座和取消

* 使用方法与签到一致，离开、退座和取消分别把url上的"sign"替换成"leave"、"signback"和"cancel"即可~
