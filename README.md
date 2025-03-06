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
        println("$name -> $number")
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
1. [안드로이드 4대 컴포넌트(Activity, Service, BroadcastReceiver, ContentProvider)](https://quartz-durian-a00.notion.site/4-1a17ecadafa1804881aee3e9a4234d04?pvs=4)    **(박성준)**
2. [Fragment 생명주기](https://www.notion.so/Fragment-Lifecycle-1a3c13dbbe2c802d840be500b996ea80?pvs=4) **(박승준)**
3. [Intent & Intent Filter](https://superohinsung.tistory.com/100) **(오인성)**
4. [Context와 ApplicationContext & Manifest와 Permissions 개념](https://carbonated-raptorex-0ab.notion.site/1-4-Context-ApplicationContext-Manifest-Permissions-1a3446854ab980568da7d11fbcc8d905) **(김성민)**

### **2주차 : UI 및 레이아웃 (2025.02.26)**
1. [Jetpack Compose 개념 및 비교 (XML vs Compose)](https://superohinsung.tistory.com/376) **(오인성)**
2. [ConstraintLayout, LinearLayout, RelativeLayout 비교](https://quartz-durian-a00.notion.site/ConstraintLayout-LinearLayout-RelativeLayout-1a57ecadafa1806b8896e2a12cc0169b?pvs=4) **(박성준)**
3. [RecyclerView와 ListView 그리고 RecyclerView 최적화](https://lean-share-b37.notion.site/RecyclerView-ListView-1a3c13dbbe2c802495e7c06c911080cc?pvs=4) **(박승준)**
4. [ViewBinding & DataBinding](https://carbonated-raptorex-0ab.notion.site/2-4-ViewBinding-DataBinding-1a3446854ab98096bd8ec96da3e82850) **(김성민)**

### **3주차 : Jetpack 라이브러리 심화 (2025.03.05)**
1. [Navigation Component 활용](https://carbonated-raptorex-0ab.notion.site/3-1-Navigation-Component-1aa446854ab980d78015e9e0acb17575) **(김성민)**
2. [Paging3](https://quartz-durian-a00.notion.site/Paging3-1ad7ecadafa180f2a220e69325793a55?pvs=4) **(박성준)**
3. [ViewModel 활용 및 Lifecycle 관리](https://superohinsung.tistory.com/393) **(오인성)**
4. [WorkManager 활용](https://lean-share-b37.notion.site/WorkManager-1acc13dbbe2c80a3991acab2cfbd0c10?pvs=4) **(박승준)**

<방향성 재정립>
