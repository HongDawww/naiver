# naiver: X이버 클론 코딩 

제작 기간 : 10/28 ~

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
 
 💜 추가 된 기능들 💜 (23.10.28)
- 검색어 입력란 placeholder 색상 변경
- 검색어 입력란 focus 시 placeholder 생성
- 검색어 입력란 focus 시 구분선 생성
- 검색어를 입력하세요 < 입력란 클릭 시 생성 되도록 변경
- keyboard hover시 색상 어둡게 변경 

 🤔 ❓ : 알게된 것들과 개인의 고찰

 1. focus 기능들을 사용하면서 여러 focus 선택자를 알게 됐다 예를들어 focus-within !! 
 2. 단순히 placehoder를 변경해야겠다는 생각을 못 했었는데 문득 바꿀 수 있나? 싶어서 아무리 적용을 해도 되지 않아 검색을 통하여 알게됐다
 3. 배치하고 싶은 위치에 배치하는 일은 언제나 어렵다 특히나  focus나 after를 사용할 경우 생각하는 것처럼 쉽게 변경되는 일은 더더욱 어렵다
 4. 검색어 입력란에 focus를 하면 구분선이 생성되게 하고 싶었는데 적용을 하고 보니 반대로 적용이 되어서 다시 반대로 css를 작성하는 어려움이 있었다
 5. 이미지 파일의 경우 햄버거 버튼, 로고 , 페이, 노티스는 직접 아이콘을 피그마로 제작하였는데 키보드와 돋보기 아이콘은 해당 사이트에서 개발자모드로 이미지를 가져왔다
 6. 이미지 파일은 한 파일에 모조리 있었는데 해당 위치에 있는 이미지를 지정하였다 이 부분은 생각보다 어려웠다
 7. 이러한 방식은 스프라이트 시트(Sprite Sheet) 라고 한다는 것을 알게 됐다.
 8. 스프라이트 시트 이유는 여러 이미지 파일을 여러 번 다운로드하는 대신, 하나의 이미지 파일로 저장하여 로딩속도를 개선할 수 있다고 한다 !!

