![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)
# 📚 Algorithm Storage 

<br />

--- 

## 📂 카테고리별 알고리즘
| 카테고리 | 알고리즘 | 난이도 | 상태 |
| :--- | :--- | :---: | :---: |
| **Sorting** | Bubble, Quick, Merge | Low/Mid | ✅ |
| **Search** | Binary Search, DFS/BFS | Mid | 🏗️ |
| **Dynamic Programming** | Knapsack, LIS | High | ⏳ |
| **Graph** | Dijkstra, Kruskal | High | ❌ |

---
## 📑 목차
- [정렬 (Sorting)](#1-정렬-sorting)
- [탐색 (Search)](#2-탐색-search)
---

## 📝 알고리즘 요약

### 1. 정렬 (Sorting)
데이터를 특정 순서대로 나열하는 알고리즘입니다.

#### [Quick Sort]
- **정의:** 분할 정복(Divide and Conquer) 전략을 사용하는 효율적인 정렬 알고리즘.
- **구현 방식:**
  1. 리스트에서 하나의 원소(Pivot)를 고릅니다.
  2. 피벗보다 작은 요소는 왼쪽, 큰 요소는 오른쪽으로 옮깁니다.
  3. 분할된 두 리스트에 대해 재귀적으로 반복합니다.
- **시간 복잡도:** - 평균: $O(n \log n)$
  - 최악: $O(n^2)$
- **코드 보기:** [QuickSort.py](./Sorting/QuickSort.py)

---

### 2. 탐색 (Search)
원하는 데이터를 효율적으로 찾는 방법입니다.

#### [BFS - 너비 우선 탐색]
- **정의:** 루트 노드(혹은 임의의 노드)에서 시작해 인접한 노드를 먼저 탐색하는 방법입니다.
- **구현 방식:** 큐(Queue) 자료구조를 사용하여 방문한 노드를 차례로 저장하고 꺼냅니다.
- **코드 보기:** [BFS.py](./Search/BFS.py)

---

## 🚀 학습 규칙
1. 매주 최소 2개의 알고리즘 구현 및 정리
2. 코드에는 반드시 주석으로 시간 복잡도와 로직 설명 포함
3. 백준/프로그래머스 관련 문제 링크 첨부
