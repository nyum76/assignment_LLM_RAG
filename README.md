# README!!!!!!
### 사용 패키지
[requirements.txt](https://github.com/nyum76/assignment_LLM_RAG/blob/main/requirements.txt)에 사용한 패키지와 버전 모두 명시
해당 프로젝트 진행시 사용했던 모든 패키지 
#### 패키지 설치
1. [requirements.txt](https://github.com/nyum76/assignment_LLM_RAG/blob/main/requirements.txt) 파일을 다운로드 한다
2. `conda activate <가상환경이름>` : 패키지를 설치할 가상환경을 활성화 한다
3. `pip install -r requirements.txt` : 패키지 설치
   * `r` (read) : 해당 파일을 읽어서 그 안에 명시된 패키지들 한번에 설치

---
# INDEX

* [ChatBot](https://github.com/nyum76/assignment_LLM_RAG/tree/main/ChatBot) : LLM 과 RAG 개인과제 디렉토리
  * **[``chat_bot.ipynb``](https://github.com/nyum76/assignment_LLM_RAG/blob/main/ChatBot/chat_bot.ipynb) : 개인과제 구현 파일**
    * 개인과제 구현시 단계별로 markdown 을 추가하였습니다


* [PDF](https://github.com/nyum76/assignment_LLM_RAG/tree/main/PDF) : 과제에 필요한 PDF 디렉토리


* [Prompts](https://github.com/nyum76/assignment_LLM_RAG/tree/main/Prompts) : 도전과제 1번. LangSmith의 Prompt Library 를 참고한 프롬프트 디렉토리


* [Results](https://github.com/nyum76/assignment_LLM_RAG/tree/main/Results) : 도전과제 3번. 실행 결과 저장 디렉토리
  * 파일명 : `사용된프롬프트이름_result_imestamp.txt`
  * 질문내용-응답내용 포함


* .gitignore : 버전 관리에서 제외시킬 파일 명시 (OPENAI_API_KEY를 설정한 `.env`파일을 제외시킴)
