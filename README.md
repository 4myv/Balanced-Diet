# Balanced Diet (1차 버전)

목표(벌크업 / 다이어트 / 건강관리)에 맞춰 AI가 하루 영양소 목표를 계산하고, 먹은 음식을 분석해 영양 현황을 보여주는 식단 관리 웹 서비스의 **1차 버전**입니다.

> 이 버전은 **서버 없이 브라우저에서 Gemini API를 직접 호출하는 구조**였습니다. 그래서 API 키가 브라우저 코드에 그대로 노출됐고, 기존 키는 폐기했습니다. 지금 이 저장소의 AI 기능은 동작하지 않습니다.
>
> 키를 서버에서 보관하도록 Spring Boot로 다시 만든 2차 버전 → [Balanced-Diet-Spring](https://github.com/4myv/Balanced-Diet-Spring)

## 기술 스택

- HTML, CSS, JavaScript
- Gemini API (브라우저에서 직접 호출)
- 브라우저 localStorage (데이터 저장)

## 문서

- [기획안](Balanced-Diet_기획안.md)
- [개선안](Balanced-Diet_개선안.md) — 사진으로 식단을 기록하는 기능 추가
