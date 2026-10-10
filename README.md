# lilkimbab

컴퓨터공학을 전공하며 AI 학습 서비스와 데이터베이스 인덱스를 구현하고 있습니다.
컴퓨터비전과 로보틱스를 공부하며, 시각 정보를 로봇의 인식과 동작에 연결하는 방법에 관심이 있습니다.

## Projects

### [Proofy — AI 수능 수학 학습 서비스](https://github.com/lilkimbab/Proofy)

진단, 학습 계획, 칠판 강의, 풀이 평가를 연결한 학습 서비스 프로젝트입니다.

- **학습 계획:** 진단 결과와 개념별 숙련도, 목표 점수, 시험까지 남은 기간을 반영해 일별 강의·문제·복습 계획을 생성합니다.
- **칠판 강의:** 수식·그래프를 단계적으로 표시하는 React UI와 강의 장면·선택 객체를 반영하는 질문 응답을 구현했습니다. LLM 미설정 시에는 기본 응답으로 동작합니다.
- **풀이 평가:** SymPy로 수식의 동치 여부와 풀이 단계를 평가하고, 오류 유형을 피드백과 오답노트로 연결합니다.

**Tech:** Next.js · React · TypeScript · FastAPI · Python · SymPy  
**Code:** [학습 계획](https://github.com/lilkimbab/Proofy/blob/main/apps/api/app/domain/planner.py) · [풀이 평가](https://github.com/lilkimbab/Proofy/blob/main/apps/api/app/domain/evaluator.py) · [칠판 UI](https://github.com/lilkimbab/Proofy/blob/main/apps/web/components/board-scene.tsx)

### [CSE321 Project 1 — 데이터베이스 인덱스 구현·비교](https://github.com/lilkimbab/cse321-project1)

Python으로 B-tree, B\*-tree, B+-tree를 구현하고 연산 성능과 구조를 비교한 프로젝트입니다.

- **트리 구현:** B-tree 노드 분할, B\*-tree 형제 노드 재분배와 2→3 분할, B+-tree 리프 연결을 구현했습니다.
- **탐색·삭제:** 키 탐색과 범위 질의, 삭제 후 재균형 및 구조 검증을 구현했습니다. B\*-tree의 삭제는 B-tree 구현을 상속합니다.
- **실험:** 차수 3·5·10에서 삽입, 10,000건 탐색, 범위 질의, 2,000건 삭제를 비교하고, 범위 선택도 1%·10%·50%에 따른 실행 시간을 측정합니다.

**Tech:** Python · 표준 라이브러리  
**Code:** [트리 구현](https://github.com/lilkimbab/cse321-project1/blob/main/cse321_ass1.py) · [실험 실행](https://github.com/lilkimbab/cse321-project1/blob/main/run_experiments.py)

## Languages

![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Scala](https://img.shields.io/badge/scala-%23DC322F.svg?style=for-the-badge&logo=scala&logoColor=white)
