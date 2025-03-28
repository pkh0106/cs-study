# operating system

**1. 운영체제 구조**

- 운영체제의 기본 구조
- 커널, 시스템 콜

> [운영체제 구조 정리](./01-os-structure/main.md)

**2. 프로세스 관리**

- 프로그램과 프로세스의 차이
- 프로세스의 상태 전이가 일어나는 이유와 조건
- PCB의 구조와 컨텍스트 스위칭
- 프로세스 간 통신(IPC)

> [프로세스 관리 정리](./02-process-management/main.md)

**3. 프로세스 동기화**

- 임계 영역
- 동기화 도구(뮤텍스와 세마포어의 차이, 모니터)

> [프로세스 동기화 정리](./03-process-synchronization/main.md)

**4. 스레드**

- 프로세스와 스레드의 차이
- 사용자 수준 스레드/커널 수준 스레드
- 스레드 풀
- 멀티스레딩, 스레드 상태, 스레드 동기화

> [스레드 정리](./04-threads/main.md)

**5. CPU 스케줄링**

- CPU 스케줄링이 필요한 이유
- 스케줄링이 발생하는 상황
- 스케줄링 알고리즘의 목표와 알고리즘의 종류

> [CPU 스케줄링 정리](./05-cpu-scheduling/main.md)

**6. 데드락**

- 데드락이 발생하는 4가지 조건
- 데드락을 다루는 방법
- 실제 운영체제에서 적용하는 방법

> [데드락 정리](./06-deadlock/main.md)

**7. 메모리 관리**

- 메모리 관리를 하는 이유
- 단일 프로그래밍 환경과 다중 프로그래밍 환경에서의 관리 기법
- 메모리 할당 알고리즘
- 캐시 메모리

> [메모리 관리 정리](./07-memory-management/main.md)

**8. 가상 메모리 개념**

- 가상 메모리가 등장한 이유
- 페이징, 세그먼테이션
- 페이지 폴트 처리 과정

> [가상 메모리 개념 정리](./08-virtual-memory-concept/main.md)

**9. 가상 메모리 성능**

- 페이지 교체 알고리즘
- 스래싱
- TLB

> [가상 메모리 성능 정리](./09-virtual-memory-performance/main.md)

**10. 동기/비동기와 블로킹/논블로킹**

- 동기/비동기의 개념과 차이
- 블로킹과 논블로킹의 개념과 차이
- 동기/비동기와 블로킹/논블로킹의 차이
- 2개의 조합으로 만들어지는 총 4개 I/O 모델
- 실제 사용 사례(Node.js의 비동기 논블로킹 I/O, Nginx의 비동기 논블로킹 방식으로 동시성 처리 등)

> [동기/비동기와 블로킹/논블로킹 정리](./10-sync-async-blocking-nonblocking/main.md)

**11. 파일 시스템**

- 파일 시스템이 필요한 이유
- 파일 시스템의 구성 요소
- 파일 시스템이 실제로 디스크에 데이터를 저장하는 방식
- 저널링, 캐시와 버퍼링

> [파일 시스템 정리](./11-file-system/main.md)

**12. 디스크 스케줄링**

- 디스크의 물리적 특성
- 디스크 스케줄링 알고리즘
- 현대의 디스크 스케줄링 알고리즘

> [디스크 스케줄링 정리](./12-disk-scheduling/main.md)
