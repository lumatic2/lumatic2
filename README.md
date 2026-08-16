# 전유성 / Yusung Jun

경영학을 전공하며 익힌 사업의 언어로 현장 문제를 읽고, AI-Native 엔지니어링으로 배포까지 직접 닫습니다. 코딩 에이전트로 명세·구현·검증을 잇고, 결과를 믿을 수 있는지 판정하는 평가 구조까지 함께 설계합니다. 관심사는 도메인 지식, 근거 인용, 평가 하네스, 에이전트 운영 방식입니다.

크래프톤 × CJ올리브영 AI Native 해커톤 FDE 트랙 본선 top 6 (약 25명, 2026.07).

I read problems in the language of the business — trained as a management major — and close them all the way to deployment with AI-native engineering: coding agents to connect spec, implementation, and verification, plus the evaluation structure that decides whether the result can be trusted. Finalist, top 6 of ~25 in the FDE track at the KRAFTON × CJ Olive Young AI Native Hackathon (2026.07).

[Portfolio](https://portfolio.askewly.com/) · [LinkedIn](https://www.linkedin.com/in/yusung-jun-b09952279/) · `yusung8307@gmail.com`

## 대표 작업 / Selected Work

1. **harness-engineering**
   AI 에이전트를 한 번 실행하는 데 필요한 context, guardrail, validator, judge, retry, evidence ledger를 실험하고 문서화한 레포입니다. 프롬프트가 아니라 모델 호출 전후의 운영 시스템을 다룹니다.
   An engineering notebook for agent harnesses: context assembly, guardrails, validators, judges, retries, and evidence ledgers around model calls.

2. **[physical-ai](https://robotics.askewly.com)**
   VLA 평가, action representation benchmark, 브라우저 기반 로봇 policy simulation을 한 레포에 묶은 피지컬 AI 학습/실험 기록입니다. [robotics.askewly.com](https://robotics.askewly.com)에서 일부 결과를 직접 볼 수 있습니다.
   A physical AI lab covering VLA evaluation, action-representation benchmarks, and browser-based robot policy simulations with a live surface at [robotics.askewly.com](https://robotics.askewly.com).

3. **[luma3-portfolio](https://portfolio.askewly.com/)**
   제 작업을 외부에서 볼 수 있게 정리하는 포트폴리오 허브입니다. 프로젝트를 단순 나열하지 않고 문제, 설계, 검증, 결과가 드러나도록 구성합니다.
   My public portfolio hub, organized around problems, design choices, verification, and outcomes rather than a flat project list.

4. **[korean-tax-accounting-ax-benchmark](https://tax-benchmark.askewly.com/)**
   한국 회계·세무 AI가 그럴듯하게 말하는지보다 실무 검증을 통과할 수 있는지를 평가하는 벤치마크입니다. 공개 샘플, private holdout, 근거 인용 채점, agent tool-use 평가, [리더보드](https://tax-benchmark.askewly.com/)를 분리해 운영합니다. 근거 검색 도구인 [law-mcp](https://github.com/lumatic2/law-mcp)를 공개해 회계·세무 근거 검색과 도구화 경계를 보여줍니다.
   A benchmark for Korean accounting and tax AI, separating public samples from private holdouts and checking grounding, calculations, citations, agent tool use, and [leaderboard](https://tax-benchmark.askewly.com/) presentation. A related public repo is [law-mcp](https://github.com/lumatic2/law-mcp), a grounding-search MCP server.

5. **[prawn-public](https://prawn.askewly.com/)**
   제조·ERP 업무 흐름을 AI tool-use와 연결하는 Prawn의 공개 mirror입니다. 실제 배포는 private canonical repo에서 운영하고, 공개 mirror에서는 코드, 아키텍처, 스키마, 검증 경계와 [live demo](https://prawn.askewly.com/)를 볼 수 있습니다.
   A sanitized public mirror of Prawn, a manufacturing ERP workspace connecting accounting, inventory, transactions, approvals, and AI tool-use. Production runs from the private canonical repo; this mirror exposes code, architecture, schema, verification boundaries, and the [live demo](https://prawn.askewly.com/).

6. **[ui-dictionary](https://ui.askewly.com/)**
   "깔끔하게", "팝업처럼" 같은 모호한 UI 요청을 card, modal, drawer, toast, data table 같은 구체적 컴포넌트 언어로 바꾸는 UI vocabulary 사이트입니다.
   A UI vocabulary site that turns vague interface requests into concrete component language for designers and AI coding agents.

## 작업 방식 / How I Work

- 도메인 문서와 공식 근거를 먼저 고정하고, 모델 답변은 그 근거에 묶어 검증합니다.  
  I anchor systems in domain sources first, then test whether model outputs stay grounded.
- README보다 먼저 공개/비공개 경계, secret scan, 데이터 권리, 재현 가능한 검증 명령을 확인합니다.  
  Before polishing README files, I check visibility boundaries, secret scans, data rights, and reproducible verification commands.
- 좋은 데모보다 실패를 잡는 하네스, 리더보드, 로그, 회귀 테스트를 더 중요하게 봅니다.  
  I care less about a clean demo and more about harnesses, leaderboards, logs, and regression checks that catch failures.
