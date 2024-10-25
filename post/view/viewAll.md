# content 전체 조회 API

## /api/boards

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

#### 성공

```
[
    {
    'num' : 'number',
    'title : 'string',
    'sub_title' : 'string',
    'board_text' : 'string',
    'uptime' : 'string',
    'writer': 'string'
    }, ...
]
```

#### 실패

```
{
    status: 500
    message: '게시물 조회 중 오류가 발생했습니다.'
}
```
