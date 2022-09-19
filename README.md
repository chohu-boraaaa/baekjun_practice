# baekjoon_practice

## 추천 문제
- https://covenant.tistory.com/224

## 입출력 정리
- https://paris-in-the-rain.tistory.com/72
- 한 줄씩 입력된다고 보면 된다.
- 한 줄로 띄어쓰기로 되어 있을 때 : list(map(int, input().split()))
- 여러 줄로 되어 있을 때 : [int(input()) for _ in range(입력개수)]

## 개인적으로 어려웠던 문제
- 🥉이진수 (기존의 bin함수 말고 이진수 구하는 알고리즘까지 짜서 시간이 더 오래걸렸다)

## 주의할점
- 잘 한 것 같은데 코드 실행이 잘 안된다면 오타가 있을 수 있으니 찬찬히 확인해보기!
- 파이썬에서 리스트 복사하고 싶을 때 대입 연산자를 이용하면 주소를 공유하게 되는 것. 진정한 복사가 아님. 따라서 리스트이름.copy()와 같이 복사를 해줘야 함
