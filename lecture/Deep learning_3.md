# ML lec 02-Linear Regression의 Hypothesis와 cost 

## 설명

본 강의에는 다소 많은 수학적 원리와 내용 등이 있습니다.

수학적 원리를 다소 글로 쓰기엔 그래서, 공식만 사진으로 붙여 드립니다.

아래 링크에서 강의를 확인  해 주세요.

[Inflearn 강의(클릭시 접속)](https://www.inflearn.com/course-status-2/)

[Youtube 강의(클릭시 접속)](https://www.youtube.com/watch?v=Hax03rCn3UI&feature=youtu.be)

-------------------------------------------------------------------
## 목차
- Achnowledgement
- Predicting exam score: regression
-------------------------------------------------------------------
## Achnowledgement
- Andrew Ng's ML class
    - https://class.coursera.org/ml-003/lecture
    - http://www.holehouse.org/mlclass (note)
- Convolutional Neural Networks for Visual Recognition.
    - http://cs23ln.github.io/
- Tensorflow
    - https://www.tensorflow.org
    - https://github.com/aymericdamien/TensorFlow-Examples
-------------------------------------------------------------------
## Predicting exam score: regression

![Alt text](/lecture/img/socre.JPG)

-------------------------------------------------------------------
## Regression (data)

![Alt text](/lecture/img/data.JPG)

--------------------------------------------------------------------
## Regression (presentation)

![Alt text](/lecture/img/presentation.JPG)

--------------------------------------------------------------------
## (Linear) Hypothesis

![Alt text](/lecture/img/linear.JPG)

### H(x)=Wx+b

![Alt text](/lecture/img/linear2.JPG)

--------------------------------------------------------------------
## Which hypothesis is better?

![Alt text](/lecture/img/linear2.JPG)


![Alt text](/lecture/img/4.JPG)

---------------------------------------------------------------------
## Cost function

- How flt the line to our(training) data

### H(x)-y

![Alt text](/lecture/img/4.JPG)

---------------------------------------------------------------------
## Cost function 2 & Math

- How flt the line to our (trainging) data

![Alt text](/lecture/img/6.JPG)

![Alt text](/lecture/img/5.JPG)

### H(x)-y

![Alt text](/lecture/img/4.JPG)

--------------------------------------------------
## Cost function 3 & Math

![Alt text](/lecture/img/7.JPG)

![Alt text](/lecture/img/8.JPG)

----
## Goal:Minimize cost

![Alt text](/lecture/img/9.JPG)
