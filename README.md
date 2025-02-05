# Android_Study

## 면접? 기술?
- 면접 스터디라는 느낌보다는 안드로이드 기술을 각자 공부하고 발표하며 지식을 공유하고 서로 궁금한 것을 공유하고 계속 질문하고 이것들을 전부 기록으로 남기는 느낌의 스터디라고 생각해주시면 편할 것 같습니다.

## 모집 대상
- 한번이라도 안드로이드 앱 개발을 경험했거나, 공부를 해보신 분들 대상
- 안드로이드 앱 개발을 한번도 해보지 않았더라도 열심히 할 분
- 질문을 광적으로 열심히 할 분
- 모집은 선착순으로 정원 5명까지 생각하고 있습니다.

## 진행 방식
- 매주 각자 인원에게 할당된 주제를 공부 (아래 예상 진행도 참고)
    - 기술 개념
    - 예시코드
    - 다른 기술 비교
    - 기술의 장단점
    - 특이 사항 or 에러사항
    - 주요 메서드 or 최적화
    - 인상 깊었던 점 or 내가 생각하기에 중요한 점
- 공부를 해서 정리한 내용을 스터디원에게 발표
- 한명의 발표가 끝나고 스터디원과 Q&A형식으로 질의 응답
- 정리한 내용을 매주 Github ReadMe 에 업로드
    - 이에 대한 내용은 본인 블로그에 다 가져가셔도 됩니다. (타 스터디원 내용까지도 허용)

## 예상 진행도
### **1주차 : 안드로이드 기본 개념 & 컴포넌트**
1. 안드로이드 4대 컴포넌트(Activity, Service, BroadcastReceiver, ContentProvider)
2. 4대 컴포넌트 + Fragment 생명주기
3. Intent & Intent Filter
4. Context와 ApplicationContext
5. Manifest와 Permissions 개념

### **2주차 : UI 및 레이아웃**
1. Jetpack Compose 개념 및 비교 (XML vs Compose)
2. ConstraintLayout, LinearLayout, RelativeLayout 비교
3. RecyclerView와 ListView 그리고 RecyclerView 최적화
4. ViewBinding & DataBinding 
5. Custom View & ViewGroup

### **3주차 : Jetpack 라이브러리 심화**
1. Navigation Component 활용
2. Paging3
3. ViewModel 활용 및 Lifecycle 관리
4. WorkManager 활용
5. DataBinding 심화

### **4주차 : 네트워크 & API 통신**
1. Retrofit2 & OkHttp 기본 개념 및 활용
2. WebSocket 개념과 활용 (실시간 데이터 처리)
3. REST API & JSON & XML 파싱 (Gson, Moshi, kotlinx.serialization)
4. 네트워크 최적화 전략 (캐싱, Retry, Timeout 설정)
5. Ktor (비교 및 서버 통신 활용법)

### **5주차 : 멀티쓰레딩 & 비동기 처리**
1. Coroutine 기본 개념 (launch, async, withContext, Scope & Dispatchers)
2. Flow vs. LiveData (특징 및 활용 비교)
3. RxJava & RxKotlin (비동기 처리 방식 비교)
4. WorkManager (백그라운드 작업 처리)
5. AsyncTask 대체 방법 (Coroutine + WorkManager 활용)

### **6주차 : DI(Dependency Injection) 및 아키텍처 패턴**
1. Koin과 Hilt 비교 (Dagger 포함)
2. Clean Architecture 개념
3. MVVM, MVI, MVP 비교
4. Repository Pattern, Factory Pattern, Builder Pattern
5. Observer Pattern & Singleton Pattern

### **7주차 : 테스트 & 디버깅**
1. Unit Test(JUnit) & Mocking(MockK, Mockito)
2. UI Test(Espresso) & Robolectric
3. LeakCanary & Memory Leak 디버깅
4. StrictMode 활용
5. Android Profiler 활용

### **8주차 : 앱 성능 최적화**
1. ANR(응답 없음) 원인 분석 및 해결
2. RenderThread와 UI 최적화
3. 배터리 최적화 (JobScheduler, WorkManager 활용)
4. 이미지 로딩 최적화 (Coil, Glide, Picasso 비교)
5. APK 사이즈 줄이기 (Proguard, R8, 리소스 압축)

### **9주차 : 보안 & 권한**
1. Proguard & R8
2. 앱 서명 및 인증 방식
3. 보안 저장소(Keystore) 활용
4. SSL Pinning
5. Biometric 인증

### **10주차 : 데이터 저장 및 관리**
1. SharedPreferences
2. RoomDB (Entity, DAO, Database, Migration)
3. DataStore(Proto, Preferences 차이)
4. SQLite 및 사용 사례 비교
5. ContentProvider 활용

### **11주차 : 최신 트렌드 & 최신 기술**
1. Jetpack Compose 고급 (State 관리, Animation)
2. Kotlin Multiplatform (KMP) 개념 및 활용
3. Jetpack Compose vs. SwiftUI 비교
4. Flutter vs. Compose 차이점 및 선택 기준
5. AI 기반 안드로이드 개발 동향 (Google I/O 참고)

### **12주차 : Android CI/CD & Linting & 기타 등등**
1. Lint & DeteKt 활용
2. GitHub Actions 기반 CI/CD 자동화
3. Firebase App Distribution
4. Play Store 배포 과정 및 Best Practice
5. 프로파일링 (CPU, Memory, Network)
