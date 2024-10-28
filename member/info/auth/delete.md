# 회원삭제

## /api/info/auth

### requset

- METHOD : DELETE
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
  "message": "회원 정보가 성공적으로 삭제되었습니다.",
}
```
###실패//400

```
{
  "error": "이메일이 필요합니다."
}
```
###실패//403

```
{
  "error": "유효하지 않은 토큰입니다."
}
```

###실패//404

```
{
  "error": "삭제할 사용자를 찾을 수 없습니다."
}
```



