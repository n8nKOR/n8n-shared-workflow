# Engineering 워크플로우

이 폴더에는 DevOps, CI/CD, 시스템 자동화, AI 기반 엔지니어링 도구에 중점을 둔 **58개의 워크플로우**가 포함되어 있습니다.

## 🤖 AI 기반 자동화 및 라우팅 시스템

### 지식 베이스 및 RAG 시스템
[![MongoDB Knowledge Base](4827.png)](4827.json)
**MongoDB 벡터 기반 지식 베이스 에이전트**
MongoDB Vector Search와 OpenAI를 활용한 고급 RAG 시스템입니다. 문서를 벡터화하여 저장하고 자연어 질문에 대해 정확한 답변을 제공합니다.

[![Instant RAG Builder](4501.png)](4501.json)
**즉석 RAG 빌더**
Google Drive와 Pinecone을 연동하여 새로운 파일이 업로드되면 자동으로 벡터화하고 RAG 시스템에 통합하는 실시간 시스템입니다.

### 동적 AI 모델 라우팅
[![Anthropic Model Router](4399.png)](4399.json)
**Anthropic Opus 4/Sonnet 4 동적 모델 선택기**
쿼리의 복잡성과 요구사항에 따라 자동으로 최적의 Anthropic 모델(Opus 4 또는 Sonnet 4)을 선택하는 지능형 라우팅 시스템입니다.

[![OpenRouter AI Routing](4237.png)](4237.json)
**OpenRouter 기반 AI 자동 라우팅**
OpenRouter를 통해 여러 AI 모델 간 동적 라우팅을 제공하여 최적의 응답을 위한 모델을 자동 선택하는 시스템입니다.

[![Dynamic LLM Switcher](3820.png)](3820.json)
**LLM 간 동적 전환 템플릿**
실행 중 오류 발생 시 자동으로 다른 LLM으로 전환하여 안정적인 AI 서비스를 보장하는 폴백 시스템입니다.

## 🔧 CI/CD 및 DevOps 자동화

### 코드 리뷰 및 품질 관리
[![GitLab MR Review](3997.png)](3997.json)
**GitLab MR 자동 리뷰 및 리스크 평가**
Anthropic Claude를 사용하여 GitLab Merge Request를 자동으로 분석하고 코드 품질, 보안 위험, 테스트 케이스를 평가하는 시스템입니다.

[![GitHub Code Review](3804.png)](3804.json)
**GitHub 코드 리뷰 워크플로우**
GitHub Pull Request를 자동으로 분석하여 AI 기반 코드 리뷰 코멘트를 생성하고 베스트 프랙티스를 검증하는 시스템입니다.

### 백업 및 배포 자동화
[![Workflow Backup](4064.png)](4064.json)
**워크플로우 GitHub 백업 시스템**
n8n 워크플로우를 정기적으로 GitHub에 백업하여 버전 관리와 재해 복구를 자동화하는 시스템입니다.

[![Multi Repo Monitor](2435.png)](2435.json)
**여러 GitHub 리포지토리 모니터링**
여러 GitHub 리포지토리에 웹훅을 등록하여 실시간으로 코드 변경사항을 모니터링하는 시스템입니다.

### 시각적 회귀 테스트
[![Visual Regression Test](2419.png)](2419.json)
**Apify 기반 비주얼 회귀 테스트**
웹사이트 스크린샷을 자동으로 생성하고 Gemini Vision을 사용하여 UI 변경사항을 감지하는 자동화된 테스트 시스템입니다.

## 💾 데이터 처리 및 벡터 스토어

### 벡터 데이터베이스 통합
[![Supabase Vector Store](4086.png)](4086.json)
**Supabase 벡터 저장소 통합 시스템**
PDF, 텍스트 파일을 자동으로 벡터화하여 Supabase에 저장하고 AI 기반 검색을 제공하는 완전한 RAG 파이프라인입니다.

[![Bright Data Extraction](3866.png)](3866.json)
**Bright Data 구조화된 대량 데이터 추출**
Bright Data를 사용하여 대규모 웹 데이터를 구조화된 형태로 추출하고 처리하는 고급 데이터 수집 시스템입니다.

### 데이터 동기화
[![Google Sheets Sync](2081.png)](2081.json)
**Google Sheets to PostgreSQL 동기화**
Google Sheets의 데이터를 PostgreSQL 데이터베이스와 실시간으로 동기화하여 데이터 일관성을 유지하는 시스템입니다.

## 🕷️ 웹 스크래핑 및 데이터 수집

### AI 기반 스크래핑
[![Dumpling AI Scraper](3701.png)](3701.json)
**Dumpling AI로 책 스크래핑**
Dumpling AI를 사용하여 온라인 서점에서 책 정보를 스크래핑하고 Google Sheets에 저장한 후 CSV로 이메일 전송하는 시스템입니다.

[![Google Maps Scraper](2063.png)](2063.json)
**Google Maps 데이터 스크래핑**
SerpAPI를 활용하여 Google Maps에서 비즈니스 정보를 체계적으로 수집하는 위치 기반 데이터 수집 시스템입니다.

## 🎨 비주얼 및 멀티미디어 자동화

### AI 콘텐츠 생성
[![Animated Stories](3655.png)](3655.json)
**GPT-4o-mini, Midjourney, Kling 애니메이션 스토리 생성**
GPT-4o-mini로 스토리를 생성하고, Midjourney로 이미지를 만들고, Kling으로 애니메이션을 제작하는 완전 자동화된 콘텐츠 생성 파이프라인입니다.

### 이미지 처리 자동화
[![Image Processing Pipeline](3459.png)](3459.json)
**AI 기반 이미지 처리 파이프라인**
다양한 이미지 처리 작업을 AI로 자동화하여 대량의 이미지를 효율적으로 처리하는 시스템입니다.

## 🛠️ MCP 서버 및 도구 개발

### MCP 서버 인프라
[![GitHub MCP Server](3635.png)](3635.json)
**GitHub MCP 서버**
Model Context Protocol을 사용하여 GitHub API와 통합하는 서버를 구축하여 AI 에이전트가 GitHub과 상호작용할 수 있게 하는 시스템입니다.

[![PayCaptain MCP Server](3638.png)](3638.json)
**PayCaptain MCP 서버 기반 직원 관리**
PayCaptain.com API를 활용한 MCP 서버 기반 HR 도구로 급여 및 직원 정보를 관리하는 시스템입니다.

## 🌐 API 및 웹서비스 개발

### RESTful API 개발
[![Multi Method API](2490.png)](2490.json)
**다중 메소드 API 엔드포인트 템플릿**
GET, POST, PUT, DELETE 등 다양한 HTTP 메소드를 지원하는 RESTful API 엔드포인트를 구축하는 템플릿입니다.

[![Custom API Builder](2328.png)](2328.json)
**커스텀 API 빌더**
n8n을 사용하여 커스텀 API 엔드포인트를 빠르게 구축하고 배포하는 개발 도구입니다.

### 웹훅 관리
[![Webhook Manager](2513.png)](2513.json)
**웹훅 관리 시스템**
여러 서비스의 웹훅을 중앙에서 관리하고 라우팅하는 통합 웹훅 관리 시스템입니다.

---

## 🛠️ 구현 가이드

### 핵심 기술 스택
- **AI/ML**: OpenAI GPT-4, Anthropic Claude, Google Gemini, OpenRouter
- **벡터 데이터베이스**: Pinecone, MongoDB Vector Search, Qdrant, Supabase Vector
- **CI/CD 도구**: GitHub Actions, GitLab CI, Docker
- **클라우드 플랫폼**: Google Cloud, AWS, Supabase
- **모니터링**: Linear, Slack, 이메일 알림
- **웹 스크래핑**: Bright Data, Apify, Dumpling AI
- **데이터베이스**: PostgreSQL, MySQL, Redis

### 설정 요구사항
1. **AI 서비스 API 키**: OpenAI, Anthropic, Google AI 등
2. **DevOps 도구 연동**: GitHub, GitLab, Linear 설정
3. **벡터 데이터베이스**: Pinecone, MongoDB Atlas 설정
4. **클라우드 서비스**: Google Drive, Supabase 연동
5. **웹 스크래핑 서비스**: Bright Data, Apify API 키

## 🔐 보안 고려사항

### CI/CD 보안
- 시크릿 관리 및 API 키 보호
- 코드 리뷰 프로세스 자동화
- 취약점 스캔 통합
- 접근 권한 관리

### 데이터 보안
- 벡터 데이터베이스 암호화
- API 엔드포인트 인증
- 민감한 데이터 마스킹
- 감사 로그 생성

## ⚡ 성능 최적화

### AI 모델 최적화
- 모델 라우팅을 통한 비용 절감
- 응답 시간 최적화
- 캐싱 전략 구현
- 배치 처리 활용

### 인프라 확장성
- 로드 밸런싱 구현
- 자동 스케일링 설정
- 데이터베이스 인덱싱
- CDN 활용

## 🔗 주요 통합 서비스

### 개발 도구
- **GitHub/GitLab**: 소스 코드 관리 및 CI/CD
- **Linear**: 이슈 추적 및 프로젝트 관리
- **Docker**: 컨테이너화 및 배포
- **Kubernetes**: 오케스트레이션

### AI 플랫폼
- **OpenAI**: GPT 모델 및 임베딩
- **Anthropic**: Claude 모델
- **Google AI**: Gemini 및 PaLM
- **OpenRouter**: 멀티 모델 액세스

### 데이터 플랫폼
- **Pinecone**: 벡터 검색
- **MongoDB Atlas**: 문서 및 벡터 저장
- **Supabase**: 백엔드 서비스
- **PostgreSQL**: 관계형 데이터베이스

## 📚 관련 자료

### 학습 리소스
- [n8n DevOps 가이드](https://docs.n8n.io/hosting/)
- [Vector Database 비교](https://docs.n8n.io/integrations/builtin/cluster-nodes/)
- [MCP 프로토콜 문서](https://modelcontextprotocol.io/)
- [AI 모델 최적화](https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.lmchatopenai/)

### 베스트 프랙티스
- [CI/CD 워크플로우 설계](https://docs.github.com/en/actions)
- [벡터 데이터베이스 설계 패턴](https://docs.pinecone.io/guides/data/understanding-hybrid-search)
- [API 보안 가이드](https://docs.n8n.io/hosting/security/)

## 🎯 사용 사례

### DevOps 팀
- 자동화된 코드 리뷰 및 품질 검사
- CI/CD 파이프라인 최적화
- 인프라 모니터링 및 알림
- 배포 자동화

### AI/ML 엔지니어
- RAG 시스템 구축 및 관리
- 모델 성능 모니터링
- 데이터 파이프라인 자동화
- A/B 테스트 자동화

### 백엔드 개발자
- API 개발 및 테스트 자동화
- 데이터베이스 마이그레이션
- 성능 모니터링
- 로그 분석 자동화

### QA 엔지니어
- 자동화된 테스트 실행
- 비주얼 회귀 테스트
- 성능 테스트 자동화
- 버그 리포팅 자동화

이 워크플로우들은 현대적인 소프트웨어 개발 및 운영 프로세스를 자동화하여 개발 효율성을 크게 향상시키고 품질을 보장하는 포괄적인 엔지니어링 솔루션을 제공합니다.