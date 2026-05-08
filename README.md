# 📱 Phone Girlfriend

> 충전기를 꽂거나 폰을 두드릴 때 반응하는 장난 앱

## 기능
- 🔌 충전기 연결/분리 감지 → 랜덤 사운드 재생
- 💥 손바닥 충격 감지 → 랜덤 사운드 재생
- 🌙 백그라운드 Wake Lock 지원
- 📲 PWA (홈 화면 추가 가능)

## 배포 방법 (GitHub Pages)

1. 이 폴더 전체를 GitHub 새 저장소에 push
   ```
   git init
   git add .
   git commit -m "init"
   git remote add origin https://github.com/YOUR_ID/phone-girlfriend.git
   git push -u origin main
   ```
2. 저장소 Settings → Pages → Source: **GitHub Actions** 선택
3. 자동으로 `https://YOUR_ID.github.io/phone-girlfriend` 배포 완료
4. 그 주소를 폰 Chrome에서 열면 가속도계 정상 작동

## 주의사항
- **HTTPS 필요**: 로컬 file://로 열면 가속도계 미작동
- **iOS**: 충전 감지 미지원 (충격 감지만 작동)
- **Android**: 충전 + 충격 감지 모두 작동
