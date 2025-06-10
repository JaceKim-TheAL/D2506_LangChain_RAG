[practical_llm]: readme.md
[![적용기술](https://skillicons.dev/icons?i=ai,anaconda,py,vscode)][practical_llm]

### INDEX

<table>
  <tr align="center">
    <td width="150px"><a href="sect_01.md"> [LangChain]        </a></td>
    <td width="150px"><a href="sect_02.md"> [RAG]              </a></td>
    <td width="180px"><a href="sect_03.md"> [Multimodal RAG]   </a></td>
    <td width="150px"><b href="sect_04.md"> [Graph RAG]        </b></td>
    <td width="150px"><a href="sect_05.md"> [ReAct Agent]      </a></td>
    <td width="150px"><a href="sect_06.md"> [sLLM]             </a></td>
  </tr>
</table>

---
## 4. Graph RAG                          


GraphRAG은 기존 RAG(Retrieval-Augmented Generation) 기술을 확장하여 지식 그래프(Knowledge Graph)를 활용하는 AI 접근 방식 </br> 
일반적인 RAG는 문서 검색을 기반으로 하지만, GraphRAG는 데이터 간의 관계를 그래프 형태로 정리하여 더욱 정교한 정보 검색과 응답 생성을 가능하게 합니다. </br>
<br/>

[[TOP]](#index)

---
### GraphRAG의 핵심 개념

- **지식 그래프 기반** – 입력 텍스트에서 엔티티와 관계를 추출하여 구조화된 지식 그래프를 구축
- **계층적 클러스터링** – 서로 밀접하게 연결된 데이터를 그룹화하여 Leiden 알고리즘을 활용한 클러스터링 수행
- **요약 생성**        – 각 데이터 그룹과 노드에 대한 요약을 생성하여 전체적인 데이터 이해도를 향상
<br/>

[[TOP]](#index)

---
### GraphRAG의 장점

- **더 정교한 정보 검색** – 단순한 키워드 검색이 아닌, 데이터 간의 관계를 분석하여 더욱 정확한 정보 제공
- **문맥 이해력 향상** – 기존 RAG보다 더 깊은 문맥을 고려하여 응답 생성 가능
- **복잡한 데이터 처리 가능** – 의료, 법률, 연구 분야 등 구조화된 데이터가 중요한 영역에서 강력한 성능 발휘

<br/>

[[TOP]](#index)

---
###  GraphRAG의 활용 사례

| 분야    | 활용 사례 |
|--------|----------|
| **의료 데이터 분석** | 환자 기록과 연구 논문을 연결하여 더 정확한 진단 지원                   |
| **법률 문서 검색**   | 판례와 법 조항 간의 관계를 분석하여 법률 전문가에게 최적화된 정보 제공   |
| **기업 데이터 관리** | 내부 문서와 보고서를 연결하여 더 효율적인 지식 관리 시스템 구축          |

GraphRAG는 기존 RAG의 한계를 극복하고 `더 깊이 있는 정보 검색과 응답 생성`을 가능하게 하는 기술로, 특히 구조화된 데이터가 중요한 분야에서 강력한 성능을 발휘합니다.
<br/>

[[TOP]](#index)

---
