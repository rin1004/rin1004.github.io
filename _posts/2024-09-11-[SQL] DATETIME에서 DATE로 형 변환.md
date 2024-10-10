---
title:  "[프로그래머스_SQL] DATETIME에서 DATE로 형 변환"
excerpt: "#programmers"

categories:
  - sql
tags:
  - [programmers, SQL, 코딩테스트]

toc: true
toc_sticky: true
 
date: 2024-09-11
last_modified_at: 2024-09-11
---

### 📜문제
-----
> <https://school.programmers.co.kr/learn/courses/30/lessons/59414>  

![image](https://github.com/user-attachments/assets/b3fce921-aa69-4fd2-a9ef-9d14d8923490)

### 📜정답
-----
```
    SELECT ANIMAL_ID,NAME,DATE_FORMAT(DATETIME,'%Y-%m-%d')AS 날짜 FROM ANIMAL_INS 
    ORDER BY ANIMAL_ID ASC
```

  
### 📜노트
---
* **DATE_FORMAT(날짜,'변경할 형식')**
{: .notice--info}
날짜의 형식을 변경할 때 사용하는 함수이다.

