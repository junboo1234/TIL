# GitHub 공부 기록

## 주요 기능 설명

### 1. Repository - 저장소, 레포
* local -> GitHub 저장소로 올려서 관리함.

### 2. Commit - 코드 저장, 커밋
* 코드 작업의 기록 단위.

### 3. Branch - 브랜치
* Main을 건드리지 않고 새로 만드는 독립작업 공간.

### 4. Pull Request - 풀 리퀘스트
* 내가 만든 Branch 코드를 원본에 합치는 과정.
* PR으로도 불림.

### 5. Issue - 이슈
* 프로젝트에서 해결해야 할 문제나 작업 목록.

---

## 충돌 관리

### 상황 판단
* Git은 시간 순으로 기록을 보기 때문에 Main이 바뀌지 않았다면 Main에서 Branch에서 Pull Request를 해도 상관이 없다.
* 하지만 내가 Main에서 Branch한 이후 다른 사람이 Main을 수정 했다면 Merge를 해야 함.

### Merge (충돌 해결 옵션)
* Accept Current Change: 내 코드만 남기기.
* Accept Incoming Change: 상대방 코드만 남기기.
* Accept Both Changes: 둘다 남기기, 위 아래로 나란히 배치.
* Compare Changes: 두 코드 양옆에 두고 비교하기.

### 팁
* Merge를 자주 하지 않으려면 작은 작업 단위로 Commit 해야 한다.
* Main으로 Pull을 자주 해야 한다.
