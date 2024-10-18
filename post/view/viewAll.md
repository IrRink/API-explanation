# content 전체 조회 API

## /board/blogbaord

### requset

- METHOD : GET
- parameter : none

---

### headers

'Content-Type': 'application/json'

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
        'subtitle' : 'string',
        'id': 'string',
        'uptime' : 'string',
        'board_text' : 'string'
    }, ...
]
```

#### 실패 // 500

```
{
    message: '게시물 조회 중 오류가 발생했습니다.'
}
```
