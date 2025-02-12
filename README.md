# Android_Study

## 멤버
- 오인성
- 박승준
- 박성준
- 김성민

## 주차마다 맡을 part 정하는 랜덤함수
```kotlin
import kotlin.random.Random

fun main() {
    val names = listOf("오인성", "박승준", "박성준", "김성민")
    val numbers = (1..4).shuffled(Random)
    
    names.zip(numbers).forEach { (name, number) ->
        println("\$name -> \$number")
    }
}

```

## 진행 방식
- 주 1회 2시간
- 매주 각자 인원에게 할당된 주제를 공부 (아래는 예시)
    - 기술 개념
    - 코드
    - 비교군
    - 기술의 장단점
    - 특이 사항 or 에러사항
    - 주요 메서드 or 최적화
    - 인상 깊었던 점 or 내가 생각하기에 중요한 점
- 공부를 해서 정리한 내용을 스터디원에게 발표
- 한명의 발표가 끝나고 면접 느낌으로 스터디원과 Q&A형식으로 질의 응답
- 정리한 내용을 매주 Github ReadMe 에 업로드
    - 이에 대한 내용은 본인 블로그에 다 가져가셔도 됩니다. (타 스터디원 내용까지도 허용)

## 진행도

### **1주차 : 안드로이드 기본 개념 & 컴포넌트 (2025.02.26)**
1. 안드로이드 4대 컴포넌트(Activity, Service, BroadcastReceiver, ContentProvider) **(박성준)**
2. 4대 컴포넌트 + Fragment 생명주기 **(박승준)**
3. Intent & Intent Filter **(오인성)**
4. Context와 ApplicationContext & Manifest와 Permissions 개념 **(김성민)**

### **2주차 : UI 및 레이아웃 (2025.02.26)**
1. Jetpack Compose 개념 및 비교 (XML vs Compose) **(오인성)**
2. ConstraintLayout, LinearLayout, RelativeLayout 비교 **(박성준)**
3. RecyclerView와 ListView 그리고 RecyclerView 최적화 **(박승준)**
4. ViewBinding & DataBinding **(김성민)**

### **3주차 : Jetpack 라이브러리 심화 (2025.03.05)**
1. Navigation Component 활용
2. Paging3
3. ViewModel 활용 및 Lifecycle 관리
4. WorkManager 활용

### **4주차 : 네트워크 & API 통신 (2025.03.12)**
1. Ktor & Retrofit2 & OkHttp 기본 개념 및 활용
2. WebSocket 개념과 활용 (실시간 데이터 처리)
3. REST API & JSON & XML 파싱 (Gson, Moshi, kotlinx.serialization)
4. 네트워크 최적화 전략 (캐싱, Retry, Timeout 설정)

### **5주차 : 멀티쓰레딩 & 비동기 처리 (2025.03.19)**
1. Coroutine 기본 개념 (launch, async, withContext, Scope & Dispatchers)
2. Flow vs. LiveData (특징 및 활용 비교)
3. RxJava & RxKotlin (비동기 처리 방식 비교)
4. AsyncTask 대체 방법 (Coroutine + WorkManager 활용)

### **6주차 : DI(Dependency Injection) 및 아키텍처 패턴 (2025.03.26)**
1. Koin과 Hilt 비교 (Dagger 포함)
2. Clean Architecture 개념 + Repository Pattern, Factory Pattern, Builder Pattern
3. MVVM, MVI, MVP 비교
4. Observer Pattern & Singleton Pattern

### **7주차 : 테스트 & 디버깅 (2025.04.02)**
1. Unit Test(JUnit) & Mocking(MockK, Mockito)
2. UI Test(Espresso) & Robolectric
3. LeakCanary & Memory Leak 디버깅
4. StrictMode 활용 & Android Profiler 활용

### **8주차 : 앱 성능 최적화 (2025.04.09)**
1. ANR(응답 없음) 원인 분석 및 해결
2. RenderThread와 UI 최적화
3. 배터리 최적화 (JobScheduler, WorkManager 활용)
4. 이미지 로딩 최적화 (Coil, Glide, Picasso 비교)

### **9주차 : 보안 & 권한 (2025.04.16)**
1. Proguard & R8
2. 앱 서명 및 인증 방식
3. 보안 저장소(Keystore) 활용
4. Biometric 인증

### **10주차 : 데이터 저장 및 관리 (2025.04.23)**
1. SharedPreferences
2. RoomDB (Entity, DAO, Database, Migration)
3. DataStore(Proto, Preferences 차이)
4. ContentProvider 활용

### **11주차 : 최신 트렌드 & 최신 기술 (2025.04.30)**
1. Jetpack Compose 고급 (State 관리, Animation)
2. Kotlin Multiplatform (KMP) 개념 및 활용
3. Flutter vs. Compose 차이점 및 선택 기준
4. AI 기반 안드로이드 개발 동향

### **12주차 ~ 15주차 Side Project : Android CI/CD & Linting & 기타 등등 (2025.05.01 ~ 2025.05.21)**
1. Lint & DeteKt 활용
2. GitHub Actions 기반 CI/CD 자동화
3. Firebase App Distribution
4. Play Store 배포 과정 및 Best Practice

## Q&A
- Why? 안드로이드 공식문서? ⇒ 안드로이드는 트렌드가 가장 빠른 기술 중 하나로 시중에 책들이 이러한 트렌드를 따라오지 못하고 있습니다. 그래서 가장 신뢰성이 있는 것은 공식문서 입니다.

## 참고자료
- 안드로이드 공식문서와 구글을 통해서 양질의 블로그를 참고하는 것을 추천합니다.
