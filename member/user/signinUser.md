# 유저 로그인 API

## /api/user/login

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

#### 성공 // 200

```
{
  'message': '유저 로그인 성공', token, user
}
```

#### 실패 // 401

```
{
    'error': error.massage
}
```
