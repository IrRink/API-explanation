# 관리자 로그인 API

## /api/admin/login

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
  
    'admin' {
	'age':'',
	'created_date':'',
	'email':'',
	'name':'',
	'password':'',
	'role':'',
	},
    'message': '관리자 로그인 성공',
   'token' : '',
}

```

#### 실패 // 401

```
{
    'error': error.massage
}
```
