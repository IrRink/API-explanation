# 토큰만료 검증 API

## /process/refresh-token

### requset

- METHOD : POST
- parameter : none

---

### headers

Authorization: Bearer YOUR_REFRESH_TOKEN

### Request body

```
{
    "token": "YOUR_REFRESH_TOKEN"
}
```
---

### Response

#### 성공 // 200

```
{
    "accessToken": "NEW_ACCESS_TOKEN"
}

```

#### 실패 // 401

```
{
    "error": "Refresh Token이 필요합니다."
}
```

#### 실패 // 403

```
{
    "error": "Refresh Token이 유효하지 않습니다."
}
```

