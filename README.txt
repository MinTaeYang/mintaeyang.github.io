[Open Insight GitHub Pages 패치본]

반영 내용
1) 중복 URL 방지
 - privacy.html / terms.html 의 '홈' 링크: index.html -> /

2) SEO/공유 메타 추가
 - index.html / privacy.html / terms.html 에 canonical 추가
 - og:site_name, og:type, og:title, og:description, og:url 추가
 - twitter:card, theme-color 추가

3) sitemap.xml 개선(선택 권장)
 - 각 URL에 <lastmod>2026-01-16</lastmod> 추가

적용 방법
- 이 zip 안의 파일 4개를 리포지토리 루트에 그대로 덮어쓰기
  (index.html, privacy.html, terms.html, sitemap.xml)
- 커밋/푸시 후 GitHub Pages 반영 확인
- Search Console에서 3개 URL(홈/개인정보/약관) 'URL 검사 -> 색인 생성 요청'

주의
- 이후 페이지를 수정하면 sitemap.xml의 lastmod 날짜도 같이 업데이트 권장
