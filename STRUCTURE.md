# STRUCTURE · fournil-sample

```
fournil-sample/
├─ index.html              단일 파일 (CSS·JS 인라인)
├─ wrangler.toml           name = fournil-sample
├─ .assetsignore           img/·문서·png 로고 배포 제외
├─ fn-gothic.woff2         영문 헤딩 (League Gothic, 라틴만)
├─ fn-pretendard.woff2     한글 · 본문 (Pretendard 400–800, 사용 글자만 → 글자 추가 시 재생성)
├─ fn-logo.webp            로고 먹색 (헤더)
├─ fn-logo-light.webp      로고 밝은색 (검정 푸터)
├─ fn-eggtart.webp         히어로 포스터 · 시그니처
├─ fn-*.webp               bake · menu · expect 사진 9장
├─ favicon.png / og-fournil.jpg
├─ img/                    다올 제공 원본 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `.band`(검정 마키) → `#hello` → `#bake`(검정) → `#menu` → `#expect` → `#philosophy`(검정) → `#store` → `#visit` → 검정 푸터.

## 영업시간 수정 (3곳)
`#visit` 시간 줄 · 푸터 · head JSON-LD `openingHoursSpecification`.

## 링크
네이버 플레이스 1976738864 · 스마트스토어 smartstore.naver.com/fournil · 카카오 pf.kakao.com/_hEdXG · 인스타그램. 지도는 구글 임베드만.

## 색 규칙
배경 `--bg`는 로고 배경색 그대로. 강조색 없이 먹 · 검정 면으로만 대비.

## 폰트 재생성
`pyftsubset … --name-IDs='*' --name-languages='*' --name-legacy` (LESSONS §24). Pretendard는 instancer로 400–800 자른 뒤 서브셋.
