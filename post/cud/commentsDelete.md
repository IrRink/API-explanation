# 댓글 삭제 API

## /api/comments/:commentId

### requset

- METHOD : delete
- parameter : commentId

---

### headers

- 'Content-Type': 'application/json'
- 'Authorization': Bearer jwt.token.here

### Request body

none

---

### Response

#### 성공

```
{
    message: '댓글이 성공적으로 삭제되었습니다!'
}
```

#### 실패 // 500

```
{
    message: '댓글 삭제 중 오류가 발생했습니다.'
}
```
