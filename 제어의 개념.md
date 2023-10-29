## State 개념  
State가 벡터로 확장되면 State space equation이다  

## State Variabel model  
<img width="367" alt="image" src="https://github.com/ces0o/matlab/assets/127365253/d9f94377-38f4-4cac-ab2b-86e29ed467c8">

state vaiable이라는 것은 수학적인 모델을 세워 system계산하고 직관적인 물리적 현상을 수식으로 옮겨 할 수 있도록 할 수 있는 계산을 하는 과정이다.  
컴퓨터를 활용할 때 State가 필요하다 이때 System을 수식화하기 위해 States를 사용한다  
컴퓨터가 쉽게 일할 수 있도록 State를 부여한다 이때 State는 미분방정식 차수에 따라 개수가 정해진다  

## State Variable의 장점  
* 차수를 낮춘다 -> 예를들어 2차 미분방정식을 1차 2개로 연립가능하게 바꾸어준다

## State를 왜 만들어야 할까?  
State는 다차수의 미분방정식을 1차 미분방정식 연립으로 바꾸어준다 이로써 행렬로써 컴퓨터로 빠르게 동작할 수 있게 도와준다  
일차 미분 방정식 2개 연립을 하나의 행렬 1차 방정식으로 바꿀 수 있다. 그래서 State Vector를 사용한다  

## Summary  
* state는 System 내부 상태
* State 정의 -> system 수식에 의미를 부여할 수 있다
* 다차 미분 방정식 -> 1차 행렬 미분 방적식
* 1차 행렬 미분 방정식은 컴퓨터가 쉽게 해결한다


