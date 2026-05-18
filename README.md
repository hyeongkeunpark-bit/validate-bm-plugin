# validate-bm

비즈니스 모델 가설을 빠르게 검증하는 Claude Code 플러그인.

제품을 만들기 전에 "이게 팔릴까?"를 확인합니다.

## 스킬 3개

| 스킬 | 하는 일 |
|------|---------|
| `/validate-hypothesis` | Lean Canvas → 검증 가능한 가설 문장 도출 |
| `/validate-landing` | 가설 기반 → 심리학 원칙이 적용된 랜딩페이지 HTML 생성 |
| `/validate-judge` | 트래픽 데이터 입력 → Go / Pivot / Kill 판정 |

## 설치

```bash
/plugin install validate-bm
```

## 사용 흐름

```
1. /validate-hypothesis  →  가설 문서 생성
2. /validate-landing     →  랜딩 HTML 생성 (직접 배포)
3. 광고 집행 + 데이터 수집
4. /validate-judge       →  판정
5. 반복
```

## 1사이클 소요

- 시간: 7~14일
- 비용: $100~500 (광고비)
- 인원: 1명
