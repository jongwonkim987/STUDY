# CPU 이해

## CPU란?
CPU(Central Processing Unit)는 컴퓨터의 모든 연산을 처리하는 핵심 부품입니다.

## CPU 구성요소

### ALU (Arithmetic Logic Unit, 산술논리연산장치)
- 덧셈, 뺄셈 등 산술 연산 수행
- AND, OR, NOT 등 논리 연산 수행

### CU (Control Unit, 제어장치)
- 명령어를 해석하고 각 장치에 제어 신호를 보냄
- 프로그램 실행 흐름 제어

### 레지스터 (Register)
- CPU 내부의 초고속 임시 저장 공간
- 주요 레지스터:
  - **PC (Program Counter)**: 다음 실행할 명령어 주소 저장
  - **IR (Instruction Register)**: 현재 실행 중인 명령어 저장
  - **MAR**: 메모리 주소 레지스터
  - **MDR**: 메모리 데이터 레지스터

## CPU 동작 사이클 (Fetch-Decode-Execute)
```
1. Fetch   → 메모리에서 명령어를 가져옴
2. Decode  → 명령어를 해석
3. Execute → 명령어를 실행
```

## 클럭(Clock)
- CPU의 동작 속도를 결정하는 신호
- 단위: Hz (GHz = 10억 Hz)
- 클럭 속도가 높을수록 초당 처리 가능한 명령어 수 증가
