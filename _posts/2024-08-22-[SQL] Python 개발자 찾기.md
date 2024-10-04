---
title:  "[프로그래머스_SQL] Python 개발자 찾기"
excerpt: "#programmers"

categories:
  - sql
tags:
  - [programmers, SQL, 코딩테스트]

toc: true
toc_sticky: true
 
date: 2024-08-22
last_modified_at: 2024-08-22
---

### 📜문제
-----
<https://school.programmers.co.kr/learn/courses/30/lessons/293258>  
![image](https://github.com/user-attachments/assets/3404f0ef-2f40-44e4-8e49-90a043013636)

### 📜정답
-----
```
    SELECT ID,EMAIL,FIRST_NAME,LAST_NAME FROM DEVELOPER_INFOS WHERE SKILL_1 ='Python' OR SKILL_2 ='Python' OR SKILL_3 ='Python' ORDER BY ID ASC
```

### 📜노트
