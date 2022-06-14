- 관련포스팅 : <https://xenostudy.tistory.com/719>

없으면 만든다.

- 자료출처 : 
  - <https://finance.daum.net/domestic/arounds>
  - <https://finance.naver.com/sise/sise_deposit.naver>

1. 직접크롤링하여 그래프를 그린다.
2. 매일 자동으로 업데이트 된다. (업데이트시간 : 9시, 18시, 22시) - 이미지상단에 업데이트 시간확인가능
3. 마커를 통해서 상세수치 확인 가능

## 고객예탁금 

### 고객예탁금 1년치 그래프 

5일평균선을 통해서 추세를 알수있다.

```sh
https://raw.githubusercontent.com/kksworks/stock_data_asset/master/deposit_graph/customer_deposit_300d.png
```

![고객예탁금 1년](https://raw.githubusercontent.com/kksworks/stock_data_asset/master/deposit_graph/customer_deposit_300d.png)

### 고객예탁금 3년치 그래프 

5일평균선을 통해서 추세를 알수있다.

```sh
https://raw.githubusercontent.com/kksworks/stock_data_asset/master/deposit_graph/customer_deposit_900d.png
```

![고객예탁금 3년](https://raw.githubusercontent.com/kksworks/stock_data_asset/master/deposit_graph/customer_deposit_900d.png)

## 신용잔고

### 신용잔고 1년치 그래프 

```sh
https://raw.githubusercontent.com/kksworks/stock_data_asset/master/deposit_graph/dept_deposit_300d.png
```

![신용잔고 1년](https://raw.githubusercontent.com/kksworks/stock_data_asset/master/deposit_graph/dept_deposit_300d.png)

### 신용잔고 3년치 그래프 

```sh
https://raw.githubusercontent.com/kksworks/stock_data_asset/master/deposit_graph/dept_deposit_900d.png
```

![신용잔고 1년](https://raw.githubusercontent.com/kksworks/stock_data_asset/master/deposit_graph/dept_deposit_900d.png)

## 예탁금 + 신용잔고

단순히 신용잔고만 보면 현상태가 어떤지 모르는경우가있어, 예탁금과 같이 본다.

```sh
https://raw.githubusercontent.com/kksworks/stock_data_asset/master/deposit_graph/dept_customer_deposit_900d.png
```

![신용잔고 + 예탁금 1년](https://raw.githubusercontent.com/kksworks/stock_data_asset/master/deposit_graph/dept_customer_deposit_900d.png)


## 구글시트에 그래프 넣기

위의 이미지 주소를 다음의 형식에 맞게 넣으면.. 구글시트에 실시간 그래프를 넣을수 있다.

```sh
=IMAGE("이미지주소",3)
```