# OpenSourceSW
오픈소스SW개론

### 1. `top`
`top` 명령어는 시스템의 실시간 성능 상태를 보여줌. 현재 실행 중인 프로세스와 CPU, 메모리 사용량을 실시간으로 확인할 수 있음.

#### 주요 키 조작:
- `q`: top 명령어 종료
- `h`: 도움말 표시
- `k`: 프로세스 종료 (PID 입력 필요)
- `1`: CPU 코어별 사용량 표시
- `P`: CPU 사용량 기준으로 정렬
- `M`: 메모리 사용량 기준으로 정렬

### 2. `ps`
`ps` 명령어는 현재 시스템에서 실행 중인 프로세스 목록을 한 번에 보여줌. 다양한 옵션을 사용하여 특정 프로세스 정보를 상세히 조회할 수 있음.

#### 주요 옵션:
- `ps aux`: 모든 사용자와 관련된 프로세스 정보를 자세히 출력
- `ps -ef`: 풀 포맷으로 모든 프로세스 정보를 출력

### 3. `jobs`
`jobs` 명령어는 현재 쉘 세션에서 백그라운드 작업의 상태 및 목록을 보여줌. 백그라운드로 실행된 작업의 리스트와 상태를 쉽게 확인할 수 있음.

#### 주요 상태:
- `Running`: 작업이 실행 중
- `Stopped`: 작업이 일시 중단
- `Done`: 작업이 완료

### 4. `kill`
`kill` 명령어는 프로세스를 종료시키는 데 사용됨. 프로세스 ID(PID)를 지정하여 특정 프로세스를 종료할 수 있음.

#### 사용 예:
```bash
kill <PID>
```
#### 주요 옵션:
- `kill -9 <PID>`: 강제 종료(SIGKILL)
- `kill -15 <PID>`: 정상 종료(SIGTERM)

### 요약
- `top`: 실시간 시스템 성능 모니터링
- `ps`: 실행 중인 프로세스 확인
- `jobs`: 백그라운드 작업 상태 확인
- `kill`: 특정 프로세스 종료
