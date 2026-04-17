# benchmark-skill

> 🇺🇸 [English README](./README.md)

**짧고 맥락 있는 벤치마킹 엔진. 5블록(정의+성공실패·구조·WHY·차용포인트·백본1줄)로 수렴. SINGLE·MULTI·METAPHOR 3모드. 4대 스코프(조직/제품/캠페인/정책).**

## 사전 요구

- **Claude Cowork 또는 Claude Code** 환경
- *(선택)* Obsidian 볼트 — `.md` 산출물 저장용

## 목표

기존 벤치마킹은 내용이 길어 안 읽히거나(덤프), 기능 나열에 그쳐 얕다. 본 스킬은 HBR식 A4 반쪽 밀도로 압축 — 백본 1줄 + 확신도 태그로 기획에 즉시 투입 가능한 사례를 생성한다.

## 사용 시점 & 방법

기획 시작 전, 레퍼런스 탐색시, 타 도메인 메커니즘을 빌릴 때.

- **SINGLE** — 하나 깊게 (A4 반쪽)
- **MULTI** — 2~5개 비교 + 비교축표 + 통합 차용포인트
- **METAPHOR** — 타 도메인 은유 + 매핑 + 충돌지점

## 사용 사례

| 상황 | 프롬프트 | 동작 |
|---|---|---|
| 하나 깊게 | `"HBR 벤치마킹해줘"` | SINGLE — 5블록 + 백본 + 확신도 |
| N개 비교 | `"HBR·Substack·Medium 비교"` | MULTI — 비교축표 + 통합 차용포인트 |
| 크로스 도메인 | `"은행을 스타벅스처럼"` | METAPHOR — 매핑 + 충돌지점 + 차용가능/불가 판정 |

## 주요 기능

- **3모드** — SINGLE / MULTI / METAPHOR 자동 판정
- **4스코프** — 조직·서비스·BM / 제품·기능·UX / 캠페인·마케팅·카피 / 정책·제도·사회현상
- **5블록 고정 템플릿** — 정의+성공실패 / 구조 / WHY / 차용포인트 / 백본1줄
- **확신도+근거 필수** — 백본마다 높음90/보통70/낮음50/모름30 태그 (UP v37 준수)
- **WHY = 인간메커니즘** — 12개 패턴(신분재·리추얼·정체성 표현 등). 기능 나열 금지
- **은유 카탈로그** — 7카테고리 × 25+ 타도메인 소스

## 연동 스킬

- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — 18축 BM 패턴 라이브러리 (BM 축 하류 소비)
- **[research-frame](https://github.com/jasonnamii/research-frame)** — 근거 부족시 호출
- **[paper-engine](https://github.com/jasonnamii/paper-engine)** — `.md` 산출 구조·QC cascade
- **[hit-skill](https://github.com/jasonnamii/hit-skill)** — WHY 블록 인간메커니즘 라이브러리
- **[copywriting-engine](https://github.com/jasonnamii/copywriting-engine)** — 스코프C(캠페인) 카피 진단 하류

## 설치

```bash
git clone https://github.com/jasonnamii/benchmark-skill.git ~/.claude/skills/benchmark-skill
```

## 업데이트

```bash
cd ~/.claude/skills/benchmark-skill && git pull
```

`~/.claude/skills/`에 배치된 스킬은 Claude Code 및 Cowork 세션에서 자동으로 사용됩니다.

## Cowork Skills

25개 이상의 커스텀 스킬 중 하나. 전체 카탈로그: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## 라이선스

MIT License — 자유롭게 사용·수정·공유 가능합니다.
