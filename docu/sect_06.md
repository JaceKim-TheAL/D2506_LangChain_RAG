[practical_llm]: readme.md
[![적용기술](https://skillicons.dev/icons?i=ai,anaconda,py,vscode)][practical_llm]

### INDEX

<table>
  <tr align="center">
    <td width="150px"><a href="sect_01.md"> [LangChain]        </a></td>
    <td width="150px"><a href="sect_02.md"> [RAG]              </a></td>
    <td width="180px"><a href="sect_03.md"> [Multimodal RAG]   </a></td>
    <td width="150px"><a href="sect_04.md"> [Graph RAG]        </a></td>
    <td width="150px"><a href="sect_05.md"> [ReAct Agent]      </a></td>
    <td width="150px"><b href="sect_06.md"> [sLLM]             </b></td>
  </tr>
</table>

---
## 6. sLLM                               

---
**sLLM(Small Large Language Model)**은 대규모 언어 모델(LLM)의 `성능을 유지하면서도 경량화된 AI 모델`을 의미 <br/>
기존 LLM은 수십억 개 이상의 파라미터를 사용하여 강력한 성능을 제공하지만, sLLM은 모델 크기를 줄이면서도 높은 성능을 유지하도록 설계되었습니다.<br/>
<br/>

---
### sLLM의 주요 특징

- **경량화된 모델 크기** – LLM보다 작은 용량으로도 높은 성능 유지
- **빠른 연산 속도** – 적은 연산 자원으로도 AI 모델을 원활하게 실행 가능
- **데이터 보안 강화** – 내부 시스템에서 실행 가능하여 기업 데이터 보호
- **비용 절감** – 대형 클라우드 인프라 없이도 효율적으로 운영 가능
<br/>

[[TOP]](#index)

---
### sLLM / LLM / SLM 비교

| 모델 유형 | 정의 | 파라미터 크기 | 주요 장점 | 주요 단점 | 
|----------|-----|-------------|----------|----------| 
| **LLM**  | 대규모 언어 모델 | 수십억~수조 개  | 높은 성능과 범용성       | 높은 연산 자원 필요 | 
| **sLLM** | 경량화된 LLM    | 수억~수십억 개  | LLM 수준의 성능과 경량화 | LLM보다는 낮은 성능 가능성 | 
| **SLM**  | 소규모 언어 모델 | 수백만~수십억 개 | 경량화, 빠른 처리       | 제한된 성능과 범용성 | 


<br/>

[[TOP]](#index)

---

