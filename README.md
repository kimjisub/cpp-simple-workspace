# cpp-simple-workspace

대학교 과제와 같은 단일 코드 실행을 위하여 프로젝트를 새로 생성하는 번거로운 작업 없이 간단히 코드 빌드를 도와주는 `Github Codespace` 기반 `Workspace` 입니다.

## 1. Workspace 클론

우측 상단에 이 프로젝트를 `Fork` 하여 본인의 `Repository`에 등록하세요.
또한 설정 페이지에서 환경 이름을 변경하는 것을 추천드립니다.

## 2. Github Codespace 활성화

Fork 받은 본인의 Repository에서 초록색 `Code`를 눌러 `Open with Codespaces`를 클릭하고 새로운 `Codespace`를 생성하세요.

## 3-1. C/C++ 익스텐션 설치

`Ctrl + Shift + X` 를 눌러 `EXTENSIONS` 탭을 열고, `C/C++` 를 검색하여 설치하고, Codespace를 `Reload`해주세요.

## 3-2. gdb 설치

Codespace 에는 기본적으로 cpp 디버깅을 위한 `gdb`가 설치되어있지 않습니다. `Ctrl + ~` 를 눌러 터미널을 열고, 아래 명렁어를 입력해주세요.

```bash
$ sudo apt-get install gdb -y
```

## 4. 개발 시작

프로젝트 `/src` 폴더에 `example` 파일들을 참고하여 단일 코드를 작성하세요.

## 5. 실행 및 디버깅

`F5`를 누르면 현재 포커싱된 파일의 실행 및 디버깅이 시작됩니다. 기본적으로 `DEBUG CONSOLE`이 선택되어 있는데, `TERMINAL`을 클릭하면 코드가 실행되는 화면을 볼 수 있습니다.

## 6. Workspace 업데이트

이 Workspace는 업데이트 될 수 있으며, 업데이트 방법은 추후에 추가될 예정입니다.
