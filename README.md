# kakao-automation-release
카카오톡 자동 메시지 어플리케이션입니다.

# MacOs 
## 개발자 코드 사인 필수 
1. 압축 후, 응용프로그램(Applications)으로 이동합니다.
2. 터미널에서 아래 커맨드를 사용해 코드 사이닝합니다.
```
codesign --force --deep --sign - /Applications/KakaoMacro.app
```
3. 정상적으로 동작하지 않을 시, 아래 두 권한이 부여되어 있는지 확인합니다.
   - 개인정보 및 보안 > 화면 및 시스템 녹음
   - 개인정보 및 보안 > 손쉬운 사용

# Windows
- 개발 환경이 없어서 충분히 테스트 되지 않았습니다. 
- 압축 후 보안 프로그램에 의해 실행파일이 삭제될 수 있습니다. 보안 설정 해제 후 사용할 수 있습니다.
