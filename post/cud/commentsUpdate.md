# 댓글 수정 API

## /api/comments/:commentId

### requset

- METHOD : put
- parameter : commentId

---

### headers

- 'Content-Type': 'application/json'
- 'Authorization': Bearer jwt.token.here

### Request body

Example Value

```
{
    'comment_text : 'string'
}
```

---

### Response

#### 성공

```
{
    message: '댓글이 성공적으로 수정되었습니다!'
}
```

#### 실패

```
{
    status: 500
    message: '댓글 수정 중 오류가 발생했습니다.'
}
```

```
{
    text: '본인의 댓글만 수정할 수 있습니다.'
}
```
