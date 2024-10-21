# 관리자 정보 조회 API

## /process/adminAndUserCount

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

#### 성공 // 201

```
{
  "adminDate": "2024-01-01", 
  "userCount": 100 
}
```

#### 실패 // 400

```
{
  "error": "Internal Server Error"
}
```

