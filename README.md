# Flutter SharedPreferences 예제

## 프로젝트 소개 👨‍💻

이 Flutter 애플리케이션은 **SharedPreferences** 패키지를 사용하여 간단한 데이터 저장 및 로딩 기능을 구현. 사용자는 텍스트 필드에 이름을 입력하고 버튼을 눌러 이름을 저장할 수 있으며, 저장된 이름은 화면에 표시됨. 이 프로젝트를 통해 SharedPreferences를 사용한 데이터 저장 및 로딩 방법을 실습하였음.
## 주요 기능 ✨

1. **이름 저장**: 텍스트 필드에 입력된 이름을 SharedPreferences를 사용하여 저장
2. **저장된 이름 표시**: 저장된 이름을 화면에 표시
3. **데이터 로딩**: 앱 시작 시 저장된 이름을 로드하여 표시

## 주요 파일 구조 🗂️

- **`main.dart`**: 애플리케이션의 진입점이며, `MyHomePage`를 홈 화면으로 설정.
- **`MyHomePage`**: 사용자로부터 이름을 입력받고 저장 및 로딩 기능을 제공

## 사용된 패키지 📦
[shared_preferences](https://pub.dev/packages/shared_preferences): 간단한 데이터 저장을 위한 패키지
