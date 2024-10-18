# 관리자 로그인 API

## /process/loginadmin

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
	'isAdmin' : 'boolean',
};
```

---

### Response

#### 성공 // 201

```
{
  'message': '관리자 로그인 성공', accessToken, refreshToken, user
}
```

#### 실패 // 400

```
{
    'error': error.massage
}
```
