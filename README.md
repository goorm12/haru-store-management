# 하루상점 판매자·플랫폼 관리자 웹

Next.js + TypeScript + Tailwind CSS 기반 PC·모바일 반응형 웹입니다. 현재 기본 환경만 구성되어 있으며 실제 관리 기능은 구현 전입니다.

## 문서

[문서 안내](docs/README.md): 판매자·플랫폼 관리자 요구사항·명세, 공통 정책·용어, 공지·문의 정책.

## 개발

```sh
npm ci
npm run dev
npm run lint
npx tsc --noEmit
npm run build
npm start
```

## 브랜치

작업 브랜치는 develop에서 분기하고 PR 대상은 develop으로 지정합니다. 배포 병합은 develop → main으로 진행합니다.

## 프로젝트 구분

- 이 저장소: [haru-store-management](https://github.com/goorm12/haru-store-management), 판매자·플랫폼 관리자 PC·모바일 반응형 웹.
- 구매자 웹·Capacitor 앱: [haru-store-buyer](https://github.com/goorm12/haru-store-buyer).
- 공통 회원·예약 서버: [haru-store-backend](https://github.com/goorm12/haru-store-backend).

공통 정책은 `docs/common`, 판매자 구현 문서는 `docs/seller`, 플랫폼 관리자 구현 문서는 `docs/admin`에서 관리합니다. 판매자 권한과 플랫폼 관리자 권한은 구분합니다.
