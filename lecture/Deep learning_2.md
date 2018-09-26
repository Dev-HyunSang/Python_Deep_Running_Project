# 기본적인 Machine Learnig의 용어와 개념 설명
개념적인 내용

[강의 내용/inflearn(클릭시 접속)](https://www.inflearn.com/course-status-2/)

[강의내용/Youtube(클릭시 접속)](https://youtu.be/qPMeuL2LIqY)
### 목차
- Basic Concepts
- Machine Learning
- Supervised/Unsupervised learning
- Supervised learning
### 1.Basic Concepts
- What is ML
> 강의자: 머신러닝은 무엇일까?
- What is learning?
  - supervised
  - unsupervised
 > 강의자: 또 러닝은 무엇일까?
- What is regression?
> 강의자: 또 러닝의 종류 중 regression은 과연 뭘까?
- What is classiflcation?
> 강의자: 그리고 classiflcation은 과연 뭘까?

> 강의자: 이런한 것들을 이해하시고 알고리즘을 이해 하시면 훨씬 편하기 때문에 이야기 해 보겠습니다.
### 2.Machine Learning
> 강의자: Machine Learning 은 일종의 소프트웨어(프로그램)이다.
- Limitations of explicit programming
  - Spam filter: many rules
  - Automatic driving: too many rules
> 강의자: 롤들을 많다.

Machine learning: 
> "Field of study that gives computers the ability to learn without being explicitly programmed" 
Arthur Samuel (1959)

> 강의자: 어떤 자료나 현상에서 자동적으로 배우면 어떨까? 프로그램이 자동적으로 자신이 학습해서 무언가를 배우는 소프트웨어(프로그램)을 머신러닝이라 한다.
### 3.Supervised/Unsupervised learning
- Supervised learning: 
  - learning with labeled examples - training set
> 강의자: 어떤 하나의 정해져 있는 데이터, 데이터는 labeled가 정해져 있다,  다른 말로는 training set이라 한다.

> 강의자: 이 데이터를 가지고 학습을 하는 것을 Supervised learning 이라 한다.

### 4.Supervised learning
An example training set for four visual categories.

![Alt text](/lecture/img/trainset.jpg)

[출처(클릭시 접속)](http://cs231n.github.io/classification/)
> 강의자: 머신러닝으로 만들어진 프로그램이다, cat,dog라는 labled을 가지고 학습을 하는 것이죠, labled를 가지고 있는 머신 러닝을 Supervised learning 이라 부른다.
### Supervised/Unsupervised learning
- Supervised learning:
  - learning with labeled examples
  - Unsupervised learning: un-labeled bate
  - Google news grouping
> 강의자:  labled이 정해지지 않아있기에 자신들이 보고 유사한 뉴스를 모읍니다, 자기들끼리 유사한 것들끼리 모읍니다. 
  - Word clustering
> 강의자: 비슷한 단어들을 모아봐라

> 강의자: 데이터를 보고 직접 학습하는 걸  Supervised learning이라고 한다.
### supervised learning
- Most common problem type in ML
  - Image labeling: learning form tagged images
  - Emaill spam filter: learning from labeled (spam or ham) Email
  - Predicting exam score: learning from previous exam score and time spent
>강의자: 데이터를 가지고 학습을 하는 것을 supervised learning 이라 합니다.
### Training data set
> 본 설명은 강의자가 직접 그려 설명하였습니다.
영상 5분50초 쪽을 확인 하세요. 
### AlphaGo
> 본 설명은 강의자가 직접 그려 설명하였습니다.
영상 7분28초 쪽을 확인 하세요.
### Type of supervised learning
-P redicting flnal exam score based on time spent
  - regression
> 강의자: 성적을 예측하는 것을 만들라고 하면, 0~100점 까지 많은 수를  예측하는 것을 regression이라고 합니다.
- Pass/non-passs based on time spent
  - binary classiflcation
> 강의자: 문제를 pass 했는냐 pass하지 못 했는지 예측합니다. 분류가 많기에 classiflcation이라 한다.
- Letter grade (A,B,C,E and F) based on time spent
  - multi-label classiflcation
>강의자: 학점을 주려고 하면, 얼마나 공부했는지를 가지고 예측을 하는 프로그램을 만든다면, label이 많다, 이러한 것들을 classiflcation이라 한다.
### Predicting flnal exam score based on time spent
![Alt text](/lecture/img/spent.JPG)
> 직접 그리시면서 강의 하셨습니다, 10분 26초를 확인하세요.
### Pass/non-pass based on time spent
![Alt text](/lecture/img/spent.2.JPG)
> 직접 그리시면서 강의 하셨습니다,  11분 35초를 확인 하세요.
