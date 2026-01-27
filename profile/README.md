### <p align = center> 2025 Techeer Summer BootCamp-i 팀 <p>

# <img width="1816" height="581" alt="E83A0AB3-AD01-4CC4-9AAC-3C62A20C9691" src="https://github.com/user-attachments/assets/0cb67c4b-84fe-4544-9d0a-161d04524ddc" />


<p align="center">
![Homepage](asset/home.png)
</p>

<p align= center> (콘텐츠) 수많은 노래 속 자신의 취향을 찾아 떠나는 세계 </p>

# 🔗 Table of Contents 
- [Service](#-Service)
- [System Architecture](#-System-Architecture)
- [Tech Stack](#-Tech-Stack)
- [ERD](#-ERD)
- [Monitoring](#-Monitoring)
- [API](#-API)
- [Member](#-Member)
<br><br>

# 💡 Introduction
- Service URL
  
- Medium

* **개인 음악 분석:** 청취 시간·AI 생성 내역·TOP 장르/아티스트·분위기/키워드·실시간 나의 TOP 차트를 한눈에 확인.
* **음원별 상세 분석:** 감정 분석·시간대별 재생 패턴·유사 음악·태그 반응까지 곡 단위로 깊게 파악.
* **태그 검색 및 탐색(MusicVerse):** 54개 태그 기반으로 취향에 맞는 곡을 발견하고 분위기 있게 탐색/청취.
* **AI 음악 생성:** 원하는 느낌을 입력해 AI 곡을 만들고, 플랫폼에 게시해 공유/스트리밍.
* **스트리밍 기본 기능:** 좋아요(곡/앨범/플리)·개인 플레이리스트·아티스트/AI 곡 검색 등 핵심 플레이어 기능 제공.
* **차트:** 실시간 TOP100·일일 차트·AI 음악 차트로 트렌드와 인기곡을 빠르게 탐색.
* **태그 스테이션:** 태그 기반 스테이션으로 장르/무드별 빠른 선곡과 연속 재생으로 취향 확장.


# 🎵 DEMO

### | 홈 검색
<img src="https://github.com/user-attachments/assets/a203b157-503a-4faf-ad20-cafb99d3f533" width="1800" />

### | 재생 및 분석
<img src="https://github.com/user-attachments/assets/02afa34c-d761-431d-bfd4-dfec26d07692" width="1800" />

### | 검색
<img src="https://github.com/user-attachments/assets/14ec39a3-2680-4e25-b1ce-69ec5da36b58" width="1800" />

### | 비슷한 곡
<img src="https://github.com/user-attachments/assets/1dbdb2d2-c4d1-4c3a-a0b1-f43b9700f7e6" width="1800" />

### | 음악 생성
<img src="https://github.com/user-attachments/assets/d3016f85-4dc3-45a4-9352-2adba0ead21b" width="1800" />

### | 태그 탐색
<img src="https://github.com/user-attachments/assets/08cad6c9-84e5-4b72-815e-c3a6d098ebee" width="1800" />


# 🏗️ System Architechture
![테커 I 팀 시스템 아키텍처의 1월 27일 최종봄](https://github.com/user-attachments/assets/64f4956b-a5cc-4ed0-adce-6a99a4f71c53)

![기술 중심 아키텍처 완성본 ](https://github.com/user-attachments/assets/e43084bc-75d1-4129-bd65-955ce78f06d8)


# 💡 Langchain & LMM 등

(어필하고 싶은 프레임워크들)


# 💾 ERD

![ERD](./erd.png)


# 🛠️ Tech Stack


| Category | Technology |
| :--- | :--- |
| **Frontend** | <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind_CSS-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white"/> |
| **Backend** | <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/> <img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white"/> <img src="https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray"/> <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white"/> <img src="https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/> <img src="https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefik&logoColor=white"/> |
| **Database & Search** | <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white"/> <img src="https://img.shields.io/badge/OpenSearch-005EB8?style=for-the-badge&logo=opensearch&logoColor=white"/> |
| **Infrastructure** | <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white"/> <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/> |
| **AI Pipeline** | <img src="https://img.shields.io/badge/Meta%20Llama%203.1-0467DF?style=for-the-badge&logo=meta&logoColor=white"/> <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white"/> <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white"/> <img src="https://img.shields.io/badge/Suno_API-000000?style=for-the-badge&logo=music&logoColor=white"/> <img src="https://img.shields.io/badge/Tailscale-181818?style=for-the-badge&logo=tailscale&logoColor=white"/> |
| **Monitoring** | <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/> <img src="https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white"/> <img src="https://img.shields.io/badge/loki-F46800?style=for-the-badge&logo=grafana&logoColor=white"/> <img src="https://img.shields.io/badge/Promtail-F46800?style=for-the-badge&logo=grafana&logoColor=white"/> <img src="https://img.shields.io/badge/Flower-37ce02?style=for-the-badge&logo=celery&logoColor=white"/> |
| **CI / CD** | <img src="https://img.shields.io/badge/github%20actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white"/> |




# 📊 Monitoring



# 🔌 API

<img width="2946" height="6990" alt="SCR-20260127-bjcp" src="https://github.com/user-attachments/assets/8ea6b962-0f12-4d9d-a6d5-26a56e999d17" />

# How to Start

### Clone Repository

```bash
$ git clone https://github.com/2025-TecheerBootcamp-team-i/Backend.git
```

### env setting in the Settings folder

- settings/.env

```text
SECRET_KEY = 
DEBUG = 
DJANGO_ALLOWED_HOSTS = 

SQL_ENGINE = 
SQL_DATABASE = 
SQL_USER = 
SQL_PASSWORD = 
SQL_HOST = 
SQL_PORT = 

CELERY_BROKER_URL = 

WINDOWS_LLAMA_IP = 
LLAMA_MODEL_NAME = 

NGROK_AUTHTOKEN = 

SUNO_API_URL = 
SUNO_MODEL_VERSION = 
SUNO_TEST_MODE = 
SUNO_API_KEY = 
SUNO_CALLBACK_URL = 

OPENSEARCH_HOST = 
OPENSEARCH_PORT = 
OPENSEARCH_USERNAME = 
OPENSEARCH_PASSWORD = 
OPENSEARCH_USE_SSL = 
OPENSEARCH_VERIFY_CERTS = 
OPENSEARCH_INDEX_PREFIX = 

AWS_ACCESS_KEY_ID = 
AWS_SECRET_ACCESS_KEY = 
AWS_STORAGE_BUCKET_NAME = 
AWS_S3_REGION_NAME = 
AWS_S3_CUSTOM_DOMAIN = 
```


# 🧑 Member

| Name | 황현승 | 서두현 | 송영의 | 이재원 | 신영준 |
| :--: | :----: | :----: | :----: | :----: | :----: |
| Profile | <img width="100" height="110" src="" /> | <img width="100" height="110" src="" /> | <img width="100" height="110" src="" /> | <img width="100" height="110" src="" /> | <img width="100" height="110" src="" /> |
| Role | Team Leader<br/><br/> | <br/> | <br/> | <br/> | <br/> |
| GitHub | <a href=""><img src="" /></a> | <a href=""><img src="" /></a> | <a href=""><img src="" /></a> | <a href=""><img src="" /></a> | <a href=""><img src="" /></a> |
