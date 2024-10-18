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