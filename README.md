# AWS Community Day - re:Invent 특집
## 개요

2019년 1월 25일 세종대학교에서 실시된 **AWS Community Day**의 내용을 정리한 문서이다.

[자세한 내용을 보기 위한 링크](https://pages.awscloud.com/aws-community-day-seoul-2019.html?trk=em_inv2&mkt_tok=eyJpIjoiT1RreU9EVTJNelpoTXpjMiIsInQiOiJZTzFsd0NVXC9iRE4rVEdJUXdcL21YODB5eWU2Q0RmMVNzYVREMlArUEFJeWdZdmNZZTQ2Vk1pcXhGN2FWeGZcL3YzaERsUWkxRUhkSm94NlI4cWVkdVFXem1nQVhRS3F4OThZK0FtbFhuZ2tEcmV0NnMzWU95QnQzK0lySnJkMUd4NE44SFo0N0JlTnJBamg2QkpZRlFYcGc9PSJ9)



## 행사 일정

![행사일정](https://awskrug.github.io/events/2019-communityday/agenda.png)



## 내용 요약

#### 인사말

- AWSKRUG 운영진이자, 이랜드 시스템스에서 운영 중인 박상욱
- **AWS Community 소개**



#### 키노트

- AWS 테크에반젤리스트, 윤석찬
- **AWS 전반적인 소개**
  - 빠른 개발 환경 지원 기능
    - AWS Toolkit
    - Serverless Application Environment
      - AWS Lamda
      - Serverless Application Repository
      - Nested Applications
      - ALB Support for Lambda
        - Web Socket support for API Gateway (**AWS Lamda New Feature**)
  - 서버리스 및 컨테이너 구현 접근법
    - AWS Fargate + AWS Lambda
      - 더이상 컨테이너 방식을 사용하지 않을 수 있다! 왜?
  - **Firecracker (microVM)**
    - 아주 작은 Virtual Machine
  - 다양한 데이터베이스 선택 옵션 제공
    - 관계형 데이터베이스 (RDBMS)
    - Key-Value Store
    - In-Memory DB
    - 시계열(Time-series) 데이터 처리에 대한 어려움 발생
      - **Amazon Timestream**
        - 빠르게 타임 시계열 데이터 처리 가능
  - 블럭체인(Blockchain) 활용 분야 안내
    - Health Care
    - DMV
    - 제조사
    - HR & 급여
    - 지원 솔루션
      - **Amazon Quantum Ledger Database**
        - 신뢰할 수 있는 중앙에서 운영하는 투명한 암호로 입증 가능한 불변 트랜잭션 로그를 제공하는 매니지드 원장 데이터베이스
      - **Amazon Managed Blockchain (Closed Beta)**
        - 확장 가능한 블록 체인 네트워크 생성 및 관리 서비스
  - **AI 플랫폼**
    - Amazon SageMaker
      - 손쉬운 기계 학습 모델 생성, 훈련 및 서비스 배포 완전 관리 서비스
        - Jupyter Notebook 기반 서비스
    - AWS DeepRacer
      - 강화 학습을 통해 자율 주행이 가능한 작은 사이즈의 자동차 모형
    - AWS DeepLens
      - 이미지 인식을 돕는 디바이스
    - AI
      - Amazon.com에서 사용된 것과 동일한 기술을 바탕으로 제작된 서비스를 소개한다.
      - 개인화 및 추천에 대해 추천 가능한 알고리즘
        - Amazon Personalize
          - 실시간 개인ㄹ화 및 추천 서비스
      - 비즈니스 예측
        - Amazon ForeCast (Preview 상태)
          - 높은 정확성의 시계열 예측 서비스
          - 구매, 매출, 광고 예측
        - 문서 내 텍스트 정보 추출, OCR
          - Amazon Textract (Preview 상태)
            - 문서에서 텍스트와 데이터를 의미적으로 쉽게 추출할 수 있는 OCR++서비스
            - 표, 데이터 상태를 추측해서 데이터베이스에 넣어주는 서비스
        - AI + 분석 + 스토리지 통합 = 요구사항 맞춤 지원
          - Data Lake 구성 및 관리는?
            - Amazon Lake Formation
              - 며칠 내에 안전한 데이터 레이크를 구축할 수 있는 서비스
  - 미래 산업 진입 장벽 철폐
    - 