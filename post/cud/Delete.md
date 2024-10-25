# content 게시글 삭제 API

## /api/boards/:num

### requset

- METHOD : delete
- parameter : num

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
    message: '게시물이 성공적으로 삭제되었습니다!'
}
```

#### 실패

```
{
    status: 500
    message: '게시물 삭제 중 오류가 발생했습니다.'
}
```
