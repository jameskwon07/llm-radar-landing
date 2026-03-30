# LLM Radar

**내 브랜드, AI 검색에서 보이고 있나요?**

LLM Radar는 Perplexity 같은 AI 검색 엔진에서 내 브랜드/서비스/블로그가 언급되는지 실시간으로 확인하는 도구입니다.

🔍 **무료로 확인하기 → [voidops.space/llm-radar/try-it](https://voidops.space/llm-radar/try-it/)**

---

## 무엇을 하는 서비스인가요?

대부분의 브랜드는 AI 검색에서 보이지 않습니다. 그리고 그 사실조차 모르고 있어요.

누군가 Perplexity에서 "이런 툴 추천해줘" 또는 "OO가 뭐야?"라고 물었을 때, 내 브랜드가 언급되고 있을까요? LLM Radar가 30초 안에 알려드립니다.

**작동 방식:**

1. URL 입력
2. LLM Radar가 브랜드/카테고리 관련 질문 자동 생성
3. Perplexity에 각 질문을 실시간으로 질의
4. 브랜드 언급 여부 + 실제 AI 응답 전문 제공

---

## 스캔 구조

LLM Radar는 3단계로 스캔합니다:

| 단계 | 유형 | 예시 |
|------|------|------|
| **브랜드 질문** | 브랜드명을 직접 포함한 질문 | "OO가 뭐야?" / "OO 써본 사람 있어?" |
| **카테고리 질문** | 브랜드명 없이 카테고리를 묻는 질문 | "AI 모니터링 툴 추천해줘" |
| **일반 질문** | 분야 일반 질문 | "AI 검색 시대에 브랜드 노출 전략" |

카테고리 질문에서 언급되는 것이 더 어렵고, 더 가치 있습니다. 내 브랜드를 모르는 사람에게 처음으로 노출되는 경로이기 때문입니다.

---

## 왜 필요한가요?

구글 SEO가 20년간 게임의 규칙이었습니다. 이제 AI 검색(Perplexity, ChatGPT, Gemini)이 사람들이 제품과 서비스를 발견하는 새로운 경로가 되고 있습니다.

규칙이 바뀌었습니다. 대부분의 브랜드는 아직 모르고 있어요.

LLM Radar는 혼자 사업하는 사람이 직접 만들고, 직접 쓰면서 개선하는 도구입니다.

---

## 기술 스택

- **Perplexity API** — 실시간 AI 검색 질의
- **Anthropic Claude** — 브랜드명 추출 및 질문 생성
- **Supabase** — 스캔 결과 저장
- **Vercel** — API 배포

---

## 링크

- 🌐 서비스: [voidops.space/llm-radar](https://voidops.space/llm-radar/)
- 🔍 무료 체험: [voidops.space/llm-radar/try-it](https://voidops.space/llm-radar/try-it/)
- 📝 빌드 로그: [codingbridge.blog](https://codingbridge.blog/2026/02/22/llm-radar-build-1/)
- 📬 문의: contact@voidops.space
