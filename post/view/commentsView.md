# 댓글 전체 조회 API

## /api/comments/:boardId

### requset

- METHOD : GET
- parameter : boardId

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
    'id': 'number',
    'comment_text': 'string',
    'writer_name': 'string',
    'writer_email': 'string',
    'board_id': 'number',
    'time': 'string'
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
