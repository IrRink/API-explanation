# content 전체 조회 API

## /blogbord

---

### requset

- METHOD : GET
- parameter : none

---

### header

- 없음

### Request body

Example value

### Response

##### 성공 // 200

```
[
    {
        'num' : 'number';
        'title : 'string';
        'subtitle' : 'string';
        'id': 'string';
        'uptime' : 'string';
        'bord_text' : 'string';
    }
]
```

##### 실패 // 500

{
message: '게시물 조회 중 오류가 발생했습니다.'
}
