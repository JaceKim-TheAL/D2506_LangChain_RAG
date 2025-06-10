[practical_llm]: readme.md
[![적용기술](https://skillicons.dev/icons?i=ai,anaconda,py,vscode)][practical_llm]

### INDEX

<table>
  <tr align="center">
    <td width="150px"><a href="sect_01.md"> [LangChain]        </a></td>
    <td width="150px"><b href="sect_02.md"> [RAG]              </b></td>
    <td width="180px"><a href="sect_03.md"> [Multimodal RAG]   </a></td>
    <td width="150px"><a href="sect_04.md"> [Graph RAG]        </a></td>
    <td width="150px"><a href="sect_05.md"> [ReAct Agent]      </a></td>
    <td width="150px"><a href="sect_06.md"> [sLLM]             </a></td>
  </tr>
</table>

---
## 2. RAG(Retrieval-Augmented Generation)


---
**RAG(Retrieval-Augmented Generation)** 은 검색 증강 생성 기술로, 대규모 언어 모델(LLM)의 한계를 보완하기 위해 개발되었습니다. <br/>
기존 LLM은 학습된 데이터만을 기반으로 응답을 생성하지만, RAG는 외부 데이터베이스에서 관련 정보를 검색한 후 이를 활용하여 더욱 정확한 응답을 생성하는 방식입니다 <br/>
<br/>

![RAG from M/S](./images/s02_rag_from_ms.png)
<br/>

### RAG의 기본 아키텍처

일반적인 RAG 파이프라인은 두 개의 주요 컴포넌트로 구성됩니다: <br/>

- **검색기(Retriever)** </br>
• 사용자 쿼리에 따라 관련 문서를 외부에서 검색해오는 역할을 합니다. <br/>
• 기존의 BM25와 같은 기호 기반 검색 방식이 아닌, Dense Embedding을 사용한 근사 최근접 이웃(ANN) 검색이 활용<br/>
• 사용자의 질문을 벡터화하여 데이터베이스에서 관련 문서를 검색 <br/>
• 대표적인 벡터 데이터베이스로는 FAISS, Pinecone, Weaviate, Chroma 등이 있습니다.
- **생성기(Generator)** <br/>
• 검색된 문서와 사용자 쿼리를 입력으로 받아 최종 응답을 생성하는 대규모 언어 모델입니다. <br/>
• 기존 LLM보다 더 신뢰성 높은 정보를 제공할 수 있음 <br/>
• (예: GPT, T5, FLAN, Gemini) <br/>
<br/>

RAG의 기본 구조는 다음과 같습니다:
<pre>
사용자 쿼리 → Dense Retriever → 상위 k개 문서 → LLM Generator → 최종 응답
</pre>





<br/>

[[TOP]](#index)

---