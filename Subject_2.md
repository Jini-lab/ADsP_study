# 데이터 분석 기획의 이해 


## <span style="color:yellowgreen"> 분석 대상과 그 방법에 따른 4가지 분석 주제 </span>
🌟 분석 대상과 그 방법에 따른 분석 유형 4가지 외우기
![](https://velog.velcdn.com/images/chung0916/post/5df928a9-64a1-4ff2-a6b8-31389d883b3a/image.png)

---
</br>

## 목표 시점 별 분석 기획 방안
💡 목표 시점별 분석 방향, 목표, 유형, 접근 방식에 대한 특정 이해하기

|당면한 분석 주제의 해결</br>(과제 단위)||지속적 분석 문화 내재화</br>(마스터플랜 단위)|
|:--|---|:--|
|Speed & Test|↔️</br> 1차 목표|Accuracy & Deploy|
|Quick & Win|↔️</br> 과제의 유형|Long Term View|
|Problem Solving|↔️</br>접근 방식|Problem Definition|

---
</br>
# 분석 방법론
## 분석 방법론 개요

방법론은 상세한 <span style="color:yellowgreen">절차(Procedures), 방법(Methods), 도구와 기법(Tools & Techniques), 템플릿과 산출물(Templates & Outputs)</span>로 구성되어 있다.

### 데이터 기반 의사결정의 필요성
🌟 데이터 기반 의사결정의 필요성에서 합리적 의사결정을 가로막는 장애요소에 대한 문제 자주 출제 !

경험과 감에 따른 의사결정 ➡️ 데이터 기반의 의사결정

</br>

📍 **기업의 합리적 의사결정을 가로막는 장애요소**
+ 고정 관념
+ 편향된 생각
+ 프레이밍 효과

</br>

### 방법론의 적용 업무 특정에 따른 모델

1️⃣ ** 폭포수 모델 (Waterfall Model)**
- 단계를 순차적으로 진행
- 이전 단계가 완료되어야 다음 단계로 진행
- 문제 발견 시, 피드백 과정 수행

</br>

2️⃣ ** 프로토타입 모델 (Prototype Model)**
- 고객 요구 분석의 어려움을 해결하기 위해 일부분을 우선 개발
- 그 결과를 통한 개선 작업 시행

</br>

3️⃣ ** 나선형 모델(Spiral Model)**
- 반복을 통해 점증적 개발
- 처음 시도하는 프로젝트에 적용


---
</br>

## <span style="color:yellowgreen">KDD 분석 방법론</span>
💡분석가 관점이다.

KDD (Knowledge Discovery in Databases)는 프로파일링 기술을 기반으로 데이터로부터 통계적 채턴이나 지식을 찾기 위해 활용될 수 있도록 체계적으로 정리한 데이터 마이닝 프로세스이다.

### KDD 분석 절차

**<span style="color:yellowgreen">데이터셋 선택 → 데이터 전처리 → 데이터 변환 → 데이터 마이닝 → 데이터 마이닝 결과 평가</span>**


1️⃣ **데이터셋 선택 (Selection)**
- 비즈니스에 대한 이해
- 프로젝트 목표 설정
- 필요한 데이터 선택
- 데이터 마이닐에 필요한 목표데이터(Target)를 구성하여 분석에 활용
</br>

2️⃣ **데이터 전처리 (Preprocessing)**
- 잡음(Noise), 이상치(Outlier), 결측치(Missing Value)를 식별하고 필요시 제거하거나 재처리하여 데이터셋 정제
- 추가로 요구되는 데이터셋이 필요한 경우, 데이터 선택 프로세스 재실행
</br>

3️⃣ **데이터 변환 (Transformation)**
- 효율적으로 데이터마이닐을 할 수 있도록 데이터에 변경하는 단계
- 변수 생성, 선택하고 데이터 차원을 축소
- 학습용 데이터, 시험용 데이터로 데이터 분리
</br>

4️⃣ **데이터 마이닝 (Data Mining)**
- 데이터마이닝 기법을 선택 및 실행
- 필요에 따라 데이터 전처리와 변환 프로세스를 추가로 실행하여 최적의 결과 산출
</br>

5️⃣ **데이터 마이닐 결과 평가 (Interpretation/Evaluation)**
- 결과에 대한 해석과 평가, 분석 목적과의 일치성 확인
- 필요에 따라 데이터 선택 프로세스에서 데이터마이닝 프로세스를 반복 수행
</br>

---
</br>

## <span style="color:yellowgreen">CRISP-DM 분석 방법론</span>

💡 기획자 관점이다.

CRISP-DM (Cross Industry Standard Process for Data Mining)은 계층적 프로세스 모델로써 4개의 레벨로 구성되며, 주요한 5개의 업체들(Daimler-Cyrysler, SPSS, NCR, Teradata, OHRA)이 주도하였다.
</br>

### CRISP-DM의 4레벨

**여러 개의 단계 (Phases) → 일반화 테스크 (Generic Tasks) → 세분화 테스크 (Specialized Tasks) → 프로세스 실행(Process Instances)**
</br>

### CRISP-DM의 프로세스
🌟 6단계 그리고 각 단계별 업무 내용 외우기

**<span style="color:yellowgreen">업무 이해 → 데이터 이해 → 데이터 준비 → 모델링 → 평가 → 전개</span>**
</br>

1️⃣ **업무 이해 (Business Understanding)**
- 목적과 요구사항 이해
- 데이터 분석을 위한 문제 정의
- 프로젝트 계획 수립
</br>

2️⃣ **데이터 이해 (Data Understanding)**
- 데이터 수집
- 데이터 속성 이해
- 인사이트 발견
   - EDA(초기 데이터 수집, 데이터 기술 분석)
   - 데이터 탐색
   데이터 품질 확인
</br>

3️⃣ **데이터 준비 (Data Preparation)**
- 수집된 데이터에서 분석 기법에 적합한 데이터를 편성
   - 분석용 데이터셋 선택
   - 데이터 정제
   - 데이터 포맷팅
</br>

4️⃣ **모델링 (Modeling)**
- 최적화 단계
- 과적합 문제 확인
   - 모델 평가
</br>

5️⃣ **평가 (Evaluation)**
- 결과가 프로젝트 목적에 부합하는지 평가
   - 분석결과 평가
</br>

6️⃣ **전개 (Deployment)**
- 실 업무에 적용하기 위한 계획 수입
- 유지보수 계획
</br>

---
## <span style="color:yellowgreen">KDD와 CRISP-DM의 비교</span>
🌟 데이터 수집은 KDD에서는 데이터셋 선택에서, CRISP-DM에서는 데이터의 이해 단계에서 진행된다.

|KDD|CRISP-DM|
|---|---|
|분석대상 비즈니스 이해|업무 이해|
|데이터셋 선택|데이터의 이해|
|데이터 전처리||
|데이터 변환|데이터 준비|
|데이터 마이닐|모델링|
|데이터 마이닝 결과 평가|평가|
|데이터 마이닝 활용|전개|

---
</br>

## <span style="color:yellowgreen">빅데이터 분석 방법론</span>
![](https://velog.velcdn.com/images/chung0916/post/007e58f6-a204-4379-bb5a-7db4e2b35d91/image.jpg)

1️⃣ **분석 기획**
- 데이터 이해 및 범위 설정
- 프로젝트 정의 및 계획 수립
- 프로젝트 위험 계획 수립
</br>

2️⃣ **데이터 준비**
- 필요 데이터 정의
- 데이터 수집 및 정합성 점검
</br>

3️⃣ **데이터 분석**
- 분석용 데이터 준비
- 텍스트 분석
- 모델링
- 모델 평가 및 검증
- 모델 운영방안 수립
</br>

4️⃣ **시스템 구현**
- 설계 및 구현
- 시스템 테스트 믳 운영
</br>

5️⃣ **평가 및 전개**
- 모델 발전계획 수립
- 프로젝트 평가 및 보고


---
</br>

# 분석 과제 발굴

## <span style="color:yellowgreen">분석 과제 발굴 방법론</span>

<분석 과제 도출의 2가지 유형>
- 하향식 접근 방법
- 상향식 접근 방법

![](https://velog.velcdn.com/images/chung0916/post/946ffa35-06da-41ea-9a6b-7b5d088978ea/image.jpg)


---
</br>

### 하향식 접근법 (Top down Approach)
🌟 특히 문제 탐색 단계는 반드시 기억하기

</br>
**문제 탐색 → 문제 정의 → 해결 방안 탐색 → 타당성 검토**

</br>

1️⃣ **문제 탐색 단계 (Problem Discovery) - 하향식 접근법 1단계**
- 비즈니스 모델 기반 문제 탐색
  - 비즈니스 모델 캔버스를 활용한 과제 발굴 방법 5가지 영역
  <img src="https://velog.velcdn.com/images/chung0916/post/aa2dd25a-e8e2-42ce-9523-d2f18e2d7af9/image.png" width="40%" height="30%" alt="PD"></img>
  
  |과제 발굴 방법|내용|예|
  |:--|:--|:--|
  |⓵ 업무</br>(Operation)|내부 프로세스 및 주요 자원|- 생산 공정 최적화</br>- 재고량 최소화|
  |⓶ 제품</br>(Product)|제품, 서비스를 개선하기 위한 관련 주제 도출|- 제품의 주요 기능 개선</br>- 서비스 모니터링 지표 도출|
  |⓷ 고객</br>(Customer)|제공하는 채널의 관점에서 관련 주제 도출|- 고객의 콜 대기 시간 최소화</br>- 영업점 위치 최적화|
  |⓸ 규제와 감사</br>(Regualtion&Audit)|규제 및 보안의 관점|- 제공 서비스 품질의 이상 징후 관리</br>- 새로운 환경 규제 시 예상되는 제품 추출|
  |⑤ 지원 인프라</br>(IT&Human Resources)|인력의 관점|- 적정 운영 인력 도출|
  </br>
  
- 분석 기회 발굴의 범위 확장
   - 4가지 관점과 내용
   <img src="https://velog.velcdn.com/images/chung0916/post/5e1f0dc6-68da-46d9-9d96-b6402a76619d/image.png" width="60%" height="50%" alt="PD1"></img>
      ⓵ 거시적 관점
      &nbsp;&nbsp;&nbsp;&nbsp; : [STEEP] 사회, 기술, 경제, 환경, 정치 영역</br>
      ⓶ 경쟁자 확대 관점
      &nbsp;&nbsp;&nbsp;&nbsp; - 대체재 : 현재 생산을 수행하고 있는 제품의 잠재적 위험 파악
      &nbsp;&nbsp;&nbsp;&nbsp; - 경쟁자 : 주요경쟁자에 대한 동향을 파악하여 분석 기회 도출
      &nbsp;&nbsp;&nbsp;&nbsp; - 신규 진입자 : 신규 지입자에 대한 동양을 파악하여 분석 기회 도출 </br>
      ⓷ 시장의 니즈 탐색 관점
      &nbsp;&nbsp;&nbsp;&nbsp; - 고객
      &nbsp;&nbsp;&nbsp;&nbsp; - 채널
      &nbsp;&nbsp;&nbsp;&nbsp; - 영향자 </br>
      ⓸ 역량의 재해석 관점
      &nbsp;&nbsp;&nbsp;&nbsp; - 내부 역량
      &nbsp;&nbsp;&nbsp;&nbsp; - 파트너와 네트워크
</br>

2️⃣ **문제 정의 단계 (Problem Definition) - 하향식 접근법 2단계**
: 비즈니스 문제를 데이터의 문제로 변환하여 정의하는 단계
</br>

3️⃣ **해결 방안 탐색 단계 (Solution Search) - 하향식 접근법 3단계**
![](https://velog.velcdn.com/images/chung0916/post/ce057dde-9fc7-4c56-8cc0-ce4a02db34d9/image.png)
</br>

4️⃣ **타당성 검토 단계 (Feasibility Study) - 하향식 접근법 4단계**
- 경제성 타당성
- 기술 및 데이터의 타당성
</br>

### 상향식 접근법 (Bottom Up Approach)

** 일반적으로 상향식 접근 방식의 데이터 분석은 비지도 학습에 의해 수행**

- 비지도 학습
&nbsp;&nbsp;&nbsp;&nbsp; : 데이터의 연관성을 중심으로 데이터의 상태를 표현
   - (예) 장바구니 분석, 군집 분석, 기술 통계, 프로파일링
   
- 지도 학습
&nbsp;&nbsp;&nbsp;&nbsp; : 명확한 목적 하에 데이터 분석 실시
   - (예) 분류, 추측, 예측, 최적화를 통해 사용자의 주도하에 분석을 실시하고 지식을 도출
  
</br>

- 시행착오를 통한 문제 해결
   - 프로토타이핑 접근법 : 반복적으로 개선해나가는 방법
   &nbsp;&nbsp;&nbsp;&nbsp; (사용하는 경우) 문제 정의가 불명확,필요 데이터 존재 여부의 불확실성, 데이터 사용 목적의 가변성

</br>

- 분석과제 정의

---
</br>

# 분석 프로젝트 관리 방안

## 분석 과제 관리를 위한 5가지 주요 영역
|영역|설명|
|:--|:--|
|데이터 크기|분석하고자 하는 데이터 양을 고려|
|데이터 복잡성|해당 데이터에 잘 적용될 수 있는 분석 모델의 선정|
|속도|시나리오 측면에서 속도를 고려|
|분석 복잡성|해석이 가능하면서 정확도를 올릴수 있는 최적모델 모색|
|정확도 & 일관성|-|

# 분석 마스터 플랜

## 마스터플랜 수립 프레임워크

![](https://velog.velcdn.com/images/chung0916/post/316ed802-b88b-4587-9f73-a2657c6ae79d/image.jpg)

- 적용 우선순위 설정
- 분석 구현 로드맵 수립

### 수행과제 도출 및 우선순위 평가

**ROI 관점에서 빅데이터 핵심 특징**
- 투자비용 요소 (3V)
   - 크기 Volume
   - 다양성 Variety
   - 속도 Velocity
- 비즈니스 효과 요소
   - 가치 Value
</br>   

**데이터 분석 과제 추진시 고려해야 하는 우선순위 평가 기준**
- 시급성
   - 시급성의 판단 기준은 전략적 중요도가 핵심
   - 비즈니스 효과 고려
- 난이드
   - 투자비용 요소 고려
</br>  

**포트폴리오 사분면 분석을 통한 과제 우선순위 선정**
<img src="https://velog.velcdn.com/images/chung0916/post/7e64b568-2b4a-40bc-a85d-634e8c250a73/image.png" width="50%" height="30%" alt="PD"></img>

---
</br>

# 분석 거버넌스 체계 수립

## <span style="color:yellowgreen">분석 거버넌스 체계 구성요소</span>
1️⃣ 데이터 (Data)
2️⃣ 분석 교육/마인드 육성체계 (Human Resource)
3️⃣ 분석 기획 및 관리 수행 조직 (Organization)
4️⃣ 과제 기획 및 운영 프로세스 (Process)
5️⃣ 분석 관련 시스템 (System)
</br>

## 데이터 분석 수준 진단 구성요소
데이터 분석 수준 진단을 위한 구성요소에는 <span style="color:yellowgreen">분석 준비도</span>와 <span style="color:yellowgreen">분석 성숙도</span>가 있다.
</br>

### 분석 준비도 Readiness
- 구성은 총 6가지 (<span style="color:yellowgreen">분석업무 파악, 인력 및 조직, 분석기법, 분석 데이터, 분석 문화, IT 인프라</span>)
</br>

### 분석 성숙도 Maturity
- <span style="color:yellowgreen">분석 성숙도 모델</span>
   - 조직의 성숙도 평가 도구 : CMMI 모델
   - 성숙도 수준 분류 : 도입단계, 활용단계, 확산단계, 최적화단계
   - 분석 성숙도 진단 분류 : 비즈니스 부문, 조직과 역량 부문, IT부문
   ![](https://velog.velcdn.com/images/chung0916/post/ccda6b15-08cf-4f31-a6b1-52d40b2ac226/image.png)


➡️ <span style="color:yellowgreen">분석 관점에서의 사분면 분석</span>
🌟 '준-정=확-도' 순서로 외우기
![](https://velog.velcdn.com/images/chung0916/post/6c3584b3-84e1-4490-853a-37744d309a07/image.png)

---
</br>

## 데이터 거버넌스
### 데이터 거버넌스 구성3요소
- 원칙
- 조직
- 프로세스
</br>

### 데이터 거버넌스 체계
- 데이터 표준화
- 데이터 관리 체계
- 데이터 저장소 관리
- 표준화 활동
</br>

### 데이터 조직 및 인력방안 수립

**<span style="color:yellowgreen">분석을 위한 3가지 조직 구조</span>**

![](https://velog.velcdn.com/images/chung0916/post/024eae71-71f0-4b72-bad7-d34f258926c2/image.png)

**[집중구조]**
- 전사 분석 업무를 별도의 분석 전담 조직에서 담당

**[기능구조]**
- 별도 분석 조직 X
- 해당 업무 부서에서 분석 수행
- 전사적 차원 X

**[분산구조]**
- 분석조직 인력을 현업부서로 직접 배치
- 전사적 차원 O
- 업무과다 이원화 가능성
</br>

**<span style="color:yellowgreen">분석 과제 관리 프로세스</span>**
**[과제 발굴]**
- 1️⃣ 분석 아이디어 발견
- 2️⃣ 분석과제 후보 제안
- 3️⃣ 분석과제 확정

</br>

**[과제 수행]**
- 4️⃣ 팀구성
- 5️⃣ 분석과제 실행
- 6️⃣ 분석과제 진행관리
- 7️⃣ 결과 공유/개선
