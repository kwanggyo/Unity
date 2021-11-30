# Unity

## Real-time engine

애니메이션, 디자인 또는 그래픽과 같은 시각화를 즉시 생성할 수 있게 해주는 도구

🤔 필요한 이유?

제품 제작 전 디자인 오류를 줄이기 위해 실시간 렌더링이 중요

몰입형 기술로 제품 디자인을 경험해보는 것이 디자인 프로세스에 중요

게임, 디자인, 제조, 건출, 가상현실, 증강현실, 교육, 회의, 영화 등에 이용

### Trends in REAL-TIME Rendering

아우디 디지털 쇼룸(그림자, 반사 등을 구현)

할리우드 VR 체험

아키텍처 렌더링

✅ 오프라인 렌더링 기술 : 실제 시제품을 만드는 기술 or 3D 디자인 툴로 작업하는 것

## Offline Rendering vs Real-time Rendering

### Offline Rendering

노가다로 한땀한땀 디자인해서 메테리얼이나 텍스쳐 같은 것을 씌워주는 것

렌더링 시간

- Image Rendering - 렌더링 시간만(빌드) 8시간 이상
- Video Rendering - 3분 비디오가 37시간

### Real-time Rendering

실시간 엔진을 이용하여 편리하게 만드는 것

렌더링 시간

- Image Rendering - 렌더링 시간이 0.1초
- Video Rendering - 10

새로운 오브젝트를 추가하거나 삭제, 재질이나 조명 변경이 쉽다

종류

- Unreal Engine

  실감 있는 Real-Time 3D(RT3D) 개발 환경을 제공하는 통합형 게임 엔진(ex. 배그)

- Unity Engine

  전세계에서 가장 널리, 많이 사용되는 Real-Time 3D(RT3D) 개발 플랫폼

## Unreal Engine vs Unity Engine

둘 다 온라인 마켓이 존재 → 기본적인 에셋을 구매 가능(import)

Unrreal 마켓이 상대적으로 활성화된 기간이 절반이라 아직까지 적다.

### Unreal Engine

C++

복잡한 로직을 통해 재질이나 음영을 제작해야한다.

처음 할 때 시간이 많이 걸린다.

품질 면에서 고퀄리티를 제공한다.

난이도 상

### Unity Engine

C#

메테리얼이나 쉐이더를 기본적으로 제공(재질, 음영) → 빠르게 개발 가능, 접근성이 좋다.

업데이트를 통해 퀄리트를 높이고 있다.

난이도 중

## 설치

Google Unity 검색 → Unity Hub 다운로드

- Unity Hub : 유니티의 버전을 관리해주는 플랫폼(버전이 매우 많음)
- 버전 호환을 잘 안해주는 단점이 있다. → 버전을 잘 맞춰서 프로젝트를 진행해야 한다.

권장 LTS를 설치하는 것을 추천!

- Microsoft Visual Studio Community 설치(미설치인 경우)
- 윈도우인 경우 Android Build Support 설치(Android SDK & NDK Tools, OpenJDK 설치)
- Documentation 설치

아이폰에서 빌드하려면 맥북을 사용해야 하고 윈도우에서는 안드로이드만 빌드 가능하다.

## 학습

Roll-a-Ball과 같은 교육 프로그램들이 있다.

커뮤니티에 Unity에서 준비하는 발표와 커뮤니티 등이 있다.

블로그에서는 최신 기능과 공지 등을 알려준다.

## 프로젝트 생성

명확하게 알아볼 수 있는 이름으로 만든다.

새로생성에서 화살표를 누룬 뒤 버전을 선택 → 템플릿 선택(2D, 3D 등)

무겁기 때문에 import할 때 많은 시간이 걸린다(이름 실수하지 말 것!!)

가상현실, 증강현실 등도 3D로 구현

프로젝트 경로나 이름에 한글 포함 금지, 띄어쓰기 금지

### File → Build Settings

pc로 하면 exe 파일로 생성된다.

안드로이드와 iOS를 따로 만들 필요 없이 하나의 코드로 같이 빌드할 수 있다(장점)

Univertial Window Platform : 영화에서 사용할 만한 고차원적 렌더링

PS4 : 플레이 스테이션

Xbox : 게임기

✅ 오큘러스에서 이용하려면 안드로이드로 빌드(안드로이드 기반으로 만들어짐)

### Edit

play : 컴파일이라고 생각 - 사용자가 바라보는 화면(게임에서 카메라가 바라보는 화면)

## 실습

🥕 화면을 끌어서 레이아웃 수정이 가능하다.

- 수정한 레이아웃 모습

  ![image-20211130231740763](README.assets/image-20211130231740763.png)

​		Main Camera와 Directional Light는 하나의 오브젝트이다.

SampleScene에서 우클릭으로 3D 객체를 추가할 수 있다(ex. cube, Sphere 등)

생성 후 움직여보면 Game에서도 움직이는 것을 볼 수 있다. → Game을 실행하면 카메라가 바라보는 방향을 바라본다.

회전을 시키려면 툴 박스(메뉴바 아래)를 사용해야 한다.

회전, 스케일, 포지션 등을 변경할 수 있다.

보통 Hand Tool, Move Tool, Rotate Tool, Scale Tool을 많이 사용 → 단축키 순서대로 q, w, e, r

화면 돌리기 : 마우스 오른쪽