# Input

* input 또는 textarea 요소의 값이 변경될 때 이벤트가 발생한다
* change 이벤트와 유사하나, 2가지 차이점이 존재한다.
* `input` 이벤트 : 요소값 변경 직후에 발생함
  select 요소에서는 작동하지 않는다
* `change` 이벤트: 요소값 변경 후 요소가 포커스를 잃으면 발생한다.
  select 요소에서도 작동한다.



## input 구문

* JS 속성방식
  object.oninput = function(){함수이름()};
* JS 메서드 방식
  object.addEventListener('input',함수이름)

