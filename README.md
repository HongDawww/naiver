# naiver: N이버 클론 코딩 

제작 기간 : 10/28 ~ 11/05

✔️ html / css 활용

# Header 
![header](https://github.com/HongDawww/naiver/assets/142575028/d6ff74fd-5d27-4f17-b31d-c8061aebf10d)
> 
>
❕ icon제작 목록 :figma를 활용하여 아이콘 제작


> 햄버거 버튼
> 
> ![header-hamberger](https://github.com/HongDawww/naiver/assets/142575028/57095db7-89dc-4541-b89b-40bff2fe3be1)
>
> neiver logo
>
> ![input-logo](https://github.com/HongDawww/naiver/assets/142575028/639c8067-6cce-44d2-91d3-b5ede0eb398e)
> 
> neiverpay logo
>
>  ![naiverpay](https://github.com/HongDawww/naiver/assets/142575028/cfef5258-c96f-4630-ad6c-f244e76d72b8)
> 
> notice logo
>
>  ![notice](https://github.com/HongDawww/naiver/assets/142575028/f38b3937-55e2-4f08-ae4b-983a1d5a3789)
>
# main
🤞 메뉴바 추가
>
 ![image](https://github.com/HongDawww/naiver/assets/142575028/dddd9c96-748d-46f6-af0f-fc8d6deadbf3)
>
# login-section
3️⃣ 로그인 섹션 추가 
>

![naver-login](https://github.com/HongDawww/naiver/assets/142575028/5576ebdd-842e-44f4-83e6-a3ea6629765c)
![naver-login2](https://github.com/HongDawww/naiver/assets/142575028/91d6b366-393a-46c5-84dc-eac17239fe06)

# newstand
4️⃣ 뉴스스탠드

![newstand](https://github.com/HongDawww/naiver/assets/142575028/b7da37ea-e789-4a41-8912-e8143f7aa359)


 # Shopping 
 5️⃣ 하단 쇼핑
 ![shopping](https://github.com/HongDawww/naiver/assets/142575028/a52e443e-3ecf-406c-a1a5-0107218cf17e)
 
 💜 추가 된 기능들 💜 
 
  (23.10.28)
  
- 검색어 입력란 placeholder 색상 변경
- 검색어 입력란 focus 시 placeholder 생성
- 검색어 입력란 focus 시 구분선 생성
- 검색어를 입력하세요 < 입력란 클릭 시 생성 되도록 변경
- keyboard hover시 색상 어둡게 변경
  
 (23.10.29)

- 전체 영역 지정
-  왼쪽 ad / 오른쪽 ad
-  오른쪽 로그인 영역
-   로그인 / 아이디찾기 / 비밀번호 찾기 / 회원가입 버튼 생성


(23.10.30)
- newstand
- footer
- 언론사 더보기 양쪽 버튼 생성
- 오른쪽 아이콘 생성 / hover
- 연합 뉴스 : text 길이가 길 때 ...으로 되도록 함
  
(23.11.05)
 - 연합뉴스 animation 효과 추가

   

 🤔 ❓ : 알게된 것들과 개인의 고찰

 1. focus 기능들을 사용하면서 여러 focus 선택자를 알게 됐다 예를들어 focus-within !! 
 2. 단순히 placehoder를 변경해야겠다는 생각을 못 했었는데 문득 바꿀 수 있나? 싶어서 아무리 적용을 해도 되지 않아 검색을 통하여 알게됐다
 3. 배치하고 싶은 위치에 배치하는 일은 언제나 어렵다 특히나  focus나 after를 사용할 경우 생각하는 것처럼 쉽게 변경되는 일은 더더욱 어렵다
 4. 검색어 입력란에 focus를 하면 구분선이 생성되게 하고 싶었는데 적용을 하고 보니 반대로 적용이 되어서 다시 반대로 css를 작성하는 어려움이 있었다
 5. 이미지 파일의 경우 햄버거 버튼, 로고 , 페이, 노티스는 직접 아이콘을 피그마로 제작하였는데 키보드와 돋보기 아이콘은 해당 사이트에서 개발자모드로 이미지를 가져왔다
 6. 이미지 파일은 한 파일에 모조리 있었는데 해당 위치에 있는 이미지를 지정하였다 이 부분은 생각보다 어려웠다
 7. 이러한 방식은 스프라이트 시트(Sprite Sheet) 라고 한다는 것을 알게 됐다.
 8. 스프라이트 시트 이유는 여러 이미지 파일을 여러 번 다운로드하는 대신, 하나의 이미지 파일로 저장하여 로딩속도를 개선할 수 있다고 한다 !!
 9. 메뉴는 li 태그로 만들었는데 li 의 요소들마다 적용하려고 하니 nth-child는 요소 안에 다른 태그들 마저 적용이 되었다 li안에 div에도 적용되는 현상 때문에 구글링을 해보니 nth-of-type 를 사용하면  li만 순서로 적용할 수 있었음
 10. css 변수 기능과 css 선택자 중에 $= 는 ~로 끝나는 모든 요소, ^= 으로 시작하는 모든 요소 라는 것을 알게 되었기 때문에 적극 사용해보았다 생소하게 느껴지지만 자주 사용해서 더 익숙하게 사용하고싶다
 11. css에서 공통으로 적용되는 부분들 먼저 적용하는 게 확실히 좋은 거 같다.. 물론 안다고 다 그렇게 되지는 않지만 💦 😰
 12. css에서 color 를 항상 지정해서 사용했었는데 color를 변수로 지정하여 사용하기도 하고 color: inherit 기능을 알게 되었다. color: inherit는 부모로 부터 상속받아서 동일한 컬러를 지정하여 사용할 수 있는 기능이라 이미 지정된 것들을 편리하게 사용할 수 있었음!!
 13. skewX 라는 기능을 사용하였는데 이 기능은 요소를 X 축을 기준으로 기울이는데 사용된다 이 기능은 deg 라는 각도를 나타내는 단위를 사용한다
 14. 그리고 vendor-prefix 은 -webkit-이나 -ms- 인데 옛날 브라우저인 경우에 사용한다고 한다 !!
 15. 연합 뉴스 부분을 표현할 때 길이가 길 경우 "..."으로 표시되는 (엘리프시스) 표현방식을 사용하기 위해 text-overflow: ellipsis를 사용하였는데 이 기능을 사용할 때 white-space: nowrap(텍스트 줄 바꿈 방지), overflow: hidden(내용이 넘칠 경우 숨김 처리)를 함께 사용하여야 했다
 16. 많이 사용하는 기능이 아니기 때문에 여러 시행착오를 겪었다 ..!
 17. 언론사 더보기 양 쪽으로 버튼이 있는데 한 방향의 이미지로 	transform: rotate(180deg) 을 사용하여 돌려서 사용하게 되었다 신선한 충격..!!!
