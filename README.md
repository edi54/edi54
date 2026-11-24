### 안녕하세요, 김주희입니다.

LLM·RAG 기반 AI 서비스를 만듭니다.<br/>
근거 있는 답변을 만드는 일에 관심이 많아요!!

<br/>

<a href="https://github.com/edi54/BioRAG">
  <img src="./assets/biorag.svg" width="100%" alt="BioRAG — PubMed 논문 근거 기반 헬스 트렌드 Q&A 챗봇" />
</a>

GLP-1, 영양제, 공복 루틴 같은 헬스 트렌드 질문에 **PubMed 논문에서 검색한 내용으로만** 답하고,<br/>
근거 수준을 3단계로 보여주는 RAG 챗봇입니다.

- 시스템 아키텍처 설계, LangGraph RAG 파이프라인 설계
- PubMed·보조 문서 크롤링, Docker 개발 환경 구축
- 진행 중 — 골든셋 구축과 RAGAS 기반 품질 평가

[Repository](https://github.com/edi54/BioRAG) · [v4 Team Repo](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN25-4th-4Team) · [v3 Team Repo](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN25-3rd-4Team)

<!-- 아키텍처 사진: assets 폴더에 architecture.png로 올린 뒤, 이 주석의 첫 줄과 마지막 줄을 지우면 보여요.
<img src="./assets/architecture.png" width="100%" alt="BioRAG System Architecture" />
-->

<br/>

### Stack

| Category | Technologies |
| :-- | :-- |
| Languages | <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" /> |
| AI · LLM | <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" /> <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" /> <img src="https://img.shields.io/badge/Multi--Agent-7C3AED?style=for-the-badge" /> <img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=for-the-badge" /> |
| ML · DL | <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" /> <img src="https://img.shields.io/badge/SHAP-FF0051?style=for-the-badge" /> <img src="https://img.shields.io/badge/Prophet-0467DF?style=for-the-badge" /> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" /> <img src="https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&logo=ultralytics&logoColor=white" /> |
| Backend | <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" /> <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" /> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" /> |
| Frontend | <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" /> |
| Database | <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" /> <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge" /> |
| Data · MLOps | <img src="https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white" /> <img src="https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white" /> |
| Infrastructure | <img src="https://img.shields.io/badge/AWS_EC2_%C2%B7_S3_%C2%B7_RDS-232F3E?style=for-the-badge" /> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" /> <img src="https://img.shields.io/badge/K3s_%28K8s%29-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" /> <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" /> |
| DevOps | <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" /> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" /> <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" /> <img src="https://img.shields.io/badge/k6-7D64FF?style=for-the-badge&logo=k6&logoColor=white" /> |
| Collaboration | <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" /> |

<br/>

### Other

- [hey_apple](https://github.com/2022-Winter-Bootcamp-team-L/frontend) — 과일 인식으로 가격을 매기고 영수증을 이메일로 보내 주는 서비스 · 2022 Winter Bootcamp

<br/>

### Contact

[Email](mailto:joohee031104@gmail.com) · [Blog](https://velog.io/@akffkd03) · [GitHub](https://github.com/edi54)
