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

---
ReAct Agent는 Reasoning(추론)과 Acting(행동)을 결합하여 문제를 해결하는 AI 에이전트입니다. 기존의 LLM(Large Language Model)이 단순히 질문에 답변을 제공하는 방식이었다면, ReAct Agent는 추론을 통해 필요한 정보를 찾고, 행동을 수행하며, 최종적으로 문제를 해결하는 순환 구조를 가집니다.
🔹 ReAct Agent의 핵심 개념
- 추론(Reasoning) – 모델이 문제를 분석하고, 해결 방법을 논리적으로 도출
- 행동(Acting) – 필요한 정보를 검색하거나 API를 호출하여 문제 해결을 위한 행동 수행
- 관찰(Observation) – 행동의 결과를 분석하고, 다음 단계의 추론을 수행
- 순환 구조(Loop-based Reasoning & Acting) – 문제 해결을 위해 여러 단계를 반복하며 최적의 답을 찾음

<br/>

[[TOP]](#index)

---