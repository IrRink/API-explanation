# 관리자 정보 조회 API

## /api/info/adminAndUserCount

### requset

- METHOD : GET
- parameter : none

---

### headers

없음

### Request body


없음

---

### Response

#### 성공 // 200

```
{
  "adminDate": "2024-01-01", 
  "userCount": 100 
}
```

#### 실패 // 500

```
{
  "error": "Internal Server Error"
}
```

