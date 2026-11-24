# 베트남어 연습장 2

한국어 화자를 위한 베트남어 문형·단어 복습 웹 앱. 순수 HTML/CSS/JS 정적 사이트라 빌드 과정이 없습니다.

## 폰에서 쓰기

https://paulikim.github.io/vietnamese-practice-2/

- iPhone: Safari에서 링크 열기 → 공유 버튼 → "홈 화면에 추가"
- Android: Chrome에서 링크 열기 → 메뉴(⋮) → "홈 화면에 추가" 또는 "앱 설치"

## 로컬에서 확인

```sh
python3 -m http.server 8080
```

브라우저에서 http://localhost:8080 을 엽니다.

## 문제 추가·수정 후 재배포

1. `index.html`의 `W`(단어), `F`(빈칸), `S`(문장), `A`(대답) 배열만 수정합니다.
2. `sw.js`의 `CACHE` 버전 숫자를 올립니다. (안 올리면 이미 방문한 폰에 옛 버전이 남을 수 있음)
3. `git add . && git commit -m "문제 추가" && git push`
4. 1~3분 뒤 폰에서 새로고침합니다. 홈 화면 앱은 완전히 종료한 뒤 다시 엽니다.
