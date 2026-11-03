# 우리 집에 어울리는 향 찾기

양키캔들 라지자 캔들 무료 향 상담 랜딩페이지입니다. 정적 HTML이라 GitHub에 올린 뒤 Vercel에서 Import하면 바로 배포됩니다.

## 로컬에서 보기

폴더에서 정적 서버를 켠 뒤 `index.html`을 엽니다.

```bash
npx --yes serve .
```

## Vercel 배포

1. [Vercel](https://vercel.com)에 GitHub 계정으로 로그인합니다.
2. **Add New → Project**에서 이 저장소를 Import합니다.
3. Framework Preset은 **Other**, Root Directory는 기본값(`.`)으로 둡니다.
4. Deploy를 누르면 `index.html`이 사이트 홈으로 배포됩니다.

이후 `main`에 푸시하면 Vercel이 자동으로 다시 배포합니다.

## 배포 전에 바꿀 값

`index.html` 안의 플레이스홀더를 실제 주소로 바꿉니다.

- `[구글폼 URL]` — CTA 버튼
- `[개인정보 수집·이용 안내 URL]` — 푸터 링크
- 후기·제품 정보 등 `[확인 필요]` 문구
