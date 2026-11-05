# 키즈 플레이 v1.0

갤럭시탭용 오프라인 안드로이드 게임 앱입니다. 기존 KidsPlay_Game.html을 Android WebView에 포함합니다.

- 메모리 게임: 4×4 / 5×5 / 6×6
- 숫자 공부: 세기, 찾기, 덧셈, 뺄셈
- 앱 버전: 1.0 (versionCode 1)
- 패키지: com.kidsplay.app

## 스마트폰에서 APK 받기
1. GitHub 저장소의 **Actions** 탭을 엽니다.
2. **Build Kids Play APK** 워크플로를 선택합니다.
3. 가장 최근의 성공한 실행을 엽니다.
4. 페이지 아래 **Artifacts**에서 **KidsPlay-v1.0-debug**를 다운로드합니다.
5. ZIP 압축을 풀고 app-debug.apk를 갤럭시탭에 설치합니다.

GitHub Actions가 성공하면 디버그 서명된 APK가 생성됩니다. 최초 설치 시 Android의 '알 수 없는 앱 설치' 허용이 필요할 수 있습니다.

## 빌드
JDK 17, Android SDK 35, Gradle 8.9, Android Gradle Plugin 8.7.3.

`gradle assembleDebug`
