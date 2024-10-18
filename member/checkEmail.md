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
	'email': 'string' // 확인하려는 이메일
};
```

---

### Response

#### 성공 // 201

```
{
  "exists": true// 이메일이 존재하면 true, 존재하지 않으면 false
}
```

#### 실패 // 400

```
{
    'error': error.massage
}
```
