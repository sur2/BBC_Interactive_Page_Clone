# BBC_Interactive_Page_Clone

BBC 인터랙티브 페이지 "코로나19가 바꿀 사무실의 미래" 클론



## 주소

https://sur2.github.io/BBC_Interactive_Page_Clone/



## 알아가는 것

### HTML5

#### 데이터 속성

- ``data-*``: 특정한 데이터를 DOM 요소에 저장하기 위함, DOM 객체의 dataset 속성을 참조하여 데이터속성을 얻을 수 있다. (조회 및 변경 가능)

  ```javascript
  const stepElems = document.querySelectorAll('.step');
  stepElems[i].setAttribute(`data-index${i}`);
  stepElems[i].dataset.index = i; // setAttribute 대신 dataset을 사용해도 같은 효과를 가진다. 
  ```




### CSS

#### transition

- **CSS 트랜지션**은 CSS 속성을 변경할 때 애니메이션 속도를 조절하는 방법을 제공합니다.

#### transform

- **transform**은 요소를 변형 시키는 property입니다.(이동, 확대축소, 회전, 경사)

#### translate

- **translate**는 X축이나 Y축으로 이동할 수 있습니다.



### Javascript

#### Intersection Observer API

- ``new Interseptionobserver(callback)``: 는 타겟 요소와 상위 요소 또는 최상위 document 의 viewport 사이의 intersection 내의 변화를 비동기적으로 관찰하는 방법입니다.

  ```javascript
  const io = new IntersectionObserver((entries, observer) => {
  	console.log(entries);
  });
  io.observe(element);
  ```

  

