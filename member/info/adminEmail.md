# 관리자 이메일 API

## /process/adminEmail

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
  "email": "admin@example.com"
}
```

#### 실패 // 400

```
{
  "error": "관리자 이름을 가져오는 중 오류 발생"
}
```