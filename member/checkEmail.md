# 이메일 중복체크 API

## /process/checkEmail

### requset

- METHOD : GET
- parameter : none

---

### headers

'Content-Type': 'application/json'

### Request body

Example Value

```
{
	'email': 'string'
};
```

---

### Response

#### 성공 // 201

```
{
  "exists": true
}
```

#### 실패 // 400

```
{
    'error': error.massage
}
```
