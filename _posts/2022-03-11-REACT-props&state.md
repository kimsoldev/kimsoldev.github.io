#1. REACT PROPS
간단하게 컴포넌트에서 컴포넌트로 전달하는 데이터를 말한다. 함수를 매개변수를 이용해서 효율적으로 재사용할 수 있는 것 처럼 컴포넌트의 .PROPS도 컴포넌트를 효율적으로 재사용할 수 있게 해준다. 
PROPS에 있는 데이터는 문자열인 경우를 제외하면 모두 중괄호{ }로 값을 감싸야 한다는 점.



#2. state와 클래형 컴포넌트
###특징
동적 데이터(말 그대로 변경될 가능성이 있는 데이터)를 다룰 때 사용한다. 객체를 예로 들면 객체의 구성 요소 중 일부가 있다가 없을 수도 있고, 구성 요소가 하나였다가 둘이 될 수도 있다. props는 그런 데이터를 다루지 못한다. 그래서 state를 쓴다. state는 클래스형 컴포넌트에서 사용할 수 있는 개념으로 클래스형 컴포넌트를 공부해야한다.

#####함수형 컴포넌트는 return문이 JSX를 반환한다. 하지만 클래스형 컴포넌트는 render()함수가 jsx를 반환한다. 
그리고 리액트는 클래스형 컴포넌트의 render()함수를 자동으로 실행시켜 준다. 
[STATE를 쓰는 이유 CONST나 LET을 쓰지 않고](http://https://ko.javascript.info/class#ref-739)
state는 객체 형태의 데이터야 반드시 클래스형 컴포넌트 안에서, 소문자로 적는다.

#3. 알아야하는 생명주기 함수

###Mount마운트로 분류하는   MJJJJJKKKKK  
render()
constructor()
constructor()

###Update업데이트로 분류한 생명주기 함수
componentDidUpdate()

###Unmount언마운트로 분류한 생명주기
componentWillUnmount()