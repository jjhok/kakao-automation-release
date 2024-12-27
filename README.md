# kakao-automation-release
카카오톡 자동 메시지 어플리케이션입니다.

# MacOs 
## 개발자 코드 사인이 되어있지 않습니다. 
1. 압축 후, 응용프로그램(Applications)으로 이동
2. 터미널에서 아래 커맨드를 사용해 코드 사이닝
```
codesign --force --deep --sign - /Applications/KakaoMacro.app
```
3. 정상적으로 동작하지 않을 시 권한 확인

# Windows
