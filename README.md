<div align="center">
  <h1>hoyeungkim</h1>
  <p>
    <strong>Backend Engineer</strong><br />
    Interested in Infrastructure &amp; Machine Learning
  </p>
  <p>API와 데이터 처리부터 배포 환경, 추천 기능까지 연결합니다.</p>
</div>

---

## Tech Stack

프로젝트에서 사용한 기술입니다.

**Backend & Data**

<p>
  <img src="https://img.shields.io/badge/Python-202020?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" height="22" />
  <img src="https://img.shields.io/badge/FastAPI-202020?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI" height="22" />
  <img src="https://img.shields.io/badge/Pydantic-202020?style=flat-square&amp;logo=pydantic&amp;logoColor=white" alt="Pydantic" height="22" />
  <img src="https://img.shields.io/badge/SQLAlchemy-202020?style=flat-square&amp;logo=sqlalchemy&amp;logoColor=white" alt="SQLAlchemy" height="22" />
  <img src="https://img.shields.io/badge/Alembic-202020?style=flat-square" alt="Alembic" height="22" />
  <img src="https://img.shields.io/badge/PostgreSQL-202020?style=flat-square&amp;logo=postgresql&amp;logoColor=white" alt="PostgreSQL" height="22" />
  <img src="https://img.shields.io/badge/PostGIS-202020?style=flat-square" alt="PostGIS" height="22" />
  <img src="https://img.shields.io/badge/Redis-202020?style=flat-square&amp;logo=redis&amp;logoColor=white" alt="Redis" height="22" />
  <img src="https://img.shields.io/badge/MongoDB-202020?style=flat-square&amp;logo=mongodb&amp;logoColor=white" alt="MongoDB" height="22" />
  <img src="https://img.shields.io/badge/SQLite-202020?style=flat-square&amp;logo=sqlite&amp;logoColor=white" alt="SQLite" height="22" />
</p>

**Infrastructure**

<p>
  <img src="https://img.shields.io/badge/Docker-303030?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker" height="22" />
  <img src="https://img.shields.io/badge/Kubernetes-303030?style=flat-square&amp;logo=kubernetes&amp;logoColor=white" alt="Kubernetes" height="22" />
  <img src="https://img.shields.io/badge/AWS-303030?style=flat-square" alt="AWS" height="22" />
  <img src="https://img.shields.io/badge/Amazon%20EKS-303030?style=flat-square" alt="Amazon EKS" height="22" />
  <img src="https://img.shields.io/badge/Amazon%20RDS-303030?style=flat-square" alt="Amazon RDS" height="22" />
  <img src="https://img.shields.io/badge/Amazon%20ECR-303030?style=flat-square" alt="Amazon ECR" height="22" />
  <img src="https://img.shields.io/badge/CloudFormation-303030?style=flat-square" alt="CloudFormation" height="22" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-303030?style=flat-square&amp;logo=githubactions&amp;logoColor=white" alt="GitHub Actions" height="22" />
  <img src="https://img.shields.io/badge/CodeBuild-303030?style=flat-square" alt="CodeBuild" height="22" />
</p>

**ML & AI**

<p>
  <img src="https://img.shields.io/badge/LightFM-444444?style=flat-square" alt="LightFM" height="22" />
  <img src="https://img.shields.io/badge/NumPy-444444?style=flat-square&amp;logo=numpy&amp;logoColor=white" alt="NumPy" height="22" />
  <img src="https://img.shields.io/badge/SciPy-444444?style=flat-square&amp;logo=scipy&amp;logoColor=white" alt="SciPy" height="22" />
  <img src="https://img.shields.io/badge/scikit--learn-444444?style=flat-square&amp;logo=scikitlearn&amp;logoColor=white" alt="scikit-learn" height="22" />
  <img src="https://img.shields.io/badge/pandas-444444?style=flat-square&amp;logo=pandas&amp;logoColor=white" alt="pandas" height="22" />
  <img src="https://img.shields.io/badge/Amazon%20Bedrock-444444?style=flat-square" alt="Amazon Bedrock" height="22" />
  <img src="https://img.shields.io/badge/Gemini-444444?style=flat-square&amp;logo=googlegemini&amp;logoColor=white" alt="Gemini" height="22" />
</p>

**Tools & Media**

<p>
  <img src="https://img.shields.io/badge/Git-555555?style=flat-square&amp;logo=git&amp;logoColor=white" alt="Git" height="22" />
  <img src="https://img.shields.io/badge/pytest-555555?style=flat-square&amp;logo=pytest&amp;logoColor=white" alt="pytest" height="22" />
  <img src="https://img.shields.io/badge/FFmpeg-555555?style=flat-square&amp;logo=ffmpeg&amp;logoColor=white" alt="FFmpeg" height="22" />
</p>

---

## Selected Projects

### 01. [Pinlm](https://github.com/SSAG-amja/VIDEO_BACK)

**사용자 행동과 콘텐츠 특성을 반영하는 개인화 영화 추천 서비스**

- FastAPI·PostgreSQL·Redis 기반 추천 API와 사용자 행동 처리
- LightFM·온톨로지 기반 모델 학습, 추천 후보 생성과 서빙 구조 구성
- MovieLens 데이터의 시간순 분할과 NDCG 기반 추천 순위 평가

[추천 엔진](https://github.com/SSAG-amja/VIDEO_BACK/tree/TEST/ontology-v2-version1) · [아키텍처](https://github.com/SSAG-amja/VIDEO_BACK/blob/TEST/ontology-v2-version1/z_v3_docs/01_architecture_and_pipeline.md) · [평가 설계](https://github.com/SSAG-amja/VIDEO_BACK/blob/TEST/ontology-v2-version1/tests/v3_long_term_eval/README.md)

<sub>추천 엔진과 관련 문서는 개발·실험 브랜치 TEST/ontology-v2-version1 기준입니다.</sub>

---

### 02. [서울 지금 어디](https://github.com/AWS-Cloud-One/seoul_now_back)

**혼잡도·교통·주차 정보를 활용한 서울 장소 추천 서비스**  
**최우수상 수상**

- CloudFormation으로 AWS EKS·RDS 실행 환경 구성
- GitHub Actions·OIDC·ECR·CodeBuild 기반 CI/CD 구축
- PostgreSQL 대화 상태 공유와 Kubernetes 순차 배포·복구 절차 구현

[인프라 코드](https://github.com/AWS-Cloud-One/seoul_now_back/tree/main/infra) · [배포 워크플로](https://github.com/AWS-Cloud-One/seoul_now_back/blob/main/.github/workflows/deploy.yml) · [구현 PR](https://github.com/AWS-Cloud-One/seoul_now_back/pull/18)

---

### 03. [SASU](https://github.com/QuietPeople/SASU_backend)

**영상·퀴즈·학습 기록을 제공하는 숏폼 학습 플랫폼**

- FFmpeg 기반 영상 검증·정규화와 썸네일 자동 생성
- 미디어 교체 시 파일·DB 정합성 및 동시 수정 충돌 처리
- HTTP Range 재생과 검색·페이지네이션 API 구현

[영상 처리](https://github.com/QuietPeople/SASU_backend/blob/main/app/modules/contents/video_service.py) · [구현 PR](https://github.com/QuietPeople/SASU_backend/pull/34)

---

### 04. [BIZIT](https://github.com/SSAG-amja/BIZIT_BACK)

**매장 정보와 상권 데이터를 결합해 Gemini 기반 경영 전략을 생성하는 서비스**

- pandas로 상권 데이터를 처리하고 매장별 분석 컨텍스트 구성
- Gemini 응답 파싱과 스키마 검증
- MongoDB 기반 분석 결과 저장·조회 API 구현

[분석 파이프라인](https://github.com/SSAG-amja/BIZIT_BACK/blob/main/api/solution.py) · [구현 PR](https://github.com/SSAG-amja/BIZIT_BACK/pull/18)

---

### 05. [IEUM](https://github.com/SSAG-amja/IEUM_route_search)

**시각장애인의 이동을 돕는 음성 기반 경로 안내 서비스**

- 경로 조회 API와 앱의 안내 흐름 연결
- 음성 입력을 활용한 목적지 선택·안내 인터페이스 구현

[백엔드 서비스](https://github.com/SSAG-amja/IEUM_route_search/blob/main/api/services.py) · [앱](https://github.com/SSAG-amja/IEUM_front)
