# 프로그래밍(1) - Python Basics

2026학년도 1학년 1학기 교과목 실습 코드 저장소입니다.

- **학과:** 글로벌시스템융합과
- **담당교수:** 정영철
- **학점/시수:** 6학점 / 6시수

## 과목 목표

Python을 활용하여 구조적 프로그래밍의 핵심 원리를 익히고, 논리적 사고를 바탕으로 문제를 분석하고 해결하는 코딩 능력을 기른다.

## 과목 구성

| 챕터 | 주제 |
|------|------|
| ch01 | 주석 (Comments) |
| ch02 | 변수 (Variables) |
| ch03 | 연산자 (Operators) |
| ch04 | 흐름제어 (Flow Control) |
| ch05 | 자료구조 (Data Structures) |
| ch06 | 함수 (Functions) |

## 디렉토리 구조

```
chXX-토픽명/
├── examples/       # 교재 예제 코드
├── practice/       # 실습 문제
└── practice-sol/   # 실습 풀이

reports/
├── reportXX/       # 레포트 문제
└── reportXX-sol/   # 레포트 풀이
```

## 사용 방법

### 1. 저장소 클론

```bash
git clone https://github.com/gsc-lab/course-python-basic.git
```

### 2. 연습용 폴더 생성

클론한 프로젝트 안에 `test/` 폴더를 만들어 개인 연습용으로 사용하세요.

```bash
cd course-python-basic
mkdir test
```

- `test/` 폴더는 `.gitignore`에 등록되어 있어 GitHub에 업로드되지 않습니다.
- 자유롭게 파일을 만들고 코드를 연습할 수 있습니다.
- 예시: `test/hello.py`, `test/my_practice.py` 등 원하는 이름으로 생성

### 3. 학습 순서

1. 각 챕터의 `examples/` 폴더에서 교재 예제 코드를 확인하고 실행합니다.
2. `test/` 폴더에서 예제 코드를 직접 따라 작성하며 연습합니다.
3. `practice/` 폴더의 실습 문제를 풀어봅니다.
4. 풀이는 수업 후 `practice-sol/` 폴더에 공개됩니다.
5. 레포트 문제는 `reports/` 폴더에서 확인하고, 풀이는 마감 후 공개됩니다.
