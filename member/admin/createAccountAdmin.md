# 관리자 회원가입 API

## /process/adduseroramdin

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
  'message': '어드민 등록 성공' 
}
```

#### 실패 // 400

```
{
    'error': error.massage
}
```
