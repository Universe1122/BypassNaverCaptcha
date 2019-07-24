# BypassNaverCaptcha
네*버 자동입력방지문자 뚫기

## 프로젝트의 시작
김종민한테 웹크롤링을 배우기 시작한 박성민..

첫 시작으로 셀레니움으로 네이버 로그인을 하려 하지만 네*버 자동입력방지에 막히고 마는데...!!

그래서 네*버 자동방지문자를 뜷는 프로젝트를 시작하기로 했다.

## 개발일지
## 19.07.23

네*버 자동방지를 피하기 위한 개발자들의 여러 방법이 있지만

우리는 자동 입력방지 이미지를 문자로 바꾸면 어떨까 했다. 

그래서 머신러닝을 사용해서 캡챠(자동입력방지문자이미지(너무길다))를 학습시키고

학습시킨 프로그램으로 이미지를 넣으면 문자를 출력하게 하려 했다.

하지만 생각외로 네*버 캡챠 이미지는 너무 복잡해보였고

그래서 대신 쉬운 이미지로 학습시켜 테스트 해본 다음 네*버 캡챠 이미지를 학습시키기로 했다

쉬운 이미지는 캡챠 생성 오픈소스를 찾아 김종민이 만들기로 했다. 


### <한 일 요약>
- 프로젝트 주제 정하기

- 오픈 소스 사용해서 captcha 코드 돌림
### <할 일 요약>
김종민 : captcha 이미지와 정답을 크롤링 하여 서버에 저장하기.

박성민 : 머신러닝으로 어떻게 학습시킬지 방법 검색

