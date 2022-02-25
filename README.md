# xiaohongshu
小红书数据采集， 原生官方api, 支持日采百万！

 
## 搜索
```
/xhs/search
```
### 参数:
- searchType: general=综合，hot=最热，time=最新
- kw 关键词
- sortType  all	筛选笔记：all=不限 ，videos=视频， notes=图文 笔记 
- pageIndex 翻页参数 1-50

## 用户信息
```
/xhs/user/detail
```
### 参数:
- userId

## 用户笔记列表
```
/xhs/note/list
```
### 参数:
- userId
- pageIndex 翻页参数，默认1

## 评论
```
/xhs/note/comments
```
### 参数:
- noteId
- startId 页参数，默认0，列表最后用户id作为下一页翻页参数

## 笔记详情
```
/xhs/note/detail
```
### 参数:
- noteId

## 话题笔记列表
```
/xhs/note/topics
```
### 参数:
- pageId topic分享页的id
- cursor 首次为空，根据结果返回的cursor传入作为下一页翻页参数
- searchType hot=最热，time=最新

## 其他


```
有任何问题可交流学习  
请勿使用本服务于商用   
请勿使用本服务大量抓取   
若因使用本服务与平台造成不必要的纠纷，本人盖不负责  
本人纯粹技术爱好，若侵犯贵公司的权益，请告知  
```

有需要的[联系](https://qr.api.cli.im/newqr/create?data=https%253A%252F%252Fqm.qq.com%252Fcgi-bin%252Fqm%252Fqr%253Fk%253DgsXU_14bQsI8BdSevrFzHU7vIYnRCnFQ%2526noverify%253D0&level=H&transparent=false&bgcolor=%23FFFFFF&forecolor=%23000000&blockpixel=12&marginblock=1&logourl=&logoshape=no&size=500&kid=cliim&key=211db538a2ba8c28441f5d952fe165db)

### 另有[抖音](https://github.com/canglingzhiyue/douyin)数据采集
### [拼多多](https://github.com/canglingzhiyue/pdd)数据接口
