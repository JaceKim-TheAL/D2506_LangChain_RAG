[practical_llm]: readme.md
[![적용기술](https://skillicons.dev/icons?i=ai,anaconda,py,vscode)][practical_llm]

### INDEX

<table>
  <tr align="center">
    <td width="150px"><a href="sect_01.md"> [LangChain]        </a></td>
    <td width="150px"><a href="sect_02.md"> [RAG]              </a></td>
    <td width="180px"><a href="sect_03.md"> [Multimodal RAG]   </a></td>
    <td width="150px"><a href="sect_04.md"> [Graph RAG]        </a></td>
    <td width="150px"><b href="sect_05.md"> [ReAct Agent]      </b></td>
    <td width="150px"><a href="sect_06.md"> [sLLM]             </a></td>
  </tr>
</table>

---               
## 5. ReAct 에이전트                       
- [ReAct Agent의 핵심 개념](#react-agent의-핵심-개념)
- [eAct Agent의 작동 방식](#react-agent의-작동-방식)
- [ReAct Agent의 활용 사례](#react-agent의-활용-사례)

---

ReAct Agent는 `Reasoning(추론)과 Acting(행동)을 결합`하여 문제를 해결하는 AI 에이전트<br/> 
<br/>
기존의 LLM(Large Language Model)이 단순히 질문에 답변을 제공하는 방식이었다면, <br/>
ReAct Agent는 추론을 통해 필요한 정보를 찾고, 행동을 수행하며, 최종적으로 문제를 해결하는 순환 구조를 가집니다.<br/>

---
### ReAct Agent의 핵심 개념

- **추론(Reasoning)**   – 모델이 문제를 분석하고, 해결 방법을 논리적으로 도출
- **행동(Acting)**      – 필요한 정보를 검색하거나 API를 호출하여 문제 해결을 위한 행동 수행
- **관찰(Observation)** – 행동의 결과를 분석하고, 다음 단계의 추론을 수행
- **순환 구조(Loop-based Reasoning & Acting)** – 문제 해결을 위해 여러 단계를 반복하며 최적의 답을 찾음

<br/>

[[TOP]](#index)

---
###  ReAct Agent의 작동 방식

ReAct Agent는 다음과 같은 순환 과정을 거칩니다: <br/>
- **Thought(추론)**     – 현재 상황을 분석하고, 필요한 정보를 찾음
- **Action(행동)**      – 검색, API 호출, 계산 등의 행동 수행
- **Observation(관찰)** – 행동의 결과를 분석하고, 다음 단계를 결정
- **Finish(완료)**      – 충분한 정보가 수집되면 최종 답변을 생성

<br/>

[[TOP]](#index)

---
### ReAct Agent의 활용 사례

| 분야    | 활용 사례 |
|--------|----------|
| **검색 기반 AI**      | 웹 검색을 통해 최신 정보를 가져와 응답 생성     |
| **자동화된 문제 해결** | API 호출을 통해 실시간 데이터 분석 및 처리      |
| **AI 챗봇**          | 고객 지원, 기술 상담 등에서 동적 문제 해결 가능  |

<br/>

[[TOP]](#index)

---