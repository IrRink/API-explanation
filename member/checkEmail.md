# 이메일 중복체크 API

## /api/user/checkEmail?email=

### requset

- METHOD : GET
- parameter : email

---

### headers

none

### Request body

none

---

### Response

#### 성공 // 200

```
{
  "exists": boolean
}
```

#### 실패 // 500

```
{
    'error': error.massage
}
```
