# grade-calculator

<br/>

## 프로젝트 개발 이유

JAVA를 공부하면서 객체지향적으로 프로그램을 만드는 법을 연습하기 위해서 시작한 프로젝트입니다.

<br/>

<br/>

## 프로젝트 내용

대학생들의 성적을 입력 받아, 학점을 계산해주는 프로그램입니다. 

학점 평가 방식은 학생의 전공 과목인 경우와 아닌 경우 다르게 평가됩니다. 

<br/>

전공 평가 방식

100~95 : S

~90 : A

~80 : B

~70 : C

~60 : D

F

<br/>

전공 과목이 아닌경우, 해당 과목의 평가방식에 따라 결정됩니다. 

ex) A,B,C,D,F 방식 또는 pass/fail 방식

<br/>

<br/>

## Class Diagram

![class-diagram1](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Hyuk1996/grade-calculator/master/gradeCalculator/uml/gradeCalculatorUml.puml)

![class-diagram1](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Hyuk1996/grade-calculator/master/gradeCalculator/uml/gradeCalculatorUml2.puml)

![class-diagram1](http://www.plantuml.com/plantuml/proxy?src=https://raw.githubusercontent.com/Hyuk1996/grade-calculator/master/gradeCalculator/uml/gradeCalculatorUml3.puml)

<br/>

<br/>

## 프로젝트 폴더 구성

~~~bash
gradeCalculator
> src  // 소스코드
	> grade // 학점 평가관련 interface, clas
		> GradeEvaluation.java
		> BasicEvaluation.java
		> MajorEvaluation.java
	> school  // 주요 class들이 위치한 package
		> report // 학생 성적을 보고해주는 class가 위치한 package
			> GenerateGradeReport.java
		> School.java
		> Score.java
		> Student.java
		> Subject.java
	> test // test가 이루어지는 곳
		> TestMain.java
	> utils 
		> Define.class  // 프로그램에서 사용되는 상수 class 
> uml  // class diagram
	> gradeCalculatorUml.puml
	> gradeCalculatorUml2.puml
	> gradeCalculatorUml3.puml
~~~

