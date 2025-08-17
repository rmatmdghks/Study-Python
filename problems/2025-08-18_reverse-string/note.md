# 문자열 뒤집기 (reverse-string)
- 플랫폼: 프로그래머스 Lv0
- 링크: https://school.programmers.co.kr/learn/courses/30/lessons/120822


## 초기 코드 , 막힌 지점
```python
def asdf():
    return asdf
- 처음에는 for문으로 뒤집으려 했는데 코드가 너무 길어짐

## 시도한 접근
1. for문 + 문자열 더하기
2. reversed() + join
3. 최종: 슬라이싱 [::-1]

## 배운 점
- 문자열 뒤집기는 `s[::-1]`
- 문자열은 불변이므로 슬라이싱이 가장 간단

## 최종 코드
```python
def solution(s: str) -> str:
    return s[::-1]
