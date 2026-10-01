WIO 홈페이지 — 빌드 완료 파일

별도의 설치나 빌드 없이 업로드할 수 있는 홈페이지 파일입니다.

1. ZIP 파일을 다운로드하고 압축을 풉니다.
2. index.html, favicon.svg, assets 폴더, .nojekyll 파일을 GitHub 저장소 최상위에 업로드합니다.
   ZIP 파일 자체나 파일들을 감싼 폴더를 업로드하지 마세요.
3. 저장소 Settings → Pages로 이동합니다.
4. Source: Deploy from a branch
5. Branch: main (실제 업로드한 브랜치 선택)
6. Folder: /(root)
7. Save를 누릅니다.
8. 배포 완료 후 Settings → Pages의 Visit site로 홈페이지를 엽니다.

기존 파일을 교체한다면 index.html과 assets 폴더를 함께 교체하세요.
기존 Pages 설정이 /docs라면 반드시 /(root)로 변경하세요.
기존 Source가 GitHub Actions라면 Deploy from a branch로 변경하세요.

GitHub Pages 배포 완료까지 시간이 걸릴 수 있습니다.
국문/영문 전환과 모바일 메뉴가 포함되어 있습니다.
