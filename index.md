---
layout: default
title: YouTube Comment Manager
---
# YouTube Comment Manager

개인 채널 운영자가 본인 소유 YouTube 채널의 댓글을 검토하기 위해 사용하는 비공식 개인용 도구입니다. Google 또는 YouTube가 제공하거나 보증하는 제품이 아닙니다. 다른 사용자의 가입이나 채널 연결은 받지 않습니다.

This is an unofficial, owner-only tool for reviewing comments on the operator's own YouTube channel. It is not a Google or YouTube product and is not offered for public registration.

## 기능과 필요한 권한

공식 YouTube Data API로 게시 댓글과 검토 보류 댓글, 답글을 조회합니다. 댓글과 일부 이전 댓글 맥락을 AI API로 분류한 뒤, 운영자가 정한 정책에 해당하는 경우 댓글 검토 상태 변경과 작성자의 추가 댓글 자동 거부를 요청합니다. AI 판단에는 오류가 있을 수 있으며 API가 모든 보류 답글을 반환한다고 보장하지 않습니다.

OAuth 요청 범위는 `https://www.googleapis.com/auth/youtube.force-ssl`입니다. 이는 댓글 전용 권한이 아니며 YouTube 동영상·평가·댓글·자막의 조회·수정·영구 삭제까지 포함하는 넓은 권한입니다. 현재 프로그램은 채널 확인, 댓글 조회, 댓글 검토 상태 변경에만 사용하도록 구현되어 있습니다. Google 계정 비밀번호를 수집하거나 저장하지 않습니다.

## 개인정보와 이용 안내

- [개인정보 처리방침 / Privacy Policy](privacy.html)
- [이용 안내 / Terms](terms.html)
- [YouTube 서비스 약관](https://www.youtube.com/t/terms)
- [Google 개인정보처리방침](https://policies.google.com/privacy)

이 공개 사이트에는 댓글 원문, 인증 토큰, API 키 또는 검수 프로그램의 소스 코드를 게시하지 않습니다.

운영: GitHub 계정 vonliv1269. 이 사이트는 도구의 안내 문서만 제공합니다. 업데이트: 2026-10-26.
