# Tracefield

[English](./README.eng.md)

## 개요

Tracefield는 Sentinel-2 위성 영상을 기반으로 지역 변화를 분석하는 지리공간 AI 워크스페이스입니다. 위성 영상, 격자 기반 지표, 지도 맥락, AI 해석을 하나의 분석 워크스페이스로 연결해 특정 지역의 전후 변화를 살펴볼 수 있도록 설계되었습니다.

## 주요 기능

- Sentinel-2 before/after 장면 비교
- 격자 기반 지역 변화 분석
- NDWI, NDVI, 구름, 신뢰도, 변화 점수 계산
- 행정구역 경계와 주변 지도 맥락 연동
- 인터랙티브 지도 워크스페이스
- 셀 단위 AI 해석

## 기술 스택

- Frontend: Next.js, React, Three.js, MapLibre
- Backend: FastAPI, Rasterio, NumPy, Shapely
- AI: OpenAI Responses API
- Deployment: Docker Compose, Caddy

프론트엔드 워크스페이스, 백엔드 분석 API, 지리공간 처리 파이프라인, AI 리포트 연동까지 하나의 엔드투엔드 프로토타입으로 설계하고 구현했습니다.

## 참고

- 분석 결과는 관측 보조용이며 공식 피해 판정, 법적 판단, 안전 판단에 사용할 수 없습니다.
