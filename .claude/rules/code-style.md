# 웹사이트 코딩 스타일

## HTML
- 들여쓰기: 2 spaces
- 언어 속성: `<html lang="ko">` 필수
- 뷰포트: `<meta name="viewport" content="width=device-width, initial-scale=1.0">` 필수
- 시맨틱 태그 사용 (`<section>`, `<article>`, `<nav>` 등)

## CSS
- 들여쓰기: 2 spaces
- CSS 변수 활용 권장 (`:root { --color-bg: #1a1209; }`)
- 테마 색상:
  - 배경: `#1a1209` (다크 골드)
  - 텍스트: `#f5ead8` (크림)
- 폰트: `'Segoe UI', 'Apple SD Gothic Neo', sans-serif`
- 반응형: 모바일 우선 (`min-width` 미디어 쿼리)

## JavaScript
- 들여쓰기: 2 spaces
- `const` / `let` 사용 (`var` 금지)
- 이벤트 리스너: `addEventListener` 방식 사용
- DOM 조작 시 `DOMContentLoaded` 이벤트 후 실행

## 이미지
- 기존 컷아웃 파일 우선 재사용
- `alt` 속성 한국어로 작성
- 배경 이미지: CSS `background-image` 또는 `<img>` absolute 포지션 방식
