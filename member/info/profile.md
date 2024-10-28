# 내 정보조회 API

## /api/info/auth

### requset

- METHOD : GET
- parameter : none

---

### headers

Authorization: Bearer YOUR_REFRESH_TOKEN

### Request body


없음

---

### Response

#### 성공 // 200

```
{
  "message": "사용자 정보 조회 성공",
  "user": {
    "email": "",
    "name": "",
    "age": ,
    "password": "",
    "role": "",
    "created_date": ""
  }
}
```

#### 실패 // 500
```
{
  "message": "사용자 정보 조회 중 오류가 발생했습니다."
}
```


