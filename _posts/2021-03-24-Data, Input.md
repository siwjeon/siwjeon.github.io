---
layout: single
title: "데이터형, 입력"
---

[문제 상황]  #Q1  
태성이는 지역아동센터에서 학습보조 자원봉사를 방과 후에 하고 있습니다. 태성이가 멘토링 하고 있는 효연는 국어 문장을 능숙하게 만들지 못합니다.   그래서 문장 생성 규칙을 만들어  연습을 많이 할 수 있도록 예시화면과 같이 문장 성분에 맞는 단어를 입력하면 문장이 완성되 는 프로그램을 작성하려고 합니다. 

~~~python
x=input('주어:')
y=input('꾸밈어:')
z=input('술어:')
print("{}가 {} {}".format(x,y,z))
~~~

|출력 결과|
주어:진달래
꾸밈어:활짝
술어:피었습니다.
진달래가 활짝 피었습니다.

연습 #1

~~~python
x="monkey"
print(type(x))
~~~

|결과|
<class 'str'>

연습 #2

~~~python
y=2.78
b=int(y)
print(b)
~~~

|결과|
2

연습 #3

~~~python
a=float(input('숫자1: '))
b=float(input('숫자2: '))
z=a+b
c=int(z)
print(c)
~~~

|결과|
숫자1: 24.5
숫자2: 12.8

연습#4

~~~python
a=input('숫자: ')
b=input('숫자: ')
c=float(a)*float(b)
c=round(c,2)
print(c)
~~~

|결과|
숫자: 4.456
숫자: 9.345
41.64

연습 #5

~~~python
x=30
y=307
print('x={},y={},x+y={}'.format(x,y,x+y))
~~~

|결과|
x=30,y=307,x+y=337

연습 #6-1

~~~python
f=open('inputData.txt','r',encoding='UTF-8')
a=f.readline()
b=f.readline()
c=float(a)+float(b)
print(c)
~~~

|결과|
333.5956

연습 #6-2

~~~python
f=open('inputData.txt','r',encoding='UTF-8')
a=f.readline()
print(a)
b=f.readline()
print(b)
c=float(a)+float(b)
print(c)
~~~

|결과|
256.3456

77.25
333.5956


