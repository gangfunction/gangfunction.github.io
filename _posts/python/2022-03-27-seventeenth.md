---
layout: single
title: "음..,넘파이 ,클래스 복습"
categories: python
tag: numpy
---

## 넘파이란?
행렬이나 일반적으로 대규모 다차원의 배열을 쉽게 처리할수잇도록 지원하는 파이썬의 라이브러리.


### @property 데코레이터 사용
- 함수 내부를 수정하지 않고 기능에 추가를 할때 쓰는 것... 
- 다른 함수를 인자로 받는것을 한다.

### 퍼스트 클래스함수
--> 함수 자체를 인자로써 다른 함수에 전달하거나 다른 함수의 결과값으로 리턴할수 있다.

#### 클로저- 함수가 종료후 다른함수의 로컬변수를 기억할수가 있는지 알수있다.
```python
def superman(power):
	def marry_jane():
		print('i know you',power)
	return marry_jane

clark=superman('power overwall')
print(clark)
clark()

```
데코레이터- 함수 자체를 수정하지 않으면서 사람들이 많이 사용하는 기능들을 파있넝 ㅣ제공하는 방법으로 변경할때 사용

함수를 할당하고 나서 함수가 호출후 종료가 되고나서도 할당된 변수가 함수를 재활용이 가능하다.


인스턴스는 저장한 순서대로 출력된다.

인스턴스명을 알아야 출력이 가능한데 인스턴스 명을 모르고 출력할수 있는 방법

브로드캐스팅

ndarray도 시퀀스 데이터 타입이다. 인덱스 이용해서 자리값 불러올수 있다.

().reshape(-1,2)
에서 -1가 존재하는 이유는 무엇인가?

슬라이싱 

넘파이도 기본적으로 랜덤메소드를 제공.... 

넘파이 시드값
랜덤 수 추출 random.choice


넘파이는 원칙적으로 지원하지않음

넘파이 슬라이싱
[:,:]
첫번째 행, 두번쨰 열

np.median(a)

np.std(a)

np.cumsum(a)

np.argmin(a)
np.argmax(a)

np.argsort


