# kawos



`kawos`은 **K**MA **AW**S AS**OS**의 약자입니다. `기상청(KMA)`이 운영하는 `방재기상관측기(AWS)`와 `종관기상관측기(ASOS)`의 관측(또는 집계) 자료에 대한 접근성을 높이는 것을 목표로합니다.



## 사용법



```python
import pandas as pd
```



```python
# 종관기상관측지점목록

pd.read_csv(f'https://raw.githubusercontent.com/dogbull/obser/master/stations/asos.stations.csv')
```



```python
# 방재기상관측지점목록

pd.read_csv(f'https://raw.githubusercontent.com/dogbull/obser/master/stations/aws.stations.csv')
```



```python
# 2021년01월01일 종관기상관측 전제지점 자료

pd.read_csv(f'https://raw.githubusercontent.com/dogbull/obser/master/daily/asosdaily/2021/01/01/asosdaily.2021-01-01.csv')
```



```python
# 서울(108)의 2021년 종관기상관측자료

pd.read_csv(f'https://raw.githubusercontent.com/dogbull/obser/master/pointly/asos/108/2021/108.2021.csv')
```



```python
# 2021년01월01일 방재기상관측 전제지점 자료

pd.read_csv(f'https://raw.githubusercontent.com/dogbull/obser/master/daily/awsdaily/2021/01/01/awsdaily.2021-01-01.csv')
```



```python
# 독도(96)의 2021년 방재기상관측자료

pd.read_csv(f'https://raw.githubusercontent.com/dogbull/obser/master/pointly/aws/96/2021/96.2021.csv')
```



## 출처

> 본 저작물은 [기상청](https://www.kma.go.kr)에서 작성하여 공공누리 제1유형으로 개방한 `종관기상관측`, `방재기상관측`을 이용하였으며,
해당 저작물은 [기상자료개방포털](https://data.kma.go.kr/)에서 무료로 다운받으실 수 있습니다.

