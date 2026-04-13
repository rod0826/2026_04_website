# website_2604 — 골든 리트리버 웹사이트

## 프로젝트 개요
골든 리트리버 테마의 인터랙티브 웹사이트. 애니메이션과 이미지 컷아웃을 활용한 시각적 페이지.

## 파일 구조
```
index.html          # 메인 페이지
animation.html      # 애니메이션 페이지
dog_cutout.png      # 강아지 컷아웃 이미지
level2_cutout.png / level2.jpeg
level3_cutout.png / level3.jpeg
1234.png
```

## 기술 스택
- 순수 HTML/CSS/JS (프레임워크 없음)
- 언어: `lang="ko"`, 한국어 콘텐츠
- 폰트: 'Segoe UI', 'Apple SD Gothic Neo'
- 테마 색상: 다크 골드 (`#1a1209` 배경, `#f5ead8` 텍스트)

## 디자인 원칙
- 모바일 우선 반응형 (`viewport` 메타 설정 필수)
- Hero 섹션: 뷰포트 전체 높이 (`100vh`)
- 이미지는 기존 컷아웃 파일 재사용 우선

## 주의
- 외부 라이브러리 추가 시 CDN 링크 방식 사용
- 이미지 파일 추가 시 파일명을 CLAUDE.md에 기록
