<!-- 
    title: RTX 업스케일러 - NVIDIA RTX 기술을 활용한 AI 비디오 화질 개선
    description: NVIDIA Maxine SDK를 사용하여 저화질 및 오래된 비디오를 변환합니다. AI 기반 초해상도와 아티팩트 감소 기능을 RTX 실시간 가속과 함께 제공합니다. 사용하기 쉬운 Gradio 인터페이스로 원활한 비디오 화질 개선이 가능합니다.
    keywords: 비디오 업스케일링, NVIDIA RTX, AI 비디오 화질 개선, 초해상도, 아티팩트 감소, 빈티지 비디오 복원, Maxine SDK, Gradio GUI, 비디오 처리
    author: ABUS
    version: 1.0.0
    last-updated: 2025-2-3
    product-type: 비디오 화질 개선 소프트웨어
    platforms: Windows
    technology-stack: NVIDIA RTX, Maxine SDK, Super Resolution, Artifact Reduction, Gradio, CUDA, ffmpeg
    license: 상용
-->

# RTX 업스케일러: NVIDIA RTX 기술을 활용한 AI 비디오 화질 개선 📺

🌍 [English](../README.md) ∙ [한국어](README.kor.md) ∙ [日本語](README.jpn.md) ∙ [中文简体](README.zh.md) ∙ [中文繁體](README.tw.md) ∙ [Deutsch](README.de.md) ∙ [Español](README.es.md)

NVIDIA RTX 기술을 활용하여 낮은 화질의 비디오를 고품질로 변환하세요. RTX 업스케일러는 NVIDIA Maxine Video Effects SDK를 기반으로 한 사용자 친화적인 Gradio GUI 프로그램으로, AI 기반 초해상도 및 아티팩트 제거 기능을 제공합니다.

[![GitHub Release](https://img.shields.io/github/v/release/abus-aikorea/rtx-upscaler)](https://github.com/abus-aikorea/rtx-upscaler/releases)

<p align="center">
  <img style="width: 90%; height: 90%" src="images/main_page.eng.png?raw=true" alt="NVIDIA RTX Video Super Resolution Web UI Interface"/>
</p>  

## 🚀 주요 기능

- **AI 기반 화질 개선**: NVIDIA의 최첨단 초해상도 및 아티팩트 제거 기술 활용
- **실시간 GPU 가속**: RTX 성능을 활용한 빠른 처리 속도
- **직관적인 인터페이스**: 간단한 Gradio 기반 GUI로 쉬운 조작
- **오래된 영상 복원**: 구형 영상을 현대적 품질로 업그레이드
- **원클릭 설치**: 설치가 간편하고 이동이 자유로움

## 🎯 시스템 요구사항

- **운영체제**: Windows 10/11 (64비트) 전용
- **GPU**: NVIDIA RTX 시리즈 (20, 30, 40, 50) 또는 NVIDIA Quadro RTX
- **VRAM**: 최소 4GB (8GB 권장)
- **RAM**: 최소 4GB
- **저장공간**: 20GB 여유공간
- **인터넷**: 설치 및 업데이트에 필요
- **드라이버**: 최신 NVIDIA 그래픽 드라이버 필수

## 🛠️ 설치 가이드

### 빠른 시작
1. 🚀 `configure.bat` 실행 (최초 1회)
   - 필수 구성 요소 설치 (git, ffmpeg, CUDA)
   - 처음 한 번만 실행, 인터넷 연결 필요
   
2. 🚀 `start.bat` 실행
   - Web-UI와 함께 RTX 업스케일러 실행
   - 첫 실행 시 자동 설치 진행

### 업데이트
- `update.bat` 실행으로 Python 가상환경 업데이트
- 기존 사용자에게 권장

### 제거
- `uninstall.bat` 실행으로 모든 구성요소 제거
- 또는 설치 폴더 삭제 (이동식 설치)

## 💻 기능 소개

### RTX 스튜디오 인터페이스
- 통합 YouTube 다운로더
- AI 기반 아티팩트 제거
- 초해상도 화질 개선
- 비디오 압축 도구
- 모든 ffmpeg 호환 형식 지원
- 맞춤형 출력 설정 (wav, flac, mp3)
- 조절 가능한 모드, 스케일, CRF, 프리셋 옵션

## ⚠️ 주의사항

- **무료 체험판 제한**: 최대 60초 비디오 처리 가능
- **GPU 호환성**: NVIDIA RTX 20 시리즈 이상만 지원
- **필수 소프트웨어**:
  - 최신 [NVIDIA 그래픽 드라이버](https://www.nvidia.com/ko-kr/drivers/)
  - [NVIDIA Video Effects SDK](https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-sdk/resources/)

## 🔧 문제 해결

브라우저가 자동으로 실행되지 않는 경우:
1. start.bat을 사용하여 프로그램 재시작
2. 표시된 주소로 수동 접속 (예: http://127.0.0.1:7892)

Windows 보안 경고 관련:
- "추가 정보" 클릭 후 "실행" 선택
- 필요한 경우 파일 속성에서 "차단 해제" 설정

## 📬 문의 및 지원

- 이메일: abus.aikorea@gmail.com
- 공식 웹사이트: https://abuskorea.imweb.me
- 아마존 구매: US, Japan, Singapore, UAE
- 제품 데모: [유튜브 채널](https://www.youtube.com/watch?v=z8g8LMhoh_o&list=PLwx5dnMDVC9Y7dAjm9r26CZUw1uU5VIeq)
- 네이버 스마트스토어: 
  - [소프트웨어](https://smartstore.naver.com/abus/products/10385660040)
  - [솔루션](https://smartstore.naver.com/abus/products/10298346364)

## 🙏 감사의 말

* NVIDIA Maxine SDK: <https://docs.nvidia.com/deeplearning/maxine/vfx-sdk-system-guide/index.html>
* yt-dlp: <https://github.com/yt-dlp/yt-dlp>
* gradio: <https://github.com/gradio-app/gradio>

## ©️ 저작권

<img src="images/ABUS-logo.jpg" width="100" height="100"> by [ABUS](https://abuskorea.imweb.me)