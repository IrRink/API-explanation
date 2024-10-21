# 로그아웃 API

## /process/logout

### requset

- METHOD : POST
- parameter : none

---

### headers

- 'Authorization': Bearer jwt.token.here


### Request body


없음

---

### Response

#### 성공 // 200

```
{
  'message': '로그아웃 성공' 
}
```

#### 실패 // 500

```
{
    'error': error.massage
}
```
