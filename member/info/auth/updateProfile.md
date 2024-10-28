# 내 정보수정 API

## /api/info/auth

### requset

- METHOD : PUT
- parameter : none

---

### headers

Authorization: Bearer YOUR_REFRESH_TOKEN

'Content-Type': 'application/json'

### Request body
explane : 빈값을 넣으면 이전 데이터와 동기화
```
{
  "email": string, 
  "name": string,
  "age": number,
  "password":"string",
}
```

없음

---

### Response

#### 성공 // 200

```
{
  "message": "사용자 정보가 성공적으로 수정되었습니다. 다시 로그인해주세요."
}
```
#### 실패//404

```
사용자를 찾을 수 없습니다.
```


#### 실패 // 500
```
{
  "message": "사용자 정보 수정 중 오류 발생"
}
```


