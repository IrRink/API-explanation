# content 개별 조회 API

## /api/boards/:num

### requset

- METHOD : GET
- parameter : num

---

### headers

- 'Content-Type': 'application/json'

### Request body

none

---

### Response

#### 성공

```
{
    'id' : 'number',
    'title : 'string',
    'sub_title' : 'string',
    'board_text' : 'string',
    'uptime' : 'string',
    'name': 'string'
}
```

#### 실패

```
{
    status: 500
    message: '게시물 조회 중 오류가 발생했습니다.'
}
```

```
{
    text: '게시물을 찾을 수 없습니다.'
}
```
