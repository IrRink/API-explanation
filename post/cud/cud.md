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

---


# content 게시글 업데이트 API

## /board/update-post

### requset

- METHOD : post
- parameter : none

---

### headers

'Content-Type': 'application/json'


### Request body
```
{
    'num' : 'number',
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

---


# content 게시글 삭제 API

## /board/delete

### requset

- METHOD : delete
- parameter : none

---

### headers

'Content-Type': 'application/json'


### Request body

```
{
    'num' : 'number'
}
```

---

### Response

#### 성공

```
{
    message: '게시물이 성공적으로 삭제되었습니다!'
}
```

#### 실패 // 500

```
{
    message: '게시물 삭제 중 오류가 발생했습니다.'
}
```


