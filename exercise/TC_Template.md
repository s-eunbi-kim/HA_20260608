# 테스트 케이스 작성 양식

이 파일은 RPAS 예제와 SLAS 실습에서 테스트 케이스를 작성하기 위한 양식이다. 요구사항 커버리지와 수행률은 강사가 마지막에 별도로 확인한다.

## 작성 규칙

- `SRS ID`에는 테스트하려는 요구사항 ID를 적는다.
- `Input`은 `항목=값` 형식으로 적고, 여러 값은 쉼표로 구분한다.
- `Expected Result`에는 요구사항을 기준으로 기대되는 출력만 적는다.
- `Actual Result`, `Result`, `Severity`, `Priority`는 HTML 실행 후 작성한다.
- `Severity`, `Priority`는 `Result=Fail`일 때만 작성한다.

## 결과 값

| 항목 | 선택 값 |
|---|---|
| Result | Pass, Fail, N/A, Not Tested |
| Severity | Critical, Major, Minor, Info |
| Priority | P1, P2, P3, P4 |

## 테스트 케이스

| No. | TC ID | SRS ID | Purpose | Pre-condition | Test Procedure | Input | Expected Result | Remarks | Actual Result | Result | Severity | Priority |
|---:|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 |  |  |  |  |  |  |  |  |  | Not Tested |  |  |
| 2 |  |  |  |  |  |  |  |  |  | Not Tested |  |  |
| 3 |  |  |  |  |  |  |  |  |  | Not Tested |  |  |
| 4 |  |  |  |  |  |  |  |  |  | Not Tested |  |  |
| 5 |  |  |  |  |  |  |  |  |  | Not Tested |  |  |

## 작성 블록 형식

```text
TC ID:
SRS ID:
Purpose:
Pre-condition:
Test Procedure:
Input:
Expected Result:
Remarks:
Actual Result:
Result: Not Tested
Severity:
Priority:
```
