# 관리자 로그인 API

## /process/login/admin

### requset

- METHOD : POST
- parameter : none

---

### headers

'Content-Type': 'application/x-www-form-urlencoded'

### Request body

Example Value
```
{
	'email' : 'string',
	'password' : 'string',
	'isAdmin' : 'string',
};
```

---

### Response

#### 성공 // 201

```
{
  "message": "관리자 로그인 성공",
  "token": "your_access_token",
  "admin": {
    "id": 1,
    "name": "관리자 이름",
    "email": "admin@example.com"
  }
}

```

#### 실패 // 400

```
{
    'error': error.massage
}
```
