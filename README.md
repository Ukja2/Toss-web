### Toss 메인 홈페이지 클론
- HTML & CSS 사용

### 주로 사용한 기능
- semantic tag
- flexbox를 이용한 주축, 교차축 설정 및 활용 과 borderl line에 대한 여러가지 속성
- 이미지 배치를 위한 z-index, position의 absolute와 relative 
- background image에 대한 그라데이션, 위치 속성
- 글자 간격 크기조절을 위한 line-height 속성
  

### 클론 코딩을 하면서 어려움을 느꼈던 부분
- 내부요소인 이미지와 그의 부모요소인 container의 크기에 대한 개념이 어려웠다.
  예를 들어 container라는 width:100%인 부모요소 내에 image라는 자식요소의 크기 때문인지 postion 값의 문제인지
  웹페이지 내에서 갑자기 가로 스크롤이 생성되었는데, 이러한 이유를 명확히 알아내지 못했다.
  -> 해결방안을 모색한 결과 크게 세 가지 해결 방안으로 1.image 자체 크기의 조절 2.postion:absolute일때 일정 범위를 넘어가지 않게 하는 방법
     3. overflow 속성의 값을 hidden으로 하는 방법이 있다고 판단된다.

- 각 요소의 class 이름 지정에 대한 기술이 부족하다. 처음 진행된 웹페이지 코딩인 만큼 크게 신경쓰지 않았던 부분이지만
  결과물을 만들고 난 후 class 이름을 살펴보았을 때 각 class에 대한 연관성을 찾기 힘들었고, 이를 개선시킬 필요가 있다고 느꼈다.

- flexbox 속성에 대한 개념 미숙
  코드를 재검토 해보았을 때 부모요소인 flexbox 중 정렬이 불필요한 곳에 속성을 적용한 부분이 다소 존재한다.
  원하는 배치를 하기 위해 내부요소 뿐 아니라 부모요소에 justify-content, align-content의 속성을 다양하게 적용하다보니 이러한 상황이 발생한 것 같다.


### 결과물
### 1.Header
![image](https://github.com/Ukja2/Toss-clone-coding/assets/157056310/e55f1f7a-78ea-4290-95fc-3e8f69e04649)

### 2.Main
![image](https://github.com/Ukja2/Toss-clone-coding/assets/157056310/7309afaf-1786-411b-bdfd-c79ac3de948e)

### 3.Footer
![image](https://github.com/Ukja2/Toss-web/assets/157056310/782c47af-f9bf-4c1e-8c34-8a1fac9d976f)


