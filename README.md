# xe-inipaystandard
누리고 이니시스 스탠다드 결제 모듈 카드 결제 자동 취소 포함 버전<br/>
주문 취소시 카드 결제 자동 취소<br/>
주문 내역에서 결제 금액 부분 취소<br/>
가상계좌 결제시 이니시스에서 결과를 여러번 호출해 주문 상태가 변경되는 문제를 해결<br/>
<br/>
* 업데이트전 반드시 관련 파일들을 백업합니다.
* 해당 자료를 사용함으로써 발생하는 문제에 대한 책임을 지지 않습니다.
<br/>

## 설치방법<br/>
본 모듈(xe-inipaystandard) 업데이트 전.. <br/>
아래 모듈을 다운로드 받아 업데이트합니다.<br/>
<br/>
1.<a href="https://github.com/Clouds101/xe-epay">epay 모듈 업데이트</a><br/>
2.<a href="https://github.com/Clouds101/xe-nstore">nstore 모듈 업데이트</a><br/>
<br/>
<a href="https://github.com/Clouds101/xe-inipaystandard">inipaystandard 모듈 업데이트</a><br/>
![nuri_admin_update](https://user-images.githubusercontent.com/21264714/81894763-90f43c80-95eb-11ea-9263-a5a893963cd8.png)<br/>
XE 관리자 페이지 첫 화면에서 테이블생성
<br/>

## 스크린샷<br/>
![Image of Admin](https://user-images.githubusercontent.com/21264714/81882974-069ddf80-95cf-11ea-8fb0-d1adac9c2811.png)
<br/>
관리자 페이지 - 사용 여부 옵션 조절<br/>
<br/>
<img src="https://user-images.githubusercontent.com/21264714/81781576-4dd69280-9533-11ea-8ddc-ea7ff7fd9de0.png"><br/>
주문 관리 - 취소가 완료 되었을때<br/>
입급완료 상태에서 -> 취소로 변경하면 해당 주문의 카드 결제도 같이 취소 됩니다.<br/>
<br/>
![ini_part_cancle2](https://user-images.githubusercontent.com/21264714/82001835-154fc980-9697-11ea-84c1-84483888d447.gif)<br/>
주문 관리 - 부분 취소 작동예