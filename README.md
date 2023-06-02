# xiaohongshu
##  小红书数据采集， 原生官方api, 支持日采400万+！
##  数据均为app实时数据，非市面上缓存数据，请自行鉴定。

### 返回code常用状态码说明
|状态码|说明|
|--|--|
|0|仅表示请求成功|
|401004|用户不存在,请先开户|
|401005|用户被锁定|
|401017|次数用完|
|401018|token缺失|
|500001|系统内部异常|
|500002|请求有问题|

 
## 1.搜索笔记
```
/xhs/searchNote
```

### 参数:
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|
|kw|string|是|关键词|
|sortType|string|是|0=综合，1=最热，2=最新|
|searchType|string|是|0=默认，1=图文，2=视频|
|pageIndex|int|是|1=默认，翻页参数1-50页|


## 2.搜索用户
```
/xhs/searchUser
```
### 参数:
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|
|kw|string|是|关键词|
|pageIndex|int|是|1=默认，翻页参数1-50页|

## 3.用户信息
```
/xhs/user/detail
```
### 参数:
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|
|userId|string|是|用户id|


## 4.用户笔记列表
```
/xhs/note/list
```
### 参数:
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|
|userId|string|是|用户ID|
|pageIndex|string|是|翻页参数，首次默认为0，根据返回结果cursor获取下一页|

## 5.评论列表
```
/xhs/note/comments
```
### 参数:
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|
|noteId|string|是|笔记id|
|startId|string|是|0=默认，根据返回结果最后target_comment里面的id作为下一页翻页参数, 也可以直接用最后一个评论的ID|

## 6.评论回复
```
/xhs/note/comment_reply
```
### 参数:
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|
|noteId|string|是|笔记id|
|commentId|string|否|评论组id|
|startId|string|否|评论组第一个评论的id|

## 7.笔记详情
```
/xhs/note/detail
```
### 参数:
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|
|noteId|string|是|笔记id|


## 8.关注列表
```
/xhs/user/focus
```
### 参数:
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|
|userId|string|是|用户ID|
|pageIndex|string|是|翻页参数，默认=0，根据返回结果cursor获取下一页|

## 9.粉丝列表
```
/xhs/user/fans
```
### 参数:
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|
|userId|string|是|用户ID|
|pageIndex|string|是|翻页参数，默认=0，根据返回结果cursor获取下一页|


## 10.收藏列表
```
/xhs/user/faver
```
### 参数:
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|
|userId|string|是|用户ID|
|pageIndex|string|是|翻页参数，默认=0，根据返回结果cursor获取下一页|



## 其他
### 调用次数/剩余次数查询
```
/user/reqCount
```
|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|token|string|是|访问凭证|


```
有任何问题可交流学习  
请勿使用本服务于商用   
请勿使用本服务大量抓取   
若因使用本服务与平台造成不必要的纠纷，本人盖不负责  
本人纯粹技术爱好，若侵犯贵公司的权益，请告知  
```

### [抖音](https://github.com/canglingzhiyue/douyin)
<!-- 
 ![qq](https://qr.api.cli.im/newqr/create?data=https%253A%252F%252Fqm.qq.com%252Fcgi-bin%252Fqm%252Fqr%253Fk%253DgsXU_14bQsI8BdSevrFzHU7vIYnRCnFQ%2526noverify%253D0&level=H&transparent=false&bgcolor=%23FFFFFF&forecolor=%23000000&blockpixel=12&marginblock=1&logourl=&logoshape=no&size=500&kid=cliim&key=211db538a2ba8c28441f5d952fe165db)

~~### 或者添加TG(@XHSAPI)：~~
###
~~![tg](https://api.isoyu.com/qr/?m=0&e=L&p=10&url=https%3A%2F%2Ft.me%2Fxhsapi)~~

~~### [拼多多(暂停)](https://github.com/canglingzhiyue/pdd)~~ -->
