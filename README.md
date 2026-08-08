# Family Asset OS Web

GitHub Pages용 대시보드 초안입니다.

## 연결 방법
1. Family Asset OS - Master Data Google Sheet 열기
2. 확장 프로그램 → Apps Script
3. `google_apps_script.gs` 내용을 붙여넣고 저장
4. 배포 → 새 배포 → 웹 앱
5. 생성된 Web App URL 복사
6. `config.js`의 `API_URL`에 붙여넣기
7. GitHub 새 저장소를 만든 뒤 이 폴더 파일 업로드
8. Settings → Pages → Deploy from a branch → main / root

API URL이 비어 있으면 현재 프로젝트의 DEMO 데이터가 표시됩니다.

주의: 자산 데이터는 민감합니다. GitHub Pages 공개 저장소에는 실제 자산값을 코드에 직접 넣지 마세요.
