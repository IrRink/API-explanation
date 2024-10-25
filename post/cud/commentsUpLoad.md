# 댓글 업로드 API

## /api/comments/:boardId

### requset

- METHOD : post
- parameter : boardId

---

### headers

- 'Content-Type': 'application/json'
- 'Authorization': Bearer jwt.token.here

### Request body

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
    status: 201
    message: '댓글이 성공적으로 추가되었습니다!'
}
```

#### 실패

```
{
    status: 500
    message: '댓글 작성 중 오류가 발생했습니다.'
}
```

```
{
    text: '댓글 내용을 입력해야 합니다.'
}
```