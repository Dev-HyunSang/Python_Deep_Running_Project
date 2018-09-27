# ML lec 02-Linear Regression의 Hypothesis와 cost 

## 설명

본 강의에는 다소 많은 수학적 원리와 내용등이 있습니다.

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
    - https::://github.com/aymericdamien/TensorFlow-Examples
-------------------------------------------------------------------
## Predicting exam score: regression

![Alt text](/lecture/img/socre.jpg)

-------------------------------------------------------------------
## Regression (data)

![Alt text](/lecture/img/data.jpg)

--------------------------------------------------------------------
## Regression (presentation)

![Alt text](/lecture/img/presentation.jpg)

--------------------------------------------------------------------
## (Linear) Hypothesis

![Alt text](/lecture/img/linear.jpg)

### H(x)=Wx+b

![Alt text](/lecture/img/linear2.jpg)

--------------------------------------------------------------------
## Which hypothesis is better?

![Alt text](/lecture/img/linear2.jpg)


![Alt text](/lecture/img/4.jpg)

---------------------------------------------------------------------
## Cost function

- How flt the line to our(training) data

### H(x)-y

<img width="100" height="100" href="/lecture/img/4.jpg">

---------------------------------------------------------------------
## Cost function 2 & Math

- How flt the line to our (trainging) data

![Alt text](/lecture/img/6.jpg)

![Alt text](/lecture/img/5.jpg)

### H(x)-y

<img width="100" height="100" href="/lecture/img/4.jpg">

--------------------------------------------------
## Cost function 3 & Math

![Alt text](/lecture/img/7.jpg)

![Alt text](/lecture/img/8.jpg)

----
## Goal:Minimize cost

![Alt text](/lecture/img/9.jpg)