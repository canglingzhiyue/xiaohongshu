# xiaohongshu
小红书数据采集， 原生官方api, 支持日采400万+！

 
## 搜索
```
/xhs/search
```
### 参数:
- searchType: general=综合，hot=最热，time=最新
- kw 关键词
- sortType  默认all	筛选笔记：all=不限 ，videos=视频， notes=图文 笔记 
- pageIndex 翻页参数 1-50

|参数名|类型|必选|说明|
|--|:--:|:--:|:--|
|apikey|string|是|访问凭证|
|kw|string|是|关键词|
|sortType|string|是|0=默认，1=图文，2=视频|
|pageIndex|int|是|0=默认，翻页参数|

```go
{
    "code": 0,
    "success": true,
    "data": {
        "items": [
            {
                "model_type": "note",
                "note": {
                    "liked": false,
                    "id": "64533a53000000001203ef7d",
                    "title": "宝宝小众高品质高颜值衣服推荐",
                    "abstract_show": "",
                    "desc": "整理了下我种草的宝宝衣服，发现真的太好看了，全部是自己心头爱，分享给有需要的新手宝妈们。我不允许宝贝们没穿过这么可爱的衣",
                    "liked_count": 0,
                    "type": "normal",
                    "user": {
                        "nickname": "蓝无机",
                        "images": "https://sns-avatar-qc.xhscdn.com/avatar/60967c79000000000100b83e.jpg?imageView2/2/w/80/format/jpg",
                        "userid": "60967c79000000000100b83e"
                    },
                    "tag_info": {},
                    "images_list": [
                        {
                            "fileid": "spectrum/1000g0k02ejnvt4ugo0005o4mfhsg9e1utslms0o",
                            "height": 791,
                            "width": 794,
                            "url": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejnvt4ugo0005o4mfhsg9e1utslms0o?imageView2/2/w/540/format/webp|imageMogr2/strip&redImage/frame/0",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejnvt4ugo0005o4mfhsg9e1utslms0o?imageView2/2/h/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejnvt4ugo0005o4mfhsg9e1utslms0o"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejnvtbego0005o4mfhsg9e1umehes68",
                            "height": 800,
                            "width": 800,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejnvtbego0005o4mfhsg9e1umehes68?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejnvtbego0005o4mfhsg9e1umehes68"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejnvtpigu0005o4mfhsg9e1u8sl9ij0",
                            "height": 800,
                            "width": 800,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejnvtpigu0005o4mfhsg9e1u8sl9ij0?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejnvtpigu0005o4mfhsg9e1u8sl9ij0"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejnvti2h80005o4mfhsg9e1unoph490",
                            "height": 800,
                            "width": 800,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejnvti2h80005o4mfhsg9e1unoph490?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejnvti2h80005o4mfhsg9e1unoph490"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejnvstkgs0005o4mfhsg9e1uhsv4620",
                            "height": 800,
                            "width": 800,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejnvstkgs0005o4mfhsg9e1uhsv4620?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejnvstkgs0005o4mfhsg9e1uhsv4620"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejo33uqgm0005o4mfhsg9e1uhgsv620",
                            "height": 1023,
                            "width": 1023,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejo33uqgm0005o4mfhsg9e1uhgsv620?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejo33uqgm0005o4mfhsg9e1uhgsv620"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejo1v8ugu0005o4mfhsg9e1ueqrr6fg",
                            "height": 1100,
                            "width": 825,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejo1v8ugu0005o4mfhsg9e1ueqrr6fg?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejo1v8ugu0005o4mfhsg9e1ueqrr6fg"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejo1ti6h00005o4mfhsg9e1ucepdero",
                            "height": 910,
                            "width": 750,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejo1ti6h00005o4mfhsg9e1ucepdero?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejo1ti6h00005o4mfhsg9e1ucepdero"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejo50okha0005o4mfhsg9e1ug6450k8",
                            "height": 630,
                            "width": 841,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejo50okha0005o4mfhsg9e1ug6450k8?imageView2/2/h/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejo50okha0005o4mfhsg9e1ug6450k8"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejo1tocgs0005o4mfhsg9e1udds98h8",
                            "height": 887,
                            "width": 750,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejo1tocgs0005o4mfhsg9e1udds98h8?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejo1tocgs0005o4mfhsg9e1udds98h8"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejo7pbch40005o4mfhsg9e1u05k6t30",
                            "height": 895,
                            "width": 895,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejo7pbch40005o4mfhsg9e1u05k6t30?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejo7pbch40005o4mfhsg9e1u05k6t30"
                        },
                        {
                            "fileid": "spectrum/1000g0k02ejo1tbih40005o4mfhsg9e1ubp653n8",
                            "height": 1002,
                            "width": 1066,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/spectrum/1000g0k02ejo1tbih40005o4mfhsg9e1ubp653n8?imageView2/2/h/1080/format/webp",
                            "original": "",
                            "trace_id": "spectrum/1000g0k02ejo1tbih40005o4mfhsg9e1ubp653n8"
                        }
                    ],
                    "has_music": false,
                    "timestamp": 1683176019,
                    "last_update_time": 0,
                    "geo_info": {
                        "distance": "<100m"
                    },
                    "corner_tag_info": [
                        {
                            "location": 5,
                            "type": "publish_time",
                            "icon": "http://picasso-static.xiaohongshu.com/fe-platform/e9b67af62f67d9d6cfac936f96ad10a85fdb868e.png",
                            "text": "6分钟前",
                            "text_en": "6 mins ago"
                        }
                    ],
                    "advanced_widgets_groups": {
                        "groups": [
                            {
                                "mode": 1,
                                "fetch_types": [
                                    "note_next_step",
                                    "second_jump_bar",
                                    "cooperate_binds",
                                    "note_collection",
                                    "rec_next_infos",
                                    "image_stickers",
                                    "image_filters",
                                    "product_review",
                                    "related_search",
                                    "cooperate_comment_component",
                                    "image_goods_cards",
                                    "ads_goods_cards",
                                    "ads_comment_component",
                                    "goods_card_v2",
                                    "image_template",
                                    "red_map_tag",
                                    "share_open_user",
                                    "buyable_goods_card_v2",
                                    "ads_engage_bar"
                                ]
                            },
                            {
                                "mode": 0,
                                "fetch_types": [
                                    "vote_stickers",
                                    "bullet_comment_lead",
                                    "note_search_box",
                                    "interact_pk",
                                    "interact_vote"
                                ]
                            }
                        ]
                    },
                    "widgets_context": "{\"flags\":{},\"author_id\":\"60967c79000000000100b83e\",\"author_name\":\"蓝无机\",\"r_r_t\":0}"
                }
            },
            {
                "model_type": "note",
                "note": {
                    "liked": false,
                    "id": "64533a52000000001203ef7c",
                    "title": "出闲置衣服",
                    "abstract_show": "",
                    "desc": "基本都25包邮，个别贵 想要私信#闲置衣服  #二手闲置  #断舍离  #清衣柜  #出闲置",
                    "liked_count": 0,
                    "type": "normal",
                    "user": {
                        "nickname": "..",
                        "images": "https://sns-avatar-qc.xhscdn.com/avatar/644b2aba46534cda96f718c5.jpg?imageView2/2/w/80/format/jpg",
                        "userid": "5bbaae603c2ad900010264b1"
                    },
                    "tag_info": {},
                    "images_list": [
                        {
                            "fileid": "1000g0082ejscoi0h00004bbs2nn60p5h73q9id8",
                            "height": 1920,
                            "width": 1440,
                            "url": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h00004bbs2nn60p5h73q9id8?imageView2/2/w/540/format/webp|imageMogr2/strip&redImage/frame/0",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h00004bbs2nn60p5h73q9id8?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h00004bbs2nn60p5h73q9id8"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h000g4bbs2nn60p5hbi2aj7g",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h000g4bbs2nn60p5hbi2aj7g?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h000g4bbs2nn60p5hbi2aj7g"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h00104bbs2nn60p5hhna8eoo",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h00104bbs2nn60p5hhna8eoo?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h00104bbs2nn60p5hhna8eoo"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h001g4bbs2nn60p5hg9462no",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h001g4bbs2nn60p5hg9462no?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h001g4bbs2nn60p5hg9462no"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h00204bbs2nn60p5hm65gun8",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h00204bbs2nn60p5hm65gun8?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h00204bbs2nn60p5hm65gun8"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h002g4bbs2nn60p5h53upvd0",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h002g4bbs2nn60p5h53upvd0?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h002g4bbs2nn60p5h53upvd0"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h00304bbs2nn60p5hltse05g",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h00304bbs2nn60p5hltse05g?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h00304bbs2nn60p5hltse05g"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h003g4bbs2nn60p5hlb6rqtg",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h003g4bbs2nn60p5hlb6rqtg?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h003g4bbs2nn60p5hlb6rqtg"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h00404bbs2nn60p5hfcvntcg",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h00404bbs2nn60p5hfcvntcg?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h00404bbs2nn60p5hfcvntcg"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h004g4bbs2nn60p5h662s4t8",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h004g4bbs2nn60p5h662s4t8?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h004g4bbs2nn60p5h662s4t8"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h00504bbs2nn60p5hfu0gdi0",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h00504bbs2nn60p5hfu0gdi0?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h00504bbs2nn60p5hfu0gdi0"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h005g4bbs2nn60p5h1sq7mno",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h005g4bbs2nn60p5h1sq7mno?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h005g4bbs2nn60p5h1sq7mno"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h00604bbs2nn60p5h9jp4488",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h00604bbs2nn60p5h9jp4488?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h00604bbs2nn60p5h9jp4488"
                        },
                        {
                            "fileid": "1000g0082ejscoi0h006g4bbs2nn60p5hih15ps8",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscoi0h006g4bbs2nn60p5hih15ps8?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscoi0h006g4bbs2nn60p5hih15ps8"
                        },
                        {
                            "fileid": "1000g0082ejscopeh00004bbs2nn60p5hkkn4l1g",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejscopeh00004bbs2nn60p5hkkn4l1g?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejscopeh00004bbs2nn60p5hkkn4l1g"
                        }
                    ],
                    "has_music": false,
                    "timestamp": 1683176018,
                    "last_update_time": 0,
                    "geo_info": {
                        "distance": "<100m"
                    },
                    "corner_tag_info": [
                        {
                            "location": 5,
                            "type": "publish_time",
                            "icon": "http://picasso-static.xiaohongshu.com/fe-platform/e9b67af62f67d9d6cfac936f96ad10a85fdb868e.png",
                            "text": "6分钟前",
                            "text_en": "6 mins ago"
                        }
                    ],
                    "advanced_widgets_groups": {
                        "groups": [
                            {
                                "mode": 1,
                                "fetch_types": [
                                    "note_next_step",
                                    "second_jump_bar",
                                    "cooperate_binds",
                                    "note_collection",
                                    "rec_next_infos",
                                    "image_stickers",
                                    "image_filters",
                                    "product_review",
                                    "related_search",
                                    "cooperate_comment_component",
                                    "image_goods_cards",
                                    "ads_goods_cards",
                                    "ads_comment_component",
                                    "goods_card_v2",
                                    "image_template",
                                    "red_map_tag",
                                    "share_open_user",
                                    "buyable_goods_card_v2",
                                    "ads_engage_bar"
                                ]
                            },
                            {
                                "mode": 0,
                                "fetch_types": [
                                    "vote_stickers",
                                    "bullet_comment_lead",
                                    "note_search_box",
                                    "interact_pk",
                                    "interact_vote"
                                ]
                            }
                        ]
                    },
                    "widgets_context": "{\"flags\":{},\"author_id\":\"5bbaae603c2ad900010264b1\",\"author_name\":\"..\",\"r_r_t\":0}"
                }
            },
            {
                "model_type": "note",
                "note": {
                    "liked": false,
                    "id": "64533a4d000000000800e7e8",
                    "title": "婚期已过，出敬酒服！",
                    "abstract_show": "",
                    "desc": "传递幸福 质量很好的敬酒服，丝绒的 本人身高155，体重92 敬酒因为赶时间穿了不到20分钟 108包邮出 #敬酒服",
                    "liked_count": 1,
                    "type": "normal",
                    "user": {
                        "nickname": "糖醋小李脊",
                        "images": "https://sns-avatar-qc.xhscdn.com/avatar/61eba023e2098371a0e39fd8.jpg?imageView2/2/w/80/format/jpg",
                        "userid": "5f25225b000000000101fd4a"
                    },
                    "tag_info": {},
                    "images_list": [
                        {
                            "fileid": "1000g0082ejse8e8go0005np549dgbvaapgfk3eg",
                            "height": 889,
                            "width": 1241,
                            "url": "http://sns-img-hw.xhscdn.com/1000g0082ejse8e8go0005np549dgbvaapgfk3eg?imageView2/2/w/540/format/webp|imageMogr2/strip&redImage/frame/0",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejse8e8go0005np549dgbvaapgfk3eg?imageView2/2/h/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejse8e8go0005np549dgbvaapgfk3eg"
                        },
                        {
                            "fileid": "1000g0082ejse8e8go00g5np549dgbvaajrgpc18",
                            "height": 1280,
                            "width": 1280,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejse8e8go00g5np549dgbvaajrgpc18?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejse8e8go00g5np549dgbvaajrgpc18"
                        },
                        {
                            "fileid": "1000g0082ejse8e8go0105np549dgbvaasq81om0",
                            "height": 1280,
                            "width": 1280,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejse8e8go0105np549dgbvaasq81om0?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejse8e8go0105np549dgbvaasq81om0"
                        }
                    ],
                    "has_music": false,
                    "timestamp": 1683176013,
                    "last_update_time": 0,
                    "geo_info": {
                        "distance": "<100m"
                    },
                    "corner_tag_info": [
                        {
                            "location": 5,
                            "type": "publish_time",
                            "icon": "http://picasso-static.xiaohongshu.com/fe-platform/e9b67af62f67d9d6cfac936f96ad10a85fdb868e.png",
                            "text": "6分钟前",
                            "text_en": "6 mins ago"
                        }
                    ],
                    "advanced_widgets_groups": {
                        "groups": [
                            {
                                "mode": 1,
                                "fetch_types": [
                                    "note_next_step",
                                    "second_jump_bar",
                                    "cooperate_binds",
                                    "note_collection",
                                    "rec_next_infos",
                                    "image_stickers",
                                    "image_filters",
                                    "product_review",
                                    "related_search",
                                    "cooperate_comment_component",
                                    "image_goods_cards",
                                    "ads_goods_cards",
                                    "ads_comment_component",
                                    "goods_card_v2",
                                    "image_template",
                                    "red_map_tag",
                                    "share_open_user",
                                    "buyable_goods_card_v2",
                                    "ads_engage_bar"
                                ]
                            },
                            {
                                "mode": 0,
                                "fetch_types": [
                                    "vote_stickers",
                                    "bullet_comment_lead",
                                    "note_search_box",
                                    "interact_pk",
                                    "interact_vote"
                                ]
                            }
                        ]
                    },
                    "widgets_context": "{\"flags\":{},\"author_id\":\"5f25225b000000000101fd4a\",\"author_name\":\"糖醋小李脊\",\"r_r_t\":0}"
                }
            },
            {
                "model_type": "note",
                "note": {
                    "liked": false,
                    "id": "64533a4800000000130053d4",
                    "title": "不一样的亲子装～吊带包屁衣",
                    "abstract_show": "",
                    "desc": "小月龄女宝宝的包屁衣，清清爽爽的过夏天啦 简简单单一套，百搭舒适又可爱 亲子装不一定是一模一样的穿搭，同色系也很搭呢#创",
                    "liked_count": 0,
                    "type": "normal",
                    "user": {
                        "nickname": "点点｀韩童馆（教搭配）",
                        "images": "https://sns-avatar-qc.xhscdn.com/avatar/6380a6b06d3615bf7f25dbeb.jpg?imageView2/2/w/80/format/jpg",
                        "userid": "634a9999000000001901d8b1"
                    },
                    "tag_info": {},
                    "images_list": [
                        {
                            "fileid": "1000g0082ejsdumigm06g5oqaj6cmbm5hbura708",
                            "height": 2560,
                            "width": 1920,
                            "url": "http://sns-img-hw.xhscdn.com/1000g0082ejsdumigm06g5oqaj6cmbm5hbura708?imageView2/2/w/540/format/webp|imageMogr2/strip&redImage/frame/0",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsdumigm06g5oqaj6cmbm5hbura708?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsdumigm06g5oqaj6cmbm5hbura708"
                        },
                        {
                            "fileid": "1000g0082ejsdumigm0505oqaj6cmbm5hlm76rdg",
                            "height": 2560,
                            "width": 1920,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsdumigm0505oqaj6cmbm5hlm76rdg?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsdumigm0505oqaj6cmbm5hlm76rdg"
                        },
                        {
                            "fileid": "1000g0082ejsdumigm04g5oqaj6cmbm5h4i8am60",
                            "height": 2560,
                            "width": 1920,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsdumigm04g5oqaj6cmbm5h4i8am60?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsdumigm04g5oqaj6cmbm5h4i8am60"
                        },
                        {
                            "fileid": "1000g0082ejsdumigm05g5oqaj6cmbm5ha47fjp0",
                            "height": 2560,
                            "width": 1920,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsdumigm05g5oqaj6cmbm5ha47fjp0?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsdumigm05g5oqaj6cmbm5ha47fjp0"
                        }
                    ],
                    "has_music": false,
                    "timestamp": 1683176008,
                    "last_update_time": 0,
                    "geo_info": {
                        "distance": "<100m"
                    },
                    "corner_tag_info": [
                        {
                            "location": 5,
                            "type": "publish_time",
                            "icon": "http://picasso-static.xiaohongshu.com/fe-platform/e9b67af62f67d9d6cfac936f96ad10a85fdb868e.png",
                            "text": "6分钟前",
                            "text_en": "6 mins ago"
                        }
                    ],
                    "advanced_widgets_groups": {
                        "groups": [
                            {
                                "mode": 1,
                                "fetch_types": [
                                    "note_next_step",
                                    "second_jump_bar",
                                    "cooperate_binds",
                                    "note_collection",
                                    "rec_next_infos",
                                    "image_stickers",
                                    "image_filters",
                                    "product_review",
                                    "related_search",
                                    "cooperate_comment_component",
                                    "image_goods_cards",
                                    "ads_goods_cards",
                                    "ads_comment_component",
                                    "goods_card_v2",
                                    "image_template",
                                    "red_map_tag",
                                    "share_open_user",
                                    "buyable_goods_card_v2",
                                    "ads_engage_bar"
                                ]
                            },
                            {
                                "mode": 0,
                                "fetch_types": [
                                    "vote_stickers",
                                    "bullet_comment_lead",
                                    "note_search_box",
                                    "interact_pk",
                                    "interact_vote"
                                ]
                            }
                        ]
                    },
                    "widgets_context": "{\"flags\":{},\"author_id\":\"634a9999000000001901d8b1\",\"author_name\":\"点点｀韩童馆（教搭配）\",\"r_r_t\":0}"
                }
            },
            {
                "model_type": "note",
                "note": {
                    "liked": false,
                    "id": "64533a4500000000130053bc",
                    "title": "宝宝连体衣",
                    "abstract_show": "",
                    "desc": "Burberry 芬迪 #宝宝爬服连体衣  #婴童穿搭  #宝宝连体衣  #宝宝衣服  #宝宝穿搭  #宝宝穿搭分享",
                    "liked_count": 0,
                    "type": "normal",
                    "user": {
                        "nickname": "BobbyLing",
                        "images": "https://sns-avatar-qc.xhscdn.com/avatar/614ea6dcaefcebe137501ab4.jpg?imageView2/2/w/80/format/jpg",
                        "userid": "608ac8ac0000000001007351"
                    },
                    "tag_info": {},
                    "images_list": [
                        {
                            "fileid": "1000g0082ejsdo7ch80005o4ap2m08sqhdlb7hng",
                            "height": 1412,
                            "width": 1080,
                            "url": "http://sns-img-hw.xhscdn.com/1000g0082ejsdo7ch80005o4ap2m08sqhdlb7hng?imageView2/2/w/540/format/webp|imageMogr2/strip&redImage/frame/0",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsdo7ch80005o4ap2m08sqhdlb7hng?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsdo7ch80005o4ap2m08sqhdlb7hng"
                        },
                        {
                            "fileid": "1000g0082ejsdo7ch800g5o4ap2m08sqhe70uqo0",
                            "height": 1414,
                            "width": 1080,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsdo7ch800g5o4ap2m08sqhe70uqo0?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsdo7ch800g5o4ap2m08sqhe70uqo0"
                        },
                        {
                            "fileid": "1000g0082ejsdo7ch80105o4ap2m08sqhnocngg8",
                            "height": 1476,
                            "width": 1080,
                            "url": "",
                            "url_size_large": "http://redimage.xhscdn.com/1000g0082ejsdo7ch80105o4ap2m08sqhnocngg8?imageView2/1/w/1080/h/1440/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsdo7ch80105o4ap2m08sqhnocngg8"
                        },
                        {
                            "fileid": "1000g0082ejsdo7ch801g5o4ap2m08sqh5onkvs8",
                            "height": 1528,
                            "width": 1080,
                            "url": "",
                            "url_size_large": "http://redimage.xhscdn.com/1000g0082ejsdo7ch801g5o4ap2m08sqh5onkvs8?imageView2/1/w/1080/h/1440/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsdo7ch801g5o4ap2m08sqh5onkvs8"
                        },
                        {
                            "fileid": "1000g0082ejsdo7ch80205o4ap2m08sqhne424po",
                            "height": 1382,
                            "width": 1080,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsdo7ch80205o4ap2m08sqhne424po?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsdo7ch80205o4ap2m08sqhne424po"
                        },
                        {
                            "fileid": "1000g0082ejsdo7ch802g5o4ap2m08sqh8n886ho",
                            "height": 1498,
                            "width": 1080,
                            "url": "",
                            "url_size_large": "http://redimage.xhscdn.com/1000g0082ejsdo7ch802g5o4ap2m08sqh8n886ho?imageView2/1/w/1080/h/1440/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsdo7ch802g5o4ap2m08sqh8n886ho"
                        }
                    ],
                    "has_music": false,
                    "timestamp": 1683176005,
                    "last_update_time": 0,
                    "geo_info": {
                        "distance": "<100m"
                    },
                    "corner_tag_info": [
                        {
                            "location": 5,
                            "type": "publish_time",
                            "icon": "http://picasso-static.xiaohongshu.com/fe-platform/e9b67af62f67d9d6cfac936f96ad10a85fdb868e.png",
                            "text": "6分钟前",
                            "text_en": "6 mins ago"
                        }
                    ],
                    "advanced_widgets_groups": {
                        "groups": [
                            {
                                "mode": 1,
                                "fetch_types": [
                                    "note_next_step",
                                    "second_jump_bar",
                                    "cooperate_binds",
                                    "note_collection",
                                    "rec_next_infos",
                                    "image_stickers",
                                    "image_filters",
                                    "product_review",
                                    "related_search",
                                    "cooperate_comment_component",
                                    "image_goods_cards",
                                    "ads_goods_cards",
                                    "ads_comment_component",
                                    "goods_card_v2",
                                    "image_template",
                                    "red_map_tag",
                                    "share_open_user",
                                    "buyable_goods_card_v2",
                                    "ads_engage_bar"
                                ]
                            },
                            {
                                "mode": 0,
                                "fetch_types": [
                                    "vote_stickers",
                                    "bullet_comment_lead",
                                    "note_search_box",
                                    "interact_pk",
                                    "interact_vote"
                                ]
                            }
                        ]
                    },
                    "widgets_context": "{\"flags\":{},\"author_id\":\"608ac8ac0000000001007351\",\"author_name\":\"BobbyLing\",\"r_r_t\":0}"
                }
            },
            {
                "model_type": "note",
                "note": {
                    "liked": false,
                    "id": "64533a300000000011010231",
                    "title": "潮流夹克",
                    "abstract_show": "",
                    "desc": "#推荐衣服  出售芙沿美式vintage复古棋盘格棒球服外套女秋冬加厚情侣装ins潮夹克#夹克外套  价格好商量",
                    "liked_count": 0,
                    "type": "normal",
                    "user": {
                        "nickname": "贝肯妮",
                        "images": "https://sns-avatar-qc.xhscdn.com/avatar/642151272a05a5c7c482642a.jpg?imageView2/2/w/80/format/jpg",
                        "userid": "5fab838300000000010037df"
                    },
                    "tag_info": {},
                    "images_list": [
                        {
                            "fileid": "1000g0082ejsccv2h006g5ntbge1g8duveigje7g",
                            "height": 1000,
                            "width": 750,
                            "url": "http://sns-img-hw.xhscdn.com/1000g0082ejsccv2h006g5ntbge1g8duveigje7g?imageView2/2/w/540/format/webp|imageMogr2/strip&redImage/frame/0",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsccv2h006g5ntbge1g8duveigje7g?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsccv2h006g5ntbge1g8duveigje7g"
                        },
                        {
                            "fileid": "1000g0082ejsccv2h00605ntbge1g8duvsqa2u60",
                            "height": 1000,
                            "width": 750,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsccv2h00605ntbge1g8duvsqa2u60?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsccv2h00605ntbge1g8duvsqa2u60"
                        },
                        {
                            "fileid": "1000g0082ejsccv2h005g5ntbge1g8duv6mmmvg0",
                            "height": 1000,
                            "width": 750,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsccv2h005g5ntbge1g8duv6mmmvg0?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsccv2h005g5ntbge1g8duv6mmmvg0"
                        },
                        {
                            "fileid": "1000g0082ejsccv2h004g5ntbge1g8duvlg4f1r8",
                            "height": 1000,
                            "width": 750,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsccv2h004g5ntbge1g8duvlg4f1r8?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsccv2h004g5ntbge1g8duvlg4f1r8"
                        },
                        {
                            "fileid": "1000g0082ejsccv2h00405ntbge1g8duvh7omqn8",
                            "height": 1000,
                            "width": 750,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejsccv2h00405ntbge1g8duvh7omqn8?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejsccv2h00405ntbge1g8duvh7omqn8"
                        }
                    ],
                    "has_music": false,
                    "timestamp": 1683175984,
                    "last_update_time": 0,
                    "geo_info": {
                        "distance": "<100m"
                    },
                    "corner_tag_info": [
                        {
                            "location": 5,
                            "type": "publish_time",
                            "icon": "http://picasso-static.xiaohongshu.com/fe-platform/e9b67af62f67d9d6cfac936f96ad10a85fdb868e.png",
                            "text": "6分钟前",
                            "text_en": "6 mins ago"
                        }
                    ],
                    "advanced_widgets_groups": {
                        "groups": [
                            {
                                "mode": 1,
                                "fetch_types": [
                                    "note_next_step",
                                    "second_jump_bar",
                                    "cooperate_binds",
                                    "note_collection",
                                    "rec_next_infos",
                                    "image_stickers",
                                    "image_filters",
                                    "product_review",
                                    "related_search",
                                    "cooperate_comment_component",
                                    "image_goods_cards",
                                    "ads_goods_cards",
                                    "ads_comment_component",
                                    "goods_card_v2",
                                    "image_template",
                                    "red_map_tag",
                                    "share_open_user",
                                    "buyable_goods_card_v2",
                                    "ads_engage_bar"
                                ]
                            },
                            {
                                "mode": 0,
                                "fetch_types": [
                                    "vote_stickers",
                                    "bullet_comment_lead",
                                    "note_search_box",
                                    "interact_pk",
                                    "interact_vote"
                                ]
                            }
                        ]
                    },
                    "widgets_context": "{\"flags\":{},\"author_id\":\"5fab838300000000010037df\",\"author_name\":\"贝肯妮\",\"r_r_t\":0}"
                }
            },
            {
                "model_type": "note",
                "note": {
                    "liked": false,
                    "id": "64533a0100000000130051f4",
                    "title": "三伏天月子服颜值高又平价",
                    "abstract_show": "",
                    "desc": "7月预产期，夏季坐月子选对月子服真的很重要，我选的是棉纱和莫代尔的面料！卖家说这两种都是夏季专属材质，料子很薄很轻盈、透",
                    "liked_count": 1,
                    "type": "normal",
                    "user": {
                        "nickname": "小陈子",
                        "images": "https://sns-avatar-qc.xhscdn.com/avatar/6429198296f1673aea68ce61.jpg?imageView2/2/w/80/format/jpg",
                        "userid": "641d76fb0000000011021615"
                    },
                    "tag_info": {},
                    "images_list": [
                        {
                            "fileid": "1000g0082ejs9fj0go0705p0tertkc5glqe3jji0",
                            "height": 1620,
                            "width": 1215,
                            "url": "http://sns-img-hw.xhscdn.com/1000g0082ejs9fj0go0705p0tertkc5glqe3jji0?imageView2/2/w/540/format/webp|imageMogr2/strip&redImage/frame/0",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs9fj0go0705p0tertkc5glqe3jji0?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs9fj0go0705p0tertkc5glqe3jji0"
                        },
                        {
                            "fileid": "1000g0082ejs9fj0go07g5p0tertkc5glikqqtm0",
                            "height": 1620,
                            "width": 1215,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs9fj0go07g5p0tertkc5glikqqtm0?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs9fj0go07g5p0tertkc5glikqqtm0"
                        },
                        {
                            "fileid": "1000g0082ejs9fj0go0805p0tertkc5glphj9org",
                            "height": 1620,
                            "width": 1215,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs9fj0go0805p0tertkc5glphj9org?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs9fj0go0805p0tertkc5glphj9org"
                        },
                        {
                            "fileid": "1000g0082ejs9fj0go08g5p0tertkc5glihqq5f0",
                            "height": 1620,
                            "width": 1215,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs9fj0go08g5p0tertkc5glihqq5f0?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs9fj0go08g5p0tertkc5glihqq5f0"
                        }
                    ],
                    "has_music": false,
                    "timestamp": 1683175937,
                    "last_update_time": 0,
                    "geo_info": {
                        "distance": "<100m"
                    },
                    "corner_tag_info": [
                        {
                            "location": 5,
                            "type": "publish_time",
                            "icon": "http://picasso-static.xiaohongshu.com/fe-platform/e9b67af62f67d9d6cfac936f96ad10a85fdb868e.png",
                            "text": "7分钟前",
                            "text_en": "7 mins ago"
                        }
                    ],
                    "advanced_widgets_groups": {
                        "groups": [
                            {
                                "mode": 1,
                                "fetch_types": [
                                    "note_next_step",
                                    "second_jump_bar",
                                    "cooperate_binds",
                                    "note_collection",
                                    "rec_next_infos",
                                    "image_stickers",
                                    "image_filters",
                                    "product_review",
                                    "related_search",
                                    "cooperate_comment_component",
                                    "image_goods_cards",
                                    "ads_goods_cards",
                                    "ads_comment_component",
                                    "goods_card_v2",
                                    "image_template",
                                    "red_map_tag",
                                    "share_open_user",
                                    "buyable_goods_card_v2",
                                    "ads_engage_bar"
                                ]
                            },
                            {
                                "mode": 0,
                                "fetch_types": [
                                    "vote_stickers",
                                    "bullet_comment_lead",
                                    "note_search_box",
                                    "interact_pk",
                                    "interact_vote"
                                ]
                            }
                        ]
                    },
                    "widgets_context": "{\"flags\":{},\"author_id\":\"641d76fb0000000011021615\",\"author_name\":\"小陈子\",\"r_r_t\":0}"
                }
            },
            {
                "model_type": "note",
                "note": {
                    "liked": false,
                    "id": "645339fa00000000270129f8",
                    "title": "一起来做衣服吧！！",
                    "abstract_show": "",
                    "desc": "武汉大悦城店#HOWOWD2Y  #大悦城  一起来体验做衣服吧",
                    "liked_count": 2,
                    "type": "normal",
                    "user": {
                        "nickname": "Ju.",
                        "images": "https://sns-avatar-qc.xhscdn.com/avatar/63595659e41b2b321120757f.jpg?imageView2/2/w/80/format/jpg",
                        "userid": "60210350000000000101fc54"
                    },
                    "tag_info": {},
                    "images_list": [
                        {
                            "fileid": "1000g0082ejs8v4mgm0005o110d80bv2kfadov68",
                            "height": 1920,
                            "width": 1440,
                            "url": "http://sns-img-hw.xhscdn.com/1000g0082ejs8v4mgm0005o110d80bv2kfadov68?imageView2/2/w/540/format/webp|imageMogr2/strip&redImage/frame/0",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs8v4mgm0005o110d80bv2kfadov68?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs8v4mgm0005o110d80bv2kfadov68"
                        },
                        {
                            "fileid": "1000g0082ejs8v4mgm00g5o110d80bv2kkqk30ng",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs8v4mgm00g5o110d80bv2kkqk30ng?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs8v4mgm00g5o110d80bv2kkqk30ng"
                        },
                        {
                            "fileid": "1000g0082ejs8v4mgm0105o110d80bv2k3937tog",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs8v4mgm0105o110d80bv2k3937tog?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs8v4mgm0105o110d80bv2k3937tog"
                        },
                        {
                            "fileid": "1000g0082ejs8v4mgm01g5o110d80bv2k6h3k078",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs8v4mgm01g5o110d80bv2k6h3k078?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs8v4mgm01g5o110d80bv2k6h3k078"
                        },
                        {
                            "fileid": "1000g0082ejs8v4mgm0205o110d80bv2kf9rjjt8",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs8v4mgm0205o110d80bv2kf9rjjt8?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs8v4mgm0205o110d80bv2kf9rjjt8"
                        },
                        {
                            "fileid": "1000g0082ejs8v4mgm02g5o110d80bv2k126nmb8",
                            "height": 1920,
                            "width": 1440,
                            "url": "",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs8v4mgm02g5o110d80bv2k126nmb8?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs8v4mgm02g5o110d80bv2k126nmb8"
                        }
                    ],
                    "has_music": false,
                    "timestamp": 1683175930,
                    "last_update_time": 0,
                    "geo_info": {
                        "distance": "<100m"
                    },
                    "corner_tag_info": [
                        {
                            "location": 5,
                            "type": "publish_time",
                            "icon": "http://picasso-static.xiaohongshu.com/fe-platform/e9b67af62f67d9d6cfac936f96ad10a85fdb868e.png",
                            "text": "7分钟前",
                            "text_en": "7 mins ago"
                        }
                    ],
                    "advanced_widgets_groups": {
                        "groups": [
                            {
                                "mode": 1,
                                "fetch_types": [
                                    "note_next_step",
                                    "second_jump_bar",
                                    "cooperate_binds",
                                    "note_collection",
                                    "rec_next_infos",
                                    "image_stickers",
                                    "image_filters",
                                    "product_review",
                                    "related_search",
                                    "cooperate_comment_component",
                                    "image_goods_cards",
                                    "ads_goods_cards",
                                    "ads_comment_component",
                                    "goods_card_v2",
                                    "image_template",
                                    "red_map_tag",
                                    "share_open_user",
                                    "buyable_goods_card_v2",
                                    "ads_engage_bar"
                                ]
                            },
                            {
                                "mode": 0,
                                "fetch_types": [
                                    "vote_stickers",
                                    "bullet_comment_lead",
                                    "note_search_box",
                                    "interact_pk",
                                    "interact_vote"
                                ]
                            }
                        ]
                    },
                    "widgets_context": "{\"flags\":{},\"author_id\":\"60210350000000000101fc54\",\"author_name\":\"Ju.\",\"r_r_t\":0}"
                }
            },
            {
                "model_type": "note",
                "note": {
                    "liked": false,
                    "id": "645339cf0000000013005165",
                    "title": "今年的衣服是怎么了",
                    "abstract_show": "",
                    "desc": "他喵的，这两年的衣服是怎么了，去年满街的泡泡袖，穿上像个大猩猩，今年又满大街的吊带上衣吊带裙，胖人有罪么，买件衣服都难得",
                    "liked_count": 0,
                    "type": "normal",
                    "user": {
                        "nickname": "林黛玉倒拔垂杨柳",
                        "images": "https://sns-avatar-qc.xhscdn.com/avatar/63688b25e7f93ece534ed732.jpg?imageView2/2/w/80/format/jpg",
                        "userid": "622ccee90000000021024c69"
                    },
                    "tag_info": {},
                    "images_list": [
                        {
                            "fileid": "1000g0082ejs6j56ha0005ohcprkocj39vuugh4o",
                            "height": 1920,
                            "width": 1440,
                            "url": "http://sns-img-hw.xhscdn.com/1000g0082ejs6j56ha0005ohcprkocj39vuugh4o?imageView2/2/w/540/format/webp|imageMogr2/strip&redImage/frame/0",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs6j56ha0005ohcprkocj39vuugh4o?imageView2/2/w/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs6j56ha0005ohcprkocj39vuugh4o"
                        }
                    ],
                    "has_music": false,
                    "timestamp": 1683175887,
                    "last_update_time": 0,
                    "geo_info": {
                        "distance": "<100m"
                    },
                    "corner_tag_info": [
                        {
                            "location": 5,
                            "type": "publish_time",
                            "icon": "http://picasso-static.xiaohongshu.com/fe-platform/e9b67af62f67d9d6cfac936f96ad10a85fdb868e.png",
                            "text": "8分钟前",
                            "text_en": "8 mins ago"
                        }
                    ],
                    "advanced_widgets_groups": {
                        "groups": [
                            {
                                "mode": 1,
                                "fetch_types": [
                                    "note_next_step",
                                    "second_jump_bar",
                                    "cooperate_binds",
                                    "note_collection",
                                    "rec_next_infos",
                                    "image_stickers",
                                    "image_filters",
                                    "product_review",
                                    "related_search",
                                    "cooperate_comment_component",
                                    "image_goods_cards",
                                    "ads_goods_cards",
                                    "ads_comment_component",
                                    "goods_card_v2",
                                    "image_template",
                                    "red_map_tag",
                                    "share_open_user",
                                    "buyable_goods_card_v2",
                                    "ads_engage_bar"
                                ]
                            },
                            {
                                "mode": 0,
                                "fetch_types": [
                                    "vote_stickers",
                                    "bullet_comment_lead",
                                    "note_search_box",
                                    "interact_pk",
                                    "interact_vote"
                                ]
                            }
                        ]
                    },
                    "widgets_context": "{\"flags\":{},\"author_id\":\"622ccee90000000021024c69\",\"author_name\":\"林黛玉倒拔垂杨柳\",\"r_r_t\":0}"
                }
            },
            {
                "model_type": "note",
                "note": {
                    "liked": false,
                    "id": "645339be0000000011013c61",
                    "title": "母亲节快到了想送妈妈好看的衣服",
                    "abstract_show": "",
                    "desc": "#买衣服  #妈妈  #母亲节",
                    "liked_count": 0,
                    "type": "normal",
                    "user": {
                        "nickname": "没头脑",
                        "images": "https://sns-avatar-qc.xhscdn.com/avatar/64413f5a7cf83cd837e13356.jpg?imageView2/2/w/80/format/jpg",
                        "userid": "5c5afa97000000001a019348"
                    },
                    "tag_info": {},
                    "images_list": [
                        {
                            "fileid": "1000g0082ejs5gdggm06g5n2qvabmj4q8a2eoeq8",
                            "height": 1999,
                            "width": 2560,
                            "url": "http://sns-img-hw.xhscdn.com/1000g0082ejs5gdggm06g5n2qvabmj4q8a2eoeq8?imageView2/2/w/540/format/webp|imageMogr2/strip&redImage/frame/0",
                            "url_size_large": "http://sns-img-hw.xhscdn.com/1000g0082ejs5gdggm06g5n2qvabmj4q8a2eoeq8?imageView2/2/h/1080/format/webp",
                            "original": "",
                            "trace_id": "1000g0082ejs5gdggm06g5n2qvabmj4q8a2eoeq8"
                        }
                    ],
                    "has_music": false,
                    "timestamp": 1683175870,
                    "last_update_time": 0,
                    "geo_info": {
                        "distance": "<100m"
                    },
                    "corner_tag_info": [
                        {
                            "location": 5,
                            "type": "publish_time",
                            "icon": "http://picasso-static.xiaohongshu.com/fe-platform/e9b67af62f67d9d6cfac936f96ad10a85fdb868e.png",
                            "text": "8分钟前",
                            "text_en": "8 mins ago"
                        }
                    ],
                    "advanced_widgets_groups": {
                        "groups": [
                            {
                                "mode": 1,
                                "fetch_types": [
                                    "note_next_step",
                                    "second_jump_bar",
                                    "cooperate_binds",
                                    "note_collection",
                                    "rec_next_infos",
                                    "image_stickers",
                                    "image_filters",
                                    "product_review",
                                    "related_search",
                                    "cooperate_comment_component",
                                    "image_goods_cards",
                                    "ads_goods_cards",
                                    "ads_comment_component",
                                    "goods_card_v2",
                                    "image_template",
                                    "red_map_tag",
                                    "share_open_user",
                                    "buyable_goods_card_v2",
                                    "ads_engage_bar"
                                ]
                            },
                            {
                                "mode": 0,
                                "fetch_types": [
                                    "vote_stickers",
                                    "bullet_comment_lead",
                                    "note_search_box",
                                    "interact_pk",
                                    "interact_vote"
                                ]
                            }
                        ]
                    },
                    "widgets_context": "{\"flags\":{},\"author_id\":\"5c5afa97000000001a019348\",\"author_name\":\"没头脑\",\"r_r_t\":0}"
                }
            }
        ],
        "recommend_info": {
            "title": ""
        },
        "recommend_items": [],
        "query_debug_info": {
            "is_forbidden": false,
            "query_risk_level": "<UNSET>"
        },
        "label_image": {}
    }
}

```


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
- pageIndex 翻页参数，默认空， 根据结果返回的cursor传入作为下一页翻页参数

## 评论
```
/xhs/note/comments
```
### 参数:
- noteId
- startId 翻页参数，默认0，列表最后用户id作为下一页翻页参数

## 评论回复
```
/xhs/note/comment_reply
```
### 参数:
- noteId 笔记ID
- commentId 回复列表第一个targetCommentId 需从笔记评论接口获取
- startId 翻页参数，默认0，列表最后用户id作为下一页翻页参数


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


## 关注列表
```
/xhs/user/focus
```
### 参数:
- userId 用户id
- pageIndex 首次为空，翻页游标， 根据结果返回的cursor传入作为下一页翻页参数


## 粉丝列表
```
/xhs/user/fans
```
### 参数:
- userId 用户id
- pageIndex 首次为空，翻页游标， 根据结果返回的cursor传入作为下一页翻页参数


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
