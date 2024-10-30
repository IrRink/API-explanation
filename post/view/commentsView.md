# 댓글 전체 조회 API

## /api/comments/:boardId

### requset

- METHOD : GET
- parameter : boardId

---

### headers

- 'Content-Type': 'application/json'

### Request body

없음

---

### Response

#### 성공

```
[
  {
    'id': 'number',
    'comment_text': 'string',
    'user_id': 'number',
    'uptime': 'string',
    'name': 'string',
  }, ...
]
```

#### 실패

```
{
  status: 500
  message: '댓글 조회 중 오류가 발생했습니다.'
}
```
