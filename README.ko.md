# Tracefield

[English](./README.md)

Tracefield는 Sentinel-2 위성 영상을 기반으로 지역 변화를 분석하는 지리공간 AI 워크스페이스 포트폴리오 자료입니다.

이 저장소에는 프로젝트 소개 자료만 포함됩니다. 소스 코드, 배포 파일, 환경변수 파일, 내부 구현 자산은 포함하지 않습니다.

## 개요

Tracefield는 위성 영상, 격자 기반 지표, 지도 맥락, AI 해석을 하나의 분석 워크스페이스로 연결해 특정 지역의 전후 변화를 살펴볼 수 있도록 설계한 프로토타입입니다.

## 주요 기능

- Sentinel-2 before/after 장면 비교
- 격자 기반 지역 변화 분석
- NDWI, NDVI, 구름, 신뢰도, 변화 점수 계산
- 행정구역 경계와 주변 지도 맥락 연동
- 인터랙티브 지도 워크스페이스
- 셀 단위 AI 해석

## 스크린샷

스크린샷은 [`screenshots`](./screenshots)에 추가합니다.

권장 구성:

- 메인 워크스페이스
- before/after 장면 비교
- 격자 분석 화면
- 셀 단위 AI 해석 패널

## 기술 스택

- Frontend: Next.js, React, Three.js, MapLibre
- Backend: FastAPI, Rasterio, NumPy, Shapely
- AI: OpenAI Responses API
- Deployment: Docker Compose, Caddy

## 프로젝트 범위

제품 흐름, 프론트엔드 워크스페이스, 백엔드 분석 API, 지리공간 처리 파이프라인, AI 리포트 연동까지 하나의 엔드투엔드 프로토타입으로 설계하고 구현했습니다.

## 참고

- 이 저장소는 포트폴리오 검토 목적입니다.
- 소스 코드와 배포 설정은 의도적으로 제외했습니다.
- 분석 결과는 관측 보조용이며 공식 피해 판정, 법적 판단, 안전 판단이 아닙니다.
- 재사용, 재배포, 상업적 이용에 대한 라이선스는 부여하지 않습니다.
