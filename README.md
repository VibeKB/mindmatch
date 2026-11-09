# 부장님과 이심전심 LIVE

사회자가 10문항을 순서대로 공개하고 참가자가 휴대전화로 투표하는 게임입니다.

## 웹주소
https://vibekb.github.io/mindmatch/

## 배포
GitHub Settings → Pages → Build and deployment → Source를 **GitHub Actions**로 지정하세요.
main 브랜치에 커밋하면 자동으로 Pages에 배포됩니다.

## 실시간 기능
Firebase Authentication의 Anonymous 로그인과 Cloud Firestore가 필요합니다.
웹앱 index.html의 FIREBASE_CONFIG를 설정하고 firestore.rules를 Firestore Rules에 게시해야 합니다.
Firebase 설정 전에는 실시간 게임이 동작하지 않습니다.

## 진행
관리자 게임 생성 → QR코드 공유 → 참가자 이름 입력 → 사회자가 문항 공개 → 투표 마감/집계 → 최종 순위 공개.
