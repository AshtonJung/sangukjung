# sangukjung 주소로 배포하기

## 1단계. 도메인 구입 (약 2만 원/년)
1. Cloudflare Registrar, Namecheap, 가비아 중 한 곳에서 `sangukjung.com`을 검색합니다.
2. 이미 팔렸다면 `sangukjung.net`, `.me`, `.kr` 등을 확인합니다.

## 2단계. 무료 호스팅 (Cloudflare Pages 기준)
1. cloudflare.com 가입 → Workers & Pages → Create → Pages → "Upload assets"
2. 이 폴더(`My Homepage`)를 통째로 올립니다. (index.html + assets 폴더)
3. 배포가 끝나면 `xxxx.pages.dev` 임시 주소가 생깁니다. 먼저 이 주소로 확인합니다.

## 3단계. 도메인 연결
1. Pages 프로젝트 → Custom domains → `sangukjung.com` 추가
2. 안내대로 DNS를 설정합니다. (Cloudflare에서 도메인을 샀다면 자동 연결)
3. 몇 분~몇 시간 뒤 https://sangukjung.com 으로 접속됩니다.

## 대안: GitHub Pages (무료 주소 sangukjung.github.io)
1. github.com에서 `sangukjung` 계정 생성
2. 저장소 `sangukjung.github.io` 생성 후 이 폴더의 파일을 업로드
3. Settings → Pages 에서 main 브랜치를 선택합니다.
