[practical_llm]: readme.md
[![적용기술](https://skillicons.dev/icons?i=ai,anaconda,py,vscode)][practical_llm]

### INDEX

<table>
  <tr align="center">
    <td width="150px"><b href="sect_01.md"> [LangChain]        </b></td>
    <td width="150px"><a href="sect_02.md"> [RAG]              </a></td>
    <td width="180px"><a href="sect_03.md"> [Multimodal RAG]   </a></td>
    <td width="150px"><a href="sect_04.md"> [Graph RAG]        </a></td>
    <td width="150px"><a href="sect_05.md"> [ReAct Agent]      </a></td>
    <td width="150px"><a href="sect_06.md"> [sLLM]             </a></td>
  </tr>
</table>

---
## 1. 랭체인(LangChain)  

대규모 언어 모델(LLM)을 활용한 애플리케이션 개발을 돕는 `오픈소스 프레임워크` <br/>
다양한 데이터를 활용하여 `맥락에 맞는 응답`을 제공할 수 있는 환경을 제공 <b**r/>

- 기존 언어 모델이 단순한 텍스트 생성에 머무르는 경우가 많지만, LangChain은 **외부 데이터 소스와 통합**하여 보다 복잡하고 유용한 애플리케이션을 만들 수 있도록 설계되었다.
- 이 프레임워크는 데이터베이스, API, 파일 시스템 등과 연결하여 **실시간 데이터를 활용**할 수 있도록 지원하며, 이를 통해 챗봇, 문서 분석, 코드 생성, 질문 응답 시스템 등 다양한 AI 애플리케이션을 구축할 수 있다. 
- 또한, 프롬프트 관리, 체인 구성, 에이전트 활용 등의 기능을 제공하여 개발자가 보다 **정교한 AI 시스템**을 만들 수 있도록 도와준다.
- 쉽게 말해, LangChain은 LLM을 단순한 텍스트 생성 도구가 아니라 **실제 애플리케이션과 연결**하여 더 강력한 기능을 수행할 수 있도록 하는 도구라고 볼 수 있다.
<br/>

### LangChain의 기본 프레임워크
_LangChain은 기본적으로 간소화된 LLM 애플리케이션 라이프사이클을 제공하며, 다음과 같은 오픈소스 라이브러리로 구성합니다._

- **개발**: LangChain의 오픈소스 빌딩 블록, 컴포넌트, 서드파티 통합 등을 사용하여 애플리케이션을 빌드합니다.<br/>
• langchain: 애플리케이션의 코그너티브 아키텍처를 구성하는 체인, 에이전트 및 검색 전략<br/>
• langchain-core: 기본 추상화 및 LangChain 표현 언어<br/>
• langchain-community: 서드파티 통합 (langchain-openai, langchain-anthropic 등)<br/>

- **테스트**: LangSmith를 사용하여 체인을 검사, 모니터링 및 평가합니다.<br/>
• LangSmith: LLM 애플리케이션을 디버깅, 테스트, 평가, 모니터링할 수 있는 개발자 플랫폼입니다.<br/>

- **배포**: LangGraph Cloud를 사용하여 LangGraph 애플리케이션을 프로덕션에 바로 사용할 수 있는 API와 Assistant로 전환합니다.<br/>
• LangGraph: 그래프의 에지와 노드로 단계를 모델링하여 LLM으로 견고한 “stateful” 멀티 액터 애플리케이션을 구축합니다.<br/>
• LangServe: LangChain 체인을 REST API로 배포합니다.<br/>



<br/>

[[TOP]](#index)

---