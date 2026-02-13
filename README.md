# 🎭 Muse Family — Character Assets

AI 스킬 시스템에 사용되는 **Muse Family** 캐릭터 표정 에셋 저장소입니다.

## 👯‍♀️ 캐릭터 소개

| | 언니 — Muse (SkillsMuse) | 동생 — URLMuse |
|---|---|---|
| **서비스** | [skillsmuse.com](https://skillsmuse.com) | [urlmuse.com](https://urlmuse.com) |
| **역할** | AI 스킬 큐레이션 가이드 | AI URL 심층 분석 가이드 |
| **티셔츠** | 💙 라이트 블루 | 🩷 소프트 핑크 |
| **성격** | 똑똑하고 따뜻한 | 활발하고 호기심 넘치는 |

## 📁 구조

```
characters/
├── muse/                    # 언니: Muse (SkillsMuse)
│   ├── assets/              # 표정 이미지 12종
│   ├── design-sheet.md      # 캐릭터 디자인 가이드
│   └── prompts.md           # AI 생성 프롬프트 기록
└── urlmuse/                 # 동생: URLMuse 🆕
    ├── assets/              # 표정 이미지 12종
    └── design-sheet.md      # 캐릭터 디자인 가이드
templates/
└── SKILL_TEMPLATE.md        # Muse가 적용된 SKILL.md 템플릿
```

## 🖼️ 표정 12종 (양쪽 동일 구조)

| # | 카테고리 | 표정 | 파일명 |
|---|---------|------|--------|
| 1 | 기본 | 인사/경례 | `salute.png` |
| 2 | 기본 | 긍정/동의 | `thumbsup.png` |
| 3 | 기본 | 성공/축하 | `success.png` |
| 4 | 작업 중 | 고민/분석 | `thinking.png` |
| 5 | 작업 중 | 아이디어! | `idea.png` |
| 6 | 작업 중 | 코딩 중 | `typing.png` |
| 7 | 문제 상황 | 당황/에러 | `panic.png` |
| 8 | 문제 상황 | 화남/분발 | `angry.png` |
| 9 | 문제 상황 | 울음/억울 | `crying.png` |
| 10 | 휴식/기타 | 커피타임 | `coffee.png` |
| 11 | 휴식/기타 | 졸림/지침 | `sleepy.png` |
| 12 | 휴식/기타 | 신남/흥분 | `excited.png` |

## 🔗 이미지 URL 형식

```
# 언니 (SkillsMuse)
https://raw.githubusercontent.com/skillsmuse/characters/main/characters/muse/assets/{파일명}

# 동생 (URLMuse)
https://raw.githubusercontent.com/skillsmuse/characters/main/characters/urlmuse/assets/{파일명}
```

## 📜 License

© 2026 Muse Family (SkillsMuse + URLMuse). All rights reserved.
