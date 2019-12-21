# java-chicken-2019
> 치킨집 사장님이 사용하는 POS 프로그램 구현

## 구현할 기능 목록
* 메인화면(1.주문등록, 2.결제하기, 3.프로그램 종료)을 출력한다.
* 메인화면 중 원하는 기능을 선택할 수 있어야한다.
    * [에외] **1,2,3 중 하나인지** 검증한다.
    * [예외] **자연수인지** 검증한다.

    1. 주문 등록 기능
        * 테이블(번호) 목록을 출력한다.
        * 테이블을 선택한다.
            * [예외] **없는 테이블**이 아닌지 검증한다. 
            * [예외] **사용중이 아닌 테이블**인지 검증한다.
            * [예외] **자연수인지** 검증한다.
        
        * 메뉴 기본 정보(메뉴번호, 종류, 이름, 가격)를 출력한다.
        * 메뉴를 선택한다.
            * [예외] **없는 메뉴가 아닌지** 검증한다.
            * [예외] **자연수인지** 검증한다.
        
        * 메뉴의 수량을 입력한다.
            * [예외] **한 메뉴의 최대 수량(99)를 넘지 않는지** 검증한다.
            * [예외] **자연수인지** 검증한다.
        
        * 주문이 등록된 테이블은 결제가 이루어지기 전까지 별도로 표시한다.

    2. 결제하기 기능
        * 테이블을 선택한다.
            * [예외] **없는 테이블**이 아닌지 검증한다. 
            * [예외] **사용중인 테이블**인지 검증한다.
            * [예외] **자연수인지** 검증한다.

        * 주문 내역을 출력한다.
        
        * 결제가 신용카드(1)인지 카드(2)인지 출력한다.
            * [에외] **1,2 중 하나인지** 검증한다.
            * [예외] **자연수인지** 검증한다.

        * 치킨 메뉴의 수량 합이 10개가 넘는 경우 10,000원씩 할인한다.
        * 현금 결제는 최종 금액에서 5%를 더 할인한다.

        * 최종 결제할 금액을 출력한다.

* 주문 혹은 결제가 불가능할 경우 그 이유를 보여준다.
* 주문 혹은 결제가 불가능할 경우 다시 주문 혹은 결제가 가능해야한다.

