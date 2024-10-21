# 유저 회원가입 API

## /process/adduseroruser

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
	'adminEmail' : 'string',
	'adminName' : 'string',
	'adminAge' : 'string',
	'password' : 'string',
	'isAdmin' : 'string',
};
```

---

### Response

#### 성공 // 201

```
{
    'messsage' : '회원가입 성공'
}
```

#### 실패 // 400

```
{
    'error': error.massage
}
```
