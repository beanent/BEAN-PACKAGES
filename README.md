# BEAN-PACKAGES

BEAN 앱(빈뮤즈 · 빈 스테이션 등)의 확장 패키지를 받는 곳입니다. 소스는 없습니다.

- 패키지 파일은 Releases 자산으로 둡니다. 자산 이름은 `<pkg_id>-<version>-<platform>.beanpkg` 입니다.
- 패키지 목록(카탈로그)은 `catalog` 릴리즈의 `catalog-<app>-<platform>.json` 입니다. 서명이 들어 있습니다.
- 썸네일은 `thumbs/<app>/` 아래에 있습니다(GitHub Pages 로 엽니다).

패키지는 BEAN 앱 안에서만 받고 씁니다. 앱이 묶음마다 해시와 서명을 확인하므로 고친 사본은 깔리지 않습니다.
유료 패키지는 라이선스가 있어야 쓸 수 있습니다. 라이선스는 https://beanent.com 에서 삽니다.

Extension packages for BEAN apps. Files only, no source. Packages are verified (SHA-256 + signature) by the app, and paid packages need a license.
