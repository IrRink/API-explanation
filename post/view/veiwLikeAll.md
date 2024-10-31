# 내가 고른 좋아요 모음 API

## /api/likes/my-likes

### requset

- METHOD : GET
- parameter : none

---

### headers

- 'Content-Type': 'application/json'
- 'Authorization': Bearer jwt.token.here

### Request body

없음

---

### Response

#### 성공
explane : 만약 좋아요가 board_id가 있다면 게시물쪽의 내용이 나오고 댓글쪽은 null이 된다.
          반대로 좋아요가 comment_id가 있다면 댓글쪽의 내용이 나오고 게시물쪽은 null이 된다.
```
[
    {
    'id': 'number',
    'board_title': 'string',
    'board_sub_title': 'string',
    'board_uptime': 'string',
    'board_user_name': 'string',
    'comment_text': 'string',
    'comment_uptime': 'string',
    'comment_user_name': 'string'
  }, ...
]
```

#### 실패

```
{
    status: 500
    message: '좋아요한 항목 조회 중 오류가 발생했습니다.'
}
```
