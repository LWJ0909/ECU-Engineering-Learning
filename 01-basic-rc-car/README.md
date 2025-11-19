# 01. Basic RC Car

## 📅 기간
Week 1-2 (2025-01-06 ~ 2025-01-19)

## 🎯 목표
라즈베리파이 5 + STM32 기반 RC카 하드웨어 세팅

## 📚 문서
- **[하드웨어 선정 과정의 어려움](./docs/hardware-selection-difficulties.md)** ⭐
  - 실제로 겪은 고민과 해결 과정
  - 부품 호환성, 전압/전류, 납땜 회피 방법
  - 최종 부품 리스트

## 🛠️ 최종 선정 하드웨어
- Wheeltek R3 Ackerman Chassis
- 18650 3S 배터리팩 (Y자형)
- L298N 모터 드라이버
- DC-DC 컨버터 (12V→5V)

[상세 스펙 보기](./docs/hardware-selection-difficulties.md#최종-선정-부품-리스트)

## 📋 체크리스트
- [ ] 모터 드라이버 연결
- [ ] PWM 출력 확인
- [ ] 전진/후진 기능 구현
- [ ] 초음파 센서 테스트
- [ ] UART 통신 확인

## 📝 개발 로그
### 2025-11-19
- 하드웨어 선정 및 부품 주문

## 🔗 관련 링크
- [STM32 Reference Manual](링크)
- [L298N 데이터시트](링크)
