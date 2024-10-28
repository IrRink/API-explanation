# 좋아요 추가및 취소 API

## /api/boards/:num

### requset

- METHOD : post
- parameter : num

---

### headers

- 'Content-Type': 'application/json'
- 'Authorization': Bearer jwt.token.here

### Request body

Example Value

```
{
    'target_id : 'number',
    'target_type' : 'string'
}
```

---

### Response

#### 성공

```
{
    message: '좋아요가 추가되었습니다.'
}
```
```
{
    message: '좋아요가 제거되었습니다.'
}
```

#### 실패

```
{
    status: 500
    message: '좋아요 처리 중 오류가 발생했습니다.'
}
```
