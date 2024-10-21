# 이메일 중복체크 API

## /process/checkEmail?email=

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

#### 성공 // 201

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
