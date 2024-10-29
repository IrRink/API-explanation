# 관리자 회원가입 API

## /api/admin/signup

### requset

- METHOD : POST
- parameter : none

---

### headers

'Content-Type': 'application/json'

### Request body

Example Value

```
{
    "email": "string",
    "name": "string",
    "age": "string",
    "password": "string",
    "securityQuestion": "string",
    "securityAnswer": "string",
    "isAdmin": boolean
}
```

---

### Response

#### 성공 // 201

```
{
  'message': '어드민 등록 성공' 
}
```

#### 실패 // 400

```
{
    'error': error.massage
}
```
