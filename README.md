# 전유성 / Yusung Jun

AI가 실제 업무와 제품 안에서 믿고 돌아가게 만드는 구조를 만듭니다. 관심사는 도메인 지식, 근거 인용, 평가 하네스, 에이전트 운영 방식입니다. 최근에는 한국 회계·세무 AX, agent harness, 포트폴리오/제품 공개 표면을 함께 정리하고 있습니다.

I build the operating structure around AI systems: domain grounding, citation discipline, evaluation harnesses, and agent workflows that can be inspected and improved. My recent work centers on Korean accounting/tax AX, agent harness engineering, and public product surfaces.

[Portfolio](https://portfolio.askewly.com/) · [LinkedIn](https://www.linkedin.com/in/yusung-jun-b09952279/) · `yusung8307@gmail.com`

## 대표 작업 / Selected Work

1. **[harness-engineering](https://github.com/lumatic2/harness-engineering)**  
   AI 에이전트를 한 번 실행하는 데 필요한 context, guardrail, validator, judge, retry, evidence ledger를 실험하고 문서화한 레포입니다. 프롬프트가 아니라 모델 호출 전후의 운영 시스템을 다룹니다.  
   An engineering notebook for agent harnesses: context assembly, guardrails, validators, judges, retries, and evidence ledgers around model calls.

2. **[luma3-portfolio](https://github.com/lumatic2/luma3-portfolio)**  
   제 작업을 외부에서 볼 수 있게 정리하는 포트폴리오 허브입니다. 프로젝트를 단순 나열하지 않고 문제, 설계, 검증, 결과가 드러나도록 구성합니다.  
   My public portfolio hub, organized around problems, design choices, verification, and outcomes rather than a flat project list.

3. **[korean-tax-accounting-ax-benchmark](https://github.com/lumatic2/korean-tax-accounting-ax-benchmark)**  
   한국 회계·세무 AI가 그럴듯하게 말하는지보다 실무 검증을 통과할 수 있는지를 평가하는 벤치마크입니다. 공개 샘플, private holdout, 근거 인용 채점, agent tool-use 평가, [리더보드](https://tax-benchmark.askewly.com/)를 분리해 운영합니다.  
   A benchmark for Korean accounting and tax AI, separating public samples from private holdouts and checking grounding, calculations, citations, agent tool use, and [leaderboard](https://tax-benchmark.askewly.com/) presentation.

4. **[prawn-public](https://github.com/lumatic2/prawn-public)**  
   제조·ERP 업무 흐름을 AI tool-use와 연결하는 Prawn의 공개 mirror입니다. 실제 배포는 private canonical repo에서 운영하고, 공개 mirror에서는 코드, 아키텍처, 스키마, 검증 경계와 [live demo](https://prawn.askewly.com/)를 볼 수 있습니다.  
   A sanitized public mirror of Prawn, a manufacturing ERP workspace connecting accounting, inventory, transactions, approvals, and AI tool-use. Production runs from the private canonical repo; this mirror exposes code, architecture, schema, verification boundaries, and the [live demo](https://prawn.askewly.com/).

5. **[ui-dictionary](https://github.com/lumatic2/ui-dictionary)**  
   "깔끔하게", "팝업처럼" 같은 모호한 UI 요청을 card, modal, drawer, toast, data table 같은 구체적 컴포넌트 언어로 바꾸는 UI vocabulary 사이트입니다.  
   A UI vocabulary site that turns vague interface requests into concrete component language for designers and AI coding agents.

## 작업 방식 / How I Work

- 도메인 문서와 공식 근거를 먼저 고정하고, 모델 답변은 그 근거에 묶어 검증합니다.  
  I anchor systems in domain sources first, then test whether model outputs stay grounded.
- README보다 먼저 공개/비공개 경계, secret scan, 데이터 권리, 재현 가능한 검증 명령을 확인합니다.  
  Before polishing README files, I check visibility boundaries, secret scans, data rights, and reproducible verification commands.
- 좋은 데모보다 실패를 잡는 하네스, 리더보드, 로그, 회귀 테스트를 더 중요하게 봅니다.  
  I care less about a clean demo and more about harnesses, leaderboards, logs, and regression checks that catch failures.
