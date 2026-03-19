# 캠페인 시스템

캠페인 시스템 개요 문서 및 다이어그램입니다.

## 보기

- **로컬**: `docs/campaign-system-onepager.html` 파일을 브라우저로 열거나, `docs` 폴더에서 로컬 서버 실행 후 접속
  ```bash
  cd docs && python3 -m http.server 8080
  ```
  → http://localhost:8080/campaign-system-onepager.html

## GitHub Pages로 외부 공유

1. 이 저장소를 GitHub에 푸시합니다.  
   (`<사용자명>` 자리에는 **본인 GitHub 아이디**를 넣으세요. 예: `https://github.com/hong-gildong` 이면 `hong-gildong`)
   ```bash
   git add .
   git commit -m "Add campaign system docs"
   git remote add origin https://github.com/<사용자명>/campaign-system.git
   git push -u origin main
   ```

2. GitHub 저장소 **Settings** → **Pages** 로 이동합니다.

3. **Build and deployment** → **Source** 에서 **Deploy from a branch** 를 선택합니다.

4. **Branch** 를 `main` (또는 사용 중인 기본 브랜치), **Folder** 를 **/docs** 로 선택한 뒤 **Save** 합니다.

5. 몇 분 후 아래 주소로 접속할 수 있습니다.  
   **`<사용자명>`** = GitHub 로그인 아이디 (예: 아이디가 `myid`면 `https://myid.github.io/campaign-system/` …)
   - **개요 1페이지**: `https://<사용자명>.github.io/campaign-system/campaign-system-onepager.html`
   - **첫 화면(리다이렉트)**: `https://<사용자명>.github.io/campaign-system/`

공유할 때는 위 개요 1페이지 URL을 전달하면 됩니다.
