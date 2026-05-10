<div align="center">

# Furigana Workspace

### 일본어 읽기, 듣기, 번역, OCR, 학습, 로컬 AI 작업을 한 화면 안에 묶은 Windows용 포터블 워크스페이스

[![Windows](https://img.shields.io/badge/Windows-Portable-2f7dff?style=for-the-badge&logo=windows)](https://github.com/luebece/furiganaworkspace/releases/latest)
[![Release](https://img.shields.io/github/v/release/luebece/furiganaworkspace?include_prereleases&style=for-the-badge&label=Latest)](https://github.com/luebece/furiganaworkspace/releases/latest)
[![Local First](https://img.shields.io/badge/Local--first-Study%20OS-19c37d?style=for-the-badge)](#local-first)
[![Preview](https://img.shields.io/badge/Channel-Preview-f2b84b?style=for-the-badge)](https://github.com/luebece/furiganaworkspace/releases/latest)

**Furigana Workspace는 단순한 후리가나 도구가 아니라, 일본어 콘텐츠를 읽고, 듣고, 번역하고, 정리하고, 학습하는 흐름 전체를 하나의 데스크톱 환경 안에 넣은 개인용 일본어 학습 OS입니다.**

[최신 버전 다운로드](https://github.com/luebece/furiganaworkspace/releases/latest) · [업데이트 메타데이터](./latest.json) · [배포 파일 정보](./dist/latest.json)

</div>

---

## 왜 Furigana Workspace인가

일본어 공부를 하다 보면 도구가 계속 흩어집니다.

- 소설은 브라우저에서 읽고
- 모르는 단어는 따로 검색하고
- 후리가나는 다른 확장 프로그램에 맡기고
- 영상 자막은 또 다른 프로그램으로 만들고
- 음성 재생, OCR, 번역, 메모, 단어장, 캡처는 전부 다른 창에서 처리합니다

Furigana Workspace는 이 흐름을 하나로 합칩니다.
브라우저, 후리가나 결과창, 학습 데이터, 메모장, 파일 관리자, 이미지/PDF/오디오 뷰어, 오피스 도구, 로컬 AI 도구를 작업표시줄과 창 시스템 안에서 OS처럼 다룹니다.

---

## 주요 기능

### 브라우저 중심 일본어 읽기

- 일본어 웹페이지에 후리가나를 직접 표시
- 드래그한 문장을 한국어로 선택 번역
- 본문을 후리가나 결과창으로 보내기
- 소설 사이트 바로가기 메뉴
- 자동 스크롤, 페이지 캡처, 방문 기록, 검색 제안
- 2분할 브라우징과 탭별 분할 상태 유지
- YouTube 전체화면, F11 페이지 전체화면, 창/탭 복원 흐름 지원

### 후리가나 결과창과 음성 재생

- 문장 단위 후리가나 표시
- 전체 재생, 문장별 재생, 정지 지점부터 재생
- VOICEVOX / Aivis Speech 기반 캐릭터 음성 연동
- 음성 엔진이 없을 경우 설치 안내 및 경로 자동 탐색
- 읽기 흐름이 끊기지 않도록 문장 음성 준비 흐름 최적화

### 학습 데이터베이스

- JLPT 단어장, 한자 목록, 문법장
- N1/N2/N3/N4/기타/전체 필터
- 외래어, 고유명사, 인명, 지명 등 카테고리 필터
- JMDict / JMnedict 기반 대규모 단어 데이터 활용
- 한자 부수별 탐색과 상세 정보
- 10분 루틴 퀴즈, 오답/정답 피드백, 타자 연습
- 학습창 내부 창 분리, 최소화, 이동, 크기 조절 지원

### 영상, OCR, 자막

- 영상 화면의 글자 OCR 추출
- GPU 기반 OCR 흐름 연동
- YouTube URL 기반 자동 모드
- Parakeet / Whisper 계열 STT 흐름 지원
- 결과창에 후리가나가 달린 문장으로 표시

### 로컬 AI와 창작 도구

- Ollama 기반 로컬 LLM 대화/번역 흐름
- ComfyUI 기반 삽화 생성
- 결과창 또는 삽화창에서 직접 이미지 생성
- 설치가 필요한 엔진은 실행 시 안내하고 경로를 자동 탐색

### 노래 모드

- YouTube 링크 기반 노래 처리
- Demucs 기반 보컬/반주 처리
- RVC 모델을 이용한 캐릭터 음성 변환
- 피치, shifts, 품질 프리셋 조정
- 결과 음원 재생 및 다운로드
- GPU 사용 환경에서 고품질 처리 가능

### 워크스페이스 OS

- 바탕화면, 시작 메뉴, 작업표시줄, 창 최소화/복원
- 창 위치 이동, 크기 조절, 탭 위치 변경
- 메모장 탭, 파일 관리자, 이미지/PDF/오디오/TXT 뷰어
- 게임 런처와 외부 실행파일 등록
- HWP 문서 편집기, PPT/DOCX/LibreOffice 기반 미리보기 흐름
- 배경 이미지 위치/크기/밝기 조절

---

## Local-first

Furigana Workspace는 가능한 한 로컬 실행을 우선합니다.

- 후리가나 처리와 브라우저 기능은 앱 내부에서 동작
- 음성, STT, 이미지 생성, 노래 변환은 사용자가 설치한 로컬 엔진을 우선 사용
- 유료 클라우드 API 과금 없이 구성 가능
- 필요한 외부 엔진은 기능을 사용할 때 설치 안내로 연결

단, YouTube 다운로드, 모델 다운로드, GitHub 업데이트, 웹 검색처럼 네트워크가 필요한 기능은 해당 서비스에 연결됩니다.

---

## 다운로드

1. [Releases](https://github.com/luebece/furiganaworkspace/releases/latest) 페이지로 이동합니다.
2. `FuriganaWorkspace-win-unpacked-*.zip` 파일을 다운로드합니다.
3. 원하는 위치에 압축을 풉니다.
4. `FuriganaWorkspace.exe`를 실행합니다.

설치형 앱이 아니라 포터블 빌드입니다.
압축을 푼 폴더를 그대로 옮겨서 사용할 수 있습니다.

---

## 업데이트

앱 내부의 다시시작/업데이트 흐름은 `latest.json`을 기준으로 최신 릴리즈를 확인하도록 설계되어 있습니다.

- 최신 릴리즈 정보: [`latest.json`](./latest.json)
- 배포용 dist 메타데이터: [`dist/latest.json`](./dist/latest.json)
- 실제 대용량 ZIP 파일은 GitHub Release asset으로 제공됩니다

---

## 권장 환경

| 항목 | 권장 |
| --- | --- |
| OS | Windows 10 / Windows 11 |
| CPU | 최신 멀티코어 CPU |
| RAM | 16GB 이상 권장 |
| GPU | NVIDIA GPU 권장, 노래/RVC/이미지 생성 사용 시 특히 유리 |
| 저장공간 | 기본 앱 외에 AI 모델/음성 엔진/캐시를 위한 여유 공간 필요 |

일반 브라우징, 후리가나, 학습 기능은 가볍게 사용할 수 있습니다.
RVC, Demucs, ComfyUI, STT 모델은 설치 모델과 설정에 따라 GPU/저장공간 요구량이 크게 달라집니다.

---

## 저장소 구조

이 저장소는 **배포용 저장소**입니다.

- 소스 전체를 보관하는 저장소가 아닙니다.
- 대용량 앱 바이너리는 GitHub Release asset으로 업로드됩니다.
- `latest.json`과 `dist/latest.json`은 앱의 업데이트 확인용 메타데이터입니다.
- `win-unpacked/`, `*.zip`, `*.asar` 같은 대용량 산출물은 Git에 직접 커밋하지 않습니다.

---

## 상태

Furigana Workspace는 빠르게 확장 중인 preview 채널 앱입니다.
일부 기능은 로컬 설치 환경, GPU, 외부 엔진, 모델 파일 상태에 따라 동작 방식이 달라질 수 있습니다.

그래도 목표는 명확합니다.

> 일본어 콘텐츠를 읽는 순간부터, 이해하고, 듣고, 기록하고, 복습하고, 창작까지 이어지는 전 과정을 하나의 워크스페이스 안에서 끝내는 것.

---

<div align="center">

**Furigana Workspace**
일본어 학습을 위한 개인용 로컬 워크스페이스.

</div>
