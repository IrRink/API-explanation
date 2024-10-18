# content 게시글 업로드 API

## /board/add-post

### requset

- METHOD : post
- parameter : none

---

### headers

'Content-Type': 'application/json'


### Request body

```
{
    'title : 'string',
    'subtitle' : 'string',
    'bord_text' : 'string'
}
```

---

### Response

#### 성공 // 201

```
{
    message: '게시물이 성공적으로 추가되었습니다!'
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
    message: '게시물 추가 중 오류가 발생했습니다.'
}
```
