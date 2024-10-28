# 임시비밀번호

## /api/info/auth

### requset

- METHOD : POST
- parameter : none

---

### headers

Content-Type: application/json

### Request body

```
{
  "email": "user@example.com"
}
```

---

### Response

#### 성공 // 200

```
{
  "message": "임시 비밀번호가 생성되었습니다.",
  "temporaryPassword": ""
}
```
#### 실패//400

```
{
  "error": "이메일 형식이 잘못되었습니다."
}
```


#### 실패//404

```
{
  "error": "사용자를 찾을 수 없습니다."
}
```



