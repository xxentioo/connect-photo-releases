# Connect Photo

Windows용 네이티브 이미지 편집기입니다. Material Design 3 Dark, 레이어·마스크·조정·PSD 입출력과 MCP 자동화를 제공합니다.

## 다운로드

[릴리스 안내](https://github.com/xxentioo/connect-photo-releases/releases/tag/v0.7.0-connect.2)

- [Windows x64 MSI 설치본](https://github.com/xxentioo/connect-photo-releases/releases/download/v0.7.0-connect.2/connect-photo-0.7.0-connect.2-windows-x64.msi)
- [Windows x64 포터블 ZIP](https://github.com/xxentioo/connect-photo-releases/releases/download/v0.7.0-connect.2/connect-photo-0.7.0-connect.2-windows-x64-portable.zip)
- [SHA-256 목록](https://github.com/xxentioo/connect-photo-releases/releases/download/v0.7.0-connect.2/connect-photo-0.7.0-connect.2-windows-x64-sha256.txt)

현재 공개 버전은 **0.7.0-connect.2 early alpha**입니다. Windows x64용입니다.

- **MSI**: 설치 후 시작 메뉴의 Connect Photo를 실행합니다.
- **Portable ZIP**: 폴더 전체를 압축 해제한 다음 `connect-photo.exe`를 실행합니다. 설정과 복구 데이터는 실행 파일 옆 `ConnectPhotoData`에 저장됩니다.
- **SHA-256**: 함께 제공되는 `sha256.txt`로 다운로드 파일의 해시를 확인할 수 있습니다.

이 설치본은 전자서명되지 않았습니다. 그래픽 드라이버로 시작이 어려우면 `connect-photo.exe --safe-gpu`를 사용할 수 있습니다.

## 이번 업데이트

Codex 모델 선택, GPT Image 2 이미지 생성, 생성 결과를 편집 가능한 레이어로 추가하는 기능을 제공합니다. 기본 화면에는 오른쪽 에이전트·레이어 패널과 두 별 에이전트 버튼이 표시됩니다. Cp 로고를 적용하고 정보 창·시작 화면·도움말의 불필요한 설명과 GitHub 연결을 정리했습니다.

레이어 PSD는 배경·인물·소품을 요소별로 생성해 구성하는 방식입니다. 완성된 한 장의 이미지를 자동으로 의미별 레이어로 분해하는 기능은 포함되지 않습니다.

## Agent 패널

Window > Agent에서 Codex 또는 Claude 제공자를 선택합니다. 해당 CLI는 사용자가 별도로 설치하고 로그인해야 합니다. 자동 탐색에 실패하면 Preferences > Agent에서 실행 파일 경로를 지정합니다. Connect Photo는 CLI 계정, 구독이나 로그인을 제공하지 않습니다.

`connect-photo-cli.exe`는 이미지 편집 명령과 MCP 브리지를 위한 별도 도구입니다.

## 라이선스

프로그램은 MIT OR Apache-2.0입니다. 두 배포 형식의 `licenses/`에 프로젝트 라이선스, 글꼴·아이콘 등의 고지와 출처가 함께 들어 있습니다.

## 호환성

문서 보안 프로그램이 설치된 개발 PC에서 테스트 파일을 반복 교체하던 중 테스트 프로세스가 종료됐습니다. 원인은 아직 확인되지 않았습니다. 별도 Windows 검증 환경에서는 설치본·포터블 각각 12회 저장을 통과했지만, 해당 개발 PC의 호환성은 추가 확인이 필요합니다. 보호 설정은 변경하지 않았습니다.

이 저장소는 설치 파일을 공개 배포하기 위한 저장소입니다.
