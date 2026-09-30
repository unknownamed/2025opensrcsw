<a id="project-overview-added"></a>

[프로젝트 안내](#project-overview-added) · [기존 README 전체 내용](#original-readme-preserved)

# 2025 Open Source Software Practice

**오픈소스 소프트웨어 수업에서 표준 폴더 구조와 Git 작업을 연습한 저장소입니다.**

2025년 10월 16일 실습 기록을 바탕으로 Markdown, 정규표현식, 소스·문서·테스트 폴더 구성을 다뤘습니다.

## 폴더 구성

```text
.
├── src/      # 소스 파일 배치 실습
├── doc/      # 사용법 문서 배치 실습
├── tests/    # 테스트 자료 배치 실습
└── README.md
```

## 확인할 자료

| 경로 | 내용 |
| --- | --- |
| [src/main.py](src/main.py) | 표준 구조를 위한 예시 파일 |
| [src/bug1.py](src/bug1.py) | 버그 수정 작업의 텍스트 기록 |
| [doc/usage.html](doc/usage.html) | 사용법 문서 위치 실습 |
| [tests](tests) | 테스트 파일과 결과 자료의 배치 |

현재 `.py`와 `.html` 파일은 실제 프로그램·테스트·웹 페이지 구현이 아닌 텍스트 자리표시자입니다. 실행할 애플리케이션이나 자동 테스트는 포함되어 있지 않습니다.

## Git 기록 확인

```bash
git clone https://github.com/unknownamed/2025opensrcsw.git
cd 2025opensrcsw
git log --oneline --graph --all
```

---

<a id="original-readme-preserved"></a>

## 기존 README 전체 내용

# 오픈소스 소프트웨어 강의 실습

- 날짜 : 2025년 10월 16일
- 강의 내용 : 표준 폴더 구조
- 실습 내용 : markdown, 정규표현, 표준폴더
