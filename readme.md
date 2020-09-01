# 대림대학교 DB프로그래밍
---

## 1. 본 저장소 포크

포크한 자신 저장소를 복제

git clone https://github.com/자기아이디/daelim_2020-2.git

원본 저장소 등록
```
git remote add src https://github.com/infohojin/daelim_2020-2.git
```

## 2. 원본 저장소 가지고 와서 병합하기

```
git fetch src
git merge src/master
```

## 코드 작성 및 올리기
---

```
git add .
git commit -m "메시지 작성"
git push -u origin master
```

## 병합 요청하기
---
작업후 포크 저장소로 push, pullrequest 요청


