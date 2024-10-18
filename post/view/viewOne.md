# content 개별 조회 API

## /board/blogbaord/:num

### requset

- METHOD : GET
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

#### 성공 // 200

```
{
    'num' : 'number',
    'title : 'string',
    'subtitle' : 'string',
    'id': 'string',
    'uptime' : 'string',
    'bord_text' : 'string'
}
```

#### 실패 // 404

```
{
    message: '게시물을 찾을 수 없습니다.'
}
```

#### 실패 // 500

```
{
    message: '게시물 조회 중 오류가 발생했습니다.'
}
```