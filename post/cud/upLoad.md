# content 게시글 업로드 API

## /api/boards

### requset

- METHOD : post
- parameter : none

---

### headers

- 'Content-Type': 'application/json'
- 'Authorization': Bearer jwt.token.here

### Request body

```
{
    'title : 'string',
    'sub_title' : 'string',
    'board_text' : 'string'
}
```

---

### Response

#### 성공

```
{
    status: 201
    message: '게시물이 성공적으로 추가되었습니다!'
}
```

#### 실패

```
{
    status: 400
    message: '모든 필드를 입력해야 합니다.'
}
```

```
{
    status: 500
    message: '게시물 추가 중 오류가 발생했습니다.'
}
```
