# content 개별 조회 API

## /api/board/:num

### requset

- METHOD : GET
- parameter : num

---

### headers

none

### Request body

none

---

### Response

#### 성공 // 200

```
{
    'num' : 'number',
    'title : 'string',
    'sub_title' : 'string',
    'board_text' : 'string',
    'uptime' : 'string',
    'writer': 'string'
}
```

#### 실패 // 404

```
{
    message: '게시물을 찾을 수 없습니다.'
}
```

#### 실패 // 500

```
{
    message: '게시물 조회 중 오류가 발생했습니다.'
}
```
