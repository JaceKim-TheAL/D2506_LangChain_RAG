[practical_llm]: https://github.com/JaceKim-TheAL/D2506_LangChain_RAG
[![적용기술](https://skillicons.dev/icons?i=ai,anaconda,py,vscode)][practical_llm]


### 랭체인과 RAG로 배우는
# 실전LLM 애플리케이션 개발

### INDEX

- [1. 랭체인(LangChain)                        ][link_01]
- [2. RAG(Retrieval-Augmented Generation)     ][link_02]
- [3. 멀티모달 RAG                             ][link_03]
- [4. Graph RAG                               ][link_04]
- [5. ReAct 에이전트                           ][link_05]
- [6. sLLM                                    ][link_06]

[nextjs15]: https://nextjs-ko.org/docs/app/building-your-application/upgrading/version-15
[link_01]: ./sect_01.md
[link_02]: ./sect_02.md
[link_03]: ./sect_03.md
[link_04]: ./sect_04.md
[link_05]: ./sect_05.md
[link_06]: ./sect_06.md

---
### Key Words

🚀 **OpenAI** 
: 인공지능(AI) 연구 및 개발을 선도하는 미국의 기업 <br/>
• 2015년에 설립되었으며, `ChatGPT`, `DALL·E`, `Codex` 등 다양한 `AI 모델을 개발`<br/>
• Microsoft와 협력하여 AI 기술을 다양한 산업에 적용<br/>
🔹 공식 웹사이트 : https://openai.com/ <br/>
<br/>

🚀 **Hugging Face**
: AI 및 머신러닝 모델을 공유하고 활용할 수 있는 `오픈소스 플랫폼`<br/>
• 특히 자연어 처리(NLP) 및 컴퓨터 비전 분야에서 강력한 도구를 제공<br/>
• 개발자, 연구원, AI 엔지니어들이 협업하고 최신 AI 기술을 쉽게 활용할 수 있도록 돕는 플랫폼<br/>

| 주요 기능    | 상세 설명  |
|-------------|----------|
| **Transformer 라이브러리**      | BERT, GPT, T5 등 다양한 AI 모델을 검색하고 다운로드 가능  |
| **모델 허브**      | 수천개의 사전 학습된 모델이 저장, 다양한 NLP 작업(번역,요약,질의-응답)에 사용  |
| **데이터셋**       | AI 모델 학습을 위한 방대한 데이터셋 제공              |
| **Inference API** | 별도의 코드 작성없이도 API 통해 모델 사용, 클라우드에서 AI 모델을 실행하고 결과를 얻을 수 있음 |
| **Spaces**        |  AI 데모 앱을 만들고 공유할 수 있는 공간              |

🔹 허깅페이스 : https://huggingface.co/ <br/>
<br/>

🚀 **CoT(Chain-of-Thought) 프롬프팅** <br/>
• 대규모 언어 모델(LLM)의 추론 능력을 향상시키는 기법으로, <br/>
• 모델이 복잡한 문제를 해결할 때 중간 추론 단계를 생성하도록 유도하는 방식 <br/>
• 기존의 단순한 프롬프팅 방식과 달리, CoT 프롬프팅은 문제를 여러 개의 작은 단계로 나누어 해결하도록 합니다.

<table>
  <tr>
    <td><b>핵심 개념</b></td>
    <td><b>상세 설명</b></td>
  </tr>
  <tr>
    <td><b>단계별 추론</b><br/>(Step-by-Step Reasoning)</td>
    <td>
      • 모델이 문제를 해결할 때 단계별로 논리적인 사고 과정을 거치도록 유도 <br/>
      • 예를 들어, 수학 문제를 풀 때 단순한 답변이 아니라 계산 과정과 논리를 명확하게 설명
    </td>
  </tr>
  <tr>
    <td><b>중간 추론 단계</b><br/>(Intermediate Reasoning Steps)</td>
    <td>
      • 모델이 최종 답변을 도출하기 전에 여러 개의 작은 단계로 문제를 나누어 해결 <br/>
      • 이를 통해 더 정확하고 신뢰할 수 있는 응답 생성 가능
    </td>
  </tr>
  <tr>
    <td><b>프롬프트 예시</b><br/>(Prompt Examples)</td>
    <td>
      • 모델에게 체인 오브 생각(Chain of Thought) 예시를 제공하여, 문제 해결 방법을 학습하도록 함 <br/>
      • 예시를 통해 모델이 논리적인 사고 과정을 따를 수 있도록 유도
    </td>
  </tr>
</table>

<br/>

---