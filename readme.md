# ReadMe

- 해당 저장소는 Udemy의 [Complete Android Jetpack Bootcamp(With Jetpack Compose)2022](https://www.udemy.com/course/android-architecture-componentsmvvm-with-dagger-retrofit/) 강의를 학습한 내용을 정리하는 곳입니다.
- 이미 알고 있던 내용도 다시 복습합니다.


## jetpack data binding : 자주 묻는 질문

1) 모든 Android 프로젝트에 findViewById()를 사용할 수 있습니까?

    예, findViewById()를 사용하여 모든 Android 프로젝트를 빌드할 수 있습니다. 그것이 우리가 안드로이드 초창기에 하던 일입니다.

현대적인 방법을 사용하여 코드 라인 수를 줄이고, 코드를 더 읽기 쉽게 만들고, 성능을 개선하고, 코드 기반을 더 조직화할 수 있습니다.



2) 코틀린 합성이란?

   Kotlin Synthetic(extensions)은 개발자가 findViewById()를 피하고 해당 ID를 사용하여 뷰를 직접 호출하는 데 사용하는 단축 방법이었습니다. 앱 수준 gradle 파일에 이를 위한 Kotlin 플러그인을 추가했습니다. 이 방법은 예기치 않은 오류가 많이 발생했기 때문에 Google은 2021년에 사용 중단했습니다.



3) 뷰바인딩이란?

뷰 바인딩은 데이터 바인딩의 경량 버전입니다. 뷰만 코드에 바인딩합니다.

그러나 데이터 바인딩은 두 가지 모두를 수행합니다. 코드에서 뷰로 데이터를 바인딩하고 뷰를 코드에 바인딩합니다. 그리고 데이터 바인딩에는 다른 많은 응용 프로그램이 있습니다.

데이터 바인딩을 배우면 뷰 바인딩이 훨씬 더 배우기 쉬울 것입니다(전혀 새로운 것은 없습니다).

프로젝트의 요구 사항을 고려하여 데이터 바인딩(또는 뷰 바인딩)을 사용할지 여부를 결정해야 합니다.

이 과정의 후반부에서 뷰 바인딩에 대해 논의하고 전체 프로젝트 예제에 뷰 바인딩을 사용할 것입니다 .



4) Jetpack Compose란 무엇입니까?

jetpack compose를 사용하면 XML을 사용할 필요가 없습니다. Kotlin을 사용하여 뷰를 생성하는 모든 코드를 작성합니다.

그러나 Jetpack Compose를 사용하려면 매우 좋은(고급 수준) Kotlin 및 Android 개발 지식이 필요합니다.

XML은 사용하기가 훨씬 빠르고(드래그 앤 드롭, 속성 창,..) 배우기/이해하기 쉽습니다.

Jetpack compose는 매우 높은 성능과 많은 다른 이점을 가지고 있습니다(Kotlin Multiplatform).

동일한 프로젝트에서 XML과 Compose를 모두 사용할 수 있습니다.

XML을 사용하여 만든 수백만 개의 Android 프로젝트가 있습니다(지속적인 유지 관리가 필요함). 일부 개발자만 새 프로젝트에 Compose를 사용합니다. 따라서 Android 개발자는 XML 방식과 Compose 방식을 모두 마스터해야 합니다.

Jetpack 작성 기본 사항과 실용적인 응용 프로그램을 가르치기 위해 이 과정에 많은 섹션을 추가했습니다. 이 과정의 후반부에서 제트팩 작성을 마스터할 수 있습니다.

