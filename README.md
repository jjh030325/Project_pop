# untitled4

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
# Project-pop


**1. 기본 개요***
“밥 줘”는 우울증을 케어하기 위한 다양한 기능이 접목된 어플리케이션이다. Todo check리스트, 한 줄 일기와 감사일기, 동물 시뮬레이터 등의 기능을 활용해 우울한 감정을 해소하고, 국내의 우울증 문제를 완화하는 것에 초점을 두어 개발한다.

**2. 어플리케이션 ui**
2.1 홈 화면 - 고양이 시뮬레이션
- 이미지: 가상의 고양이 이미지 표시
- 상태 표시: 고양이의 현재의 상태(포만감, 친밀도 등) 표시
- 상호작용
- 버튼: 고양이와의 상호작용을 위한 버튼
- 먹이주기 버튼: 고양이에게 먹이를 줄 수 있는 버튼
- 놀아주기 버튼: 고양이와 놀아줄 수 있는 버튼
- 동물 이미지는 사용자와 상호작용할 때마다 변하며, 동물의 상태를 시각적으로 보여줌

2.2 체크리스트
- 우울을 개선하는데 도움이 된다고 제시되어지는 항목들을 To-Do List 항목으로 넣어서 사용자가 항목들을 수행했는지 안 했는지 눈으로 볼 수 있게 함
- 각 항목들을 수행할 때 마다 익일 지급되는 보상이 얼마가 될지 눈으로 볼 수 있게 함
- 오늘 기분이 어땠는지 눈으로 볼 수 있도록 체크리스트를 배치함

2.3 일기
- 텍스트 박스: 일기, 감사일기 작성
- 저장 버튼: 작성한 일기 저장

2.4 Store 기능 및 인벤토리 기능
- 체크리스트와 일기작성 등의 기능을 수행하여 얻은 리워드를 사용할 수 있도록하는 상점페이지
- 탭을 나누어서 항목별로 사용자가 쉽게 찾을 수 있도록 함
- 구매한 내역들은 가방에서 그대로 보여짐

**3. 사용 기술**
-	언어: Dart
-	프레임워크: Flutter
-	통합 개발 환경
  - Android Studio
