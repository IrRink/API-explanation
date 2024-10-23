# content 전체 조회 API

## /posts

### requset

- METHOD : GET
- parameter : none

---

### headers

none

### Request body

없음

---

### Response

#### 성공 // 200

```
[
    {
    'num' : 'number',
    'title : 'string',
    'subTitle' : 'string',
    'boardText' : 'string',
    'uptime' : 'string',
    'writer': 'string'
    }, ...
]
```

#### 실패 // 500

```
{
    message: '게시물 조회 중 오류가 발생했습니다.'
}
```
