# 유저 로그인 API

## /process/login

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
	'adminId' : 'string',
	'password' : 'string',
	'isAdmin' : 'boolean',
};
```

---

### Response

#### 성공 // 201

```
{
  'message': '유저 로그인 성공', accessToken, refreshToken, user
}
```

#### 실패 // 400

```
{
    'error': error.massage
}
```
