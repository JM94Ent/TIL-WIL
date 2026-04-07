

# 1. 해야할 것

1. 게임산업 뉴스 읽기 
2. 개인 공부

[유튜브: 도시 레벨디자인 10팁](https://youtu.be/LCacISZnHME?si=4tb_yGW4Q3dzYiKA)

# 2. 오늘 배운 것


<details>
<summary>접기/펼치기</summary>




---

# 🔷 전체 구조 (포트폴리오 설계)

JM 포폴은 이렇게 구성됩니다:

## 1️⃣ Core Mechanics (핵심 시스템)

* 벽타기
* 로프 이동
* 점프 연결

---

## 2️⃣ Interaction System

* 트리거
* 이벤트 발생
* 이펙트

---

## 3️⃣ Level Application

* 실제 레벨에 적용
* Flow 설계

---

👉 이 3개가 연결되어야
**“실무형 레벨디자이너”**로 보입니다.

---

# 🔶 Blocktober 4주 계획 (JM 맞춤)

---

## 🟩 Week 1: 벽타기 시스템

### 목표

👉 “벽을 타고 이동 가능”

### 구현 요소 (BP)

* Line Trace (벽 감지)
* Character Attach
* 이동 제한 (좌우/상하)

### 이벤트

* 벽 붙을 때:

  * 파티클
  * 사운드

📌 포인트
👉 “붙는 순간 손맛”

---

## 🟩 Week 2: 로프 시스템

### 목표

👉 “스윙 이동”

### 구현 요소

* Physics Constraint or Timeline
* 입력 기반 좌우 이동

### 이벤트

* 점프 시:

  * 카메라 쉐이크
  * 바람 이펙트

---

## 🟩 Week 3: 액션 퍼즐

### 목표

👉 “이동 + 상호작용”

구성:

* 벽타기 → 스위치 → 문 열림 → 이동

### BP 핵심

* Trigger Box
* Event Dispatcher

---

## 🟩 Week 4: 통합 레벨

### 목표

👉 “하나의 플레이 경험”

구성:

* 벽타기
* 로프
* 전투 or 함정

👉 Flow 완성

---

# 🔷 Unreal Blueprint 구조 (실전 설계)

JM이 써야 할 구조입니다:

---

## ✅ 1. Interaction BP (기본 틀)

```
Player Overlap Trigger
    → Event Call
        → Door Open
        → Particle Spawn
        → Sound Play
```

---

## ✅ 2. 벽타기 구조

```
Tick
 → LineTrace (앞쪽)
 → Hit Wall?
     → Attach to Wall
     → Disable Gravity
     → Allow Movement (Axis 제한)
```

---

## ✅ 3. 로프 구조

```
Input Jump
 → Attach to Rope
 → Apply Swing Force
 → Release → Launch Character
```

---

# 🔶 무료 에셋 (Unreal 추천)

👉 Epic 공식 무료만 써도 충분합니다

* Epic Games 제공:

  * **Infinity Blade Assets**
  * **Paragon Assets**
  * Starter Content

👉 출처: Epic Games Marketplace (공식 무료 콘텐츠 정책)

---

# 🔥 이펙트 & 이벤트 설계 핵심

JM이 차별화되는 포인트입니다:

---

## 1️⃣ “행동 → 피드백” 반드시 연결

* 벽 붙음 → 먼지 + 사운드
* 로프 점프 → 바람 + 카메라

👉 안 하면 “허공에서 움직이는 느낌”

---

## 2️⃣ 타이밍 설계

* 즉시 반응 (0초)
* 지연 반응 (0.3초)

👉 타이밍으로 손맛 결정됨

---

## 3️⃣ 시각적 가이드

* 벽타기 가능한 곳:

  * 색 다르게
  * 패턴 넣기

👉 Star Wars Jedi: Fallen Order에서 대표적으로 사용

---

# 🔷 포트폴리오 구성 (JM용 핵심)

---

## 🎯 제목

“Traversal Action Level with Blueprint Systems”

---

## 구성

### 1. 시스템 설명

* 벽타기 구현 방식
* 로프 구현 방식

---

### 2. 레벨 적용

* Flow 설명
* 플레이 영상

---

### 3. 이벤트 설계

* Trigger → 결과

---

### 4. 문제 해결

* 버그
* 개선 과정


</details>





# 3. 개선


<details>
<summary>접기/펼치기</summary>



</details>


# 4. 생각



