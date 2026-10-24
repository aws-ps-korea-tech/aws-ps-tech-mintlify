# AWS Korea Public Sector SA Team Docs — Mintlify

BookStack(`aws-ps-tech.kr`) 마이그레이션 비교용. Mintlify(가장 노션스러운 UI, SaaS).

## 배포 방법 (연결 1회 필요)
Mintlify는 SaaS라 GitHub Pages처럼 push만으로 뜨지 않고, 대시보드에서 이 리포를 연결해야 합니다:
1. https://dashboard.mintlify.com 로그인 (GitHub으로)
2. **Add deployment → GitHub → `aws-ps-korea-tech/mintlify`** 연결
3. 연결 후 main push마다 자동 빌드·배포 → `https://<subdomain>.mintlify.app`

무료 플랜으로 비교 미리보기 가능. 결제·AWS 의존 없음.

## 구성
- 콘텐츠: `docs/` (.mdx)
- 네비게이션: `docs.json`
- 에이전트 접근: `/llms.txt` (Mintlify는 llms.txt/llms-full.txt 자동 생성도 지원)
