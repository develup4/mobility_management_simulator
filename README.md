# mobility_management_simulator

# 프로젝트 소개

modem chip에서 사용하는 프로토콜 스택 소프트웨어에서 NAS(non-acss) 레이어의 MM 모듈(mobil)을 rust로 작성한 내용입니다. 실제 target 하드웨어나 os가 없는 시뮬레이터입니다. CDMA 1x를 기준으로 작성되었습니다.

## 용어 소개

- nas
- mm

## 의의

rust는 임베디드의 미래입니다. nas레이어가 하드웨어와 아주 밀접한 것은 아니지만 실리콘 위에 올라가는 소프트웨어로서 그 미래를 확인하게에 딱입니다.

## 참고스펙

링크

# 시뮬레이션 방법

- 시뮬레이션셔은 모두 Rust의 It(integration test)로 이루어져 있습니다. MM과 인접 레이어가 mock처리 되어 서로 메시지를 주고 받습니다.

## 테스트 항목 리스트

- 부트업
- 레지
- 등등

# 라이센스

안됨
