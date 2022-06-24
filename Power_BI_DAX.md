### Power BI Data Analysis eXpressions



* 측정값 이름 = 함수(테이블이름[열이름])

* 총 수량 = SUM('판매'[수량])

* DAX 함수 : SUM, AVERAGE, COUNT, SUMX, CALCULATE  



#### 01. 날짜 테이블 참조

* Calendar = Calendar(Date(2020,01,01), Date(2020,12,31))



#### 02. 날짜 테이블 참조 (새 테이블 ,.)

* Calendar = ADDCOLUMNS(
              CALENDAR(DATE(2016,01,01), DATE(2022,12,31)),
              "연도", Year([Date]),
              "분기", Format([Date], "Q")&"분기",
              "연월", Format([Date], "yyyy-mm"),
              "월No", Month([Date]),
              "월", Format([Date], "mm"),
              "월(영문)", Format([Date], "mmm"),
              "일", Format([Date], "dd"),
              "요일(한글)", Format([Date], "aaa"),
              "요일No", WEEKDAY([Date],2))
                 

#### [판매] 테이블 / 계산

* 매출금액= [단가]*[수량]*(1-[할인율])
* 매출원가=RELATED('제품'[원가])*[수량]
* 매출이익= [매출금액]-[매출원가]



#### [판매] 테이블 / 측정값 

* 총수량=SUM('판매'[수량])
* 주문건수=COUNTA('판매'[판매ID])
* 평균매출=AVERAGE('판매'[매출금액])
* 총매출금액=SUM('판매'[매출금액])
* 총매출이익= SUM('판매'[매출이익])
* 매출이익률=DIVIDE([총매출이익], [총매출금액],0)



*[Contoso Sales Sample Power BI Desktop 파일 참조](https://download.microsoft.com/download/4/6/A/46AB5E74-50F6-4761-8EDB-5AE077FD603C/Contoso%20Sales%20for%20Power%20BI%20Designer.zip)*



