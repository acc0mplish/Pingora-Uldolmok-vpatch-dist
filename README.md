# Pingora-Uldolmok-vpatch-dist

UVPB(Uldolmok Virtual-Patch Bundle) v1 공개 배포 좌석 — **서명 완료 아티팩트만** 게시된다.

- `releases/latest/download/uvpb-bundle.json` — 소비자 피드 안정 URL (UVPB envelope)
- 릴리스마다: envelope·receipt.json(key_id·sequence·sha256·provenance)·공지 노트
- 형식 스펙 공개 판본 (`spec/` — 머리글에 원천 커밋 표기·드리프트 게이트 관리)

이 리포의 호스팅 신뢰는 무의미하다 — 무결성은 Ed25519 서명 검증이 소유한다
(운영자 토폴로지 확정 2026-11-17: private 소스 리포 + 공개 dist, 설계 r3.2 D4).

게시물은 전부 Pingora-Uldolmok-vpatch-producer 리포 CI가 생성한다 — 이 리포에 직접 커밋하지 않는다.
