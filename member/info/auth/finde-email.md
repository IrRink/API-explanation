# 이메일 찾기 API

## /api/info/forget

### requset

- METHOD : POST
- parameter : none

---

### headers

'Content-Type': 'application/json'

### Request body
explane : 빈값을 넣으면 이전 데이터와 동기화
```
{
    "name": "string",
    "age": "number",
    "securityQuestion": "string",
    "securityAnswer": "string"
}
```

없음

---

### Response

#### 성공 // 200

```
{
    "email": "user@example.com"
}
```
#### 실패//400

```
{
    "error": "입력된 정보와 일치하는 사용자가 없습니다."
}
```




