# KIOSK_PROJECT
한솥도시락을 벤치마킹하여 웹기반 사용자의 UI/UX를 표현하는 비대면 서비스를 위한 KIOSK UI 구현

[시연영상 🎬](https://www.youtube.com/watch?v=z_4dOv2sEcA)

------------

# 1. 소개
![image](https://user-images.githubusercontent.com/71997900/119938302-2a0fae80-bfc7-11eb-91e6-3b796021a066.png)

![image](https://user-images.githubusercontent.com/71997900/119938468-6a6f2c80-bfc7-11eb-8495-8c0222ff72e7.png)

![image](https://user-images.githubusercontent.com/71997900/119941986-3fd3a280-bfcc-11eb-83d1-de4ab5889dd1.png)

------------

# 2. 화면설계 & 화면구현
![image](https://user-images.githubusercontent.com/71997900/119938526-84107400-bfc7-11eb-9aff-d5a44ac529dd.png)

![image](https://user-images.githubusercontent.com/71997900/119938516-7f4bc000-bfc7-11eb-8262-cb0e41ad6f8a.png)

![image](https://user-images.githubusercontent.com/71997900/119938540-896dbe80-bfc7-11eb-97ca-22f6f984551a.png)

![image](https://user-images.githubusercontent.com/71997900/119938556-8e327280-bfc7-11eb-829a-475df1fa0d5e.png)

![image](https://user-images.githubusercontent.com/71997900/119938568-938fbd00-bfc7-11eb-8319-1ab1a4e114c8.png)

------------

# 3. 주요기능 & 설계 내용

*메뉴목록지정
![image](https://user-images.githubusercontent.com/71997900/119940885-cbe4ca80-bfca-11eb-834e-7adbe91ebc1b.png)

*메뉴 불러오는 함수
![image](https://user-images.githubusercontent.com/71997900/119940933-e028c780-bfca-11eb-8931-2d8bc140b070.png)

*팝업창 제어 함수
![image](https://user-images.githubusercontent.com/71997900/119941868-1ca8f300-bfcc-11eb-9add-51951b1e5ab2.png)

*장바구니 배열에 넣기
![image](https://user-images.githubusercontent.com/71997900/119941800-06029c00-bfcc-11eb-8e49-41cfc742c5fa.png)

*장바구니 배열 선택내역에 출력
![image](https://user-images.githubusercontent.com/71997900/119942321-a2c53980-bfcc-11eb-9c7c-d250e126449c.png)
![image](https://user-images.githubusercontent.com/71997900/119942392-ba9cbd80-bfcc-11eb-9ed0-386109b3739c.png)

*장바구니 메뉴 수량 변경
![image](https://user-images.githubusercontent.com/71997900/119942533-eddf4c80-bfcc-11eb-972e-0684a9de3535.png)

*가격의 총 합계를 구하는 함수
![image](https://user-images.githubusercontent.com/71997900/119942682-16674680-bfcd-11eb-9e69-00b34d8c8e78.png)

*원하는 메뉴 삭제 함수
![image](https://user-images.githubusercontent.com/71997900/119942786-2f6ff780-bfcd-11eb-987b-1dc53df71316.png)
![image](https://user-images.githubusercontent.com/71997900/119942970-5e866900-bfcd-11eb-8461-8e6f8d638ace.png)

*결제관련 선택창
![image](https://user-images.githubusercontent.com/71997900/119943487-1287f400-bfce-11eb-9107-c4d5060521d8.png)
![image](https://user-images.githubusercontent.com/71997900/119943051-79f17400-bfcd-11eb-915f-167e7ac58033.png)
![image](https://user-images.githubusercontent.com/71997900/119943165-a1484100-bfcd-11eb-9c7d-b4a7fd2e57b7.png)

*영수증 출력
![image](https://user-images.githubusercontent.com/71997900/119943345-e1a7bf00-bfcd-11eb-837b-dcf090ab4f5f.png)
![image](https://user-images.githubusercontent.com/71997900/119943293-d05eb280-bfcd-11eb-88a0-34e98435fb95.png)



------------

# 4. 프로젝트를 진행하며 느낀점
자바스크립트로 진행한 프로젝트가 처음이라 초반에 자바스크립트, html, css를 유기적으로 연결하는 것에 어려움을 느꼈습니다. 또한 장바구니 파트를 맡았는데 이 파트를 진행하면서 장바구니 배열을 오브젝트로 생성하는 부분을 이해하는데 긴 시간이 걸렸고 이해한 후에도 구현하기까지 시간이 꽤 소요되었습니다. 그러다보니 마음이 더 앞서 순서대로 진행하지 못하고 뒤죽박죽이 되었는데 이 경험을 통해 데이터 설계 시에는 작업 단위를 쪼개서 계속 콘솔에 값을 찍어보며 확인하는 습관이 필요하고 중요하다는 것을 깨달았습니다.
