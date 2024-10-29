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
  "email": "사용자 이메일",
  "securityQuestion": "사용자의 보안 질문",
  "securityAnswer": "사용자의 보안 답변"
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
  "error": "이메일, 보안 질문 또는 답변이 일치하지 않습니다."
}
```



