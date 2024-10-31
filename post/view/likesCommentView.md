# 좋아요 조회 API

## /api/likes/comments/:commentid

### requset

- METHOD : GET
- parameter : commentid

---

### headers

- 'Content-Type': 'application/json'

### Request body

없음

---

### Response

#### 성공

```
{
  'count': 'number'
}
```

#### 실패

```
{
  status: 500
  message: '좋아요 수 조회 중 오류가 발생했습니다.'
}
```
