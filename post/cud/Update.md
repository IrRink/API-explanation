# content 게시글 업데이트 API

## /board/update-post/:num

### requset

- METHOD : post
- parameter : num

---

### headers

'Content-Type': 'application/json'

### Request body

Example Value

```
{
    'title : 'string',
    'subtitle' : 'string',
    'board_text' : 'string'
}
```

---

### Response

#### 성공 // 201

```
{
    message: '게시물이 성공적으로 업데이트되었습니다!'
}
```

#### 실패 // 400

```
{
    message: '모든 필드를 입력해야 합니다.'
}
```

#### 실패 // 500

```
{
    message: '게시물 업데이트 중 오류가 발생했습니다.'
}
```
