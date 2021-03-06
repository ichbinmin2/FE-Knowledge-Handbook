## Semantic Markup 태그를 써야 하는 이유

### 웹 접근성(시각장애인을 위한)

HTML 노드에 어떤 태그가 있더라도 CSS만 제대로 작성하면 디자이너가 그린 것과 똑같은 화면을 만들 수 있다. 일반적 경우라면 아무 문제없다. 다만, 웹 접근성(web accessibility) 차원에서는 문제가 된다. 웹페이지에 일반적인 방법으로 접근할 수 없는 사람들, 특히 시각장애인의 경우는 볼 수 없기 때문에 스크린 리더와 같이 문서를 소리로 바꿔주는 특수한 장치를 이용해야 한다. 웹사이트를 눈이 아닌 귀로 듣는 경험은 어떨지 상상하기 어렵다. 아마 많이 불편할 것이다. 우리가 상상할 수 없다고 간과해서는 안된다. 웹을 만드는 사람이라면 조금이라도 이 불편함을 해소할 수 있도록 도와야 할 의무가 있다.

</br>

### SEO(검색엔진 최적화)

검색엔진이 웹사이트를 방문하면 문서에 포함된 링크를 따라가며 관련 페이지를 모두 방문하고 수집한다. 수집된 문서는 구글 시스템에서 분석 과정을 거친다. 웹사이트에 사용된 태그와 단어의 빈도 등 검색엔진 자체 알고리즘에 따라 주요 키워드를 추출한다. `<div>`와 `<span>`만 사용한 문서는 어떤 부분이 중요한 영역인지 구분이 어렵다. 문서의 제목에 해당하는 `<title>`, 본문 영역 표시 `<main>`, 글 제목 `<h1>` 등 주요 **항목을 별도의 태그로 구분한 문서**가 더 좋은 점수(실제 점수가 있는 건 아니다)를 획득한다. 즉, **검색 결과 상위에 노출된다**. 물론, 검색엔진마다 알고리즘이 다르기 때문에(우리는 알 수 없다) 무엇이 정답이다 말할 수는 없다. 하지만, 상식적으로 생각해도 영역 구분이 확실한 문서가 그렇지 않은 문서보다 더 적절한 키워드를 추출할 것이라 예상할 수 있다. 우리가 웹문서를 의미에 맞게 구성해야 하는 이유다.

</br>

### 개발자들을 위해서(알아보기 쉽게 해서 유지보수성을 높이기)

개발자들이 알아보기 쉬운 태그들을 사용해서 유지보수성을 높인다.

</br>

### 크로스브라우징(Cross Browsing)

크로스브라우징(Cross Browsing) 이란 W3C에서 채택된 **표준 웹기술을 적용해서** 모든 브라우저에 다른 기종의 OS나 HTML 렌더링 기술로 비슷하게 만들어서 **어떤 환경에서도 이상없이 작동되게 만드는 기법과 방법론**을 말합니다. 쉽게 말하자면, 크로스브라우징을 이용하여 다양한 브라우저를 이용하더라도 사이트를 100% 이용할 수 있게 만드는 기술을 말합니다.

</br>

### 결론

![스크린샷 2022-07-14 오후 8 44 01](https://user-images.githubusercontent.com/53133662/178974922-82fc8a48-5bbd-442b-94af-7934d3fdab08.png)

웹은 점점 규모가 커지고, 의미 있는 내용을 추리는데 더 많은 시간과 자원을 사용한다. 정확하고 가치 있는 정보를 탐색하기 위해서는 웹문서가 단순한 코드의 나열이 아니라 의미를 가진 하나의 구조로 작동해야 한다. 단순히 정보가 나열된 문서는 중요한 요소를 구분하기 어렵다. 자칫 크롤러가 엉뚱한 부분을 중요하다고 착각하는 요인이 될 수 있다. 우리가 웹페이지를 구성할 때 적절한 위치에 적합한 요소를 사용해야 이런 오해를 줄일 수 있다. 즉, **시맨틱 태그를 이용해서 의미를 구분할 수 있는 문서를 만들어야 사용자에게 정확한 정보를 제공할** 수 있는 것이다.

</br>

### 출처

---

- [[HTML 바로 알기] Semantic Web을 위한 Semantic Elements](https://poiemaweb.com/html5-semantic-web)
- [[드림코딩] 시맨틱 태그, 중요한 태그들 모음](https://youtu.be/T7h8O7dpJIg)
