# Anomaly Detection

## Anomaly 란?

[Anomaly](https://github.com/kyopark2014/ML-anomaly-detection/blob/main/anomaly.md)에서는 Anomaly의 정의에 대해 설명합니다. 

### Anomaly Detection 용도

- 유지보수를 예측: default/defect 예측
- 네트워크 보안
- Health Care
- financial fraud 검출 

### 뉴욕 택시 정보

[nyc_taxi.csv](https://github.com/kyopark2014/ML-anomaly-detection/blob/main/ny-taxi/nyc_taxi.csv)에서는 뉴욕 택시의 호출 정보를 표시하고 있습니다.

해당 정보는 아래처럼 다운로드 가능합니다.

```java
curl https://raw.githubusercontent.com/numenta/NAB/master/data/realKnownCause/nyc_taxi.csv -o nyc_taxi.csv
```

## RCF 란?

[Random Cut Forest (RCF)](https://github.com/kyopark2014/ML-anomaly-detection/blob/main/rcf.md)에서는 RCF 이론에 대해 설명합니다.

## SageMaker를 이용한 Anomaly Detection

[SageMaker의 RCF](https://github.com/kyopark2014/ML-anomaly-detection/blob/main/SageMaker/README.md)에서는 SageMaker의 Built-in Algorithm을 이용한 RCF 구현 방법에 대해 설명합니다.



## RRCF (Robust Random Cut Forest)를 이용한 Anomaly Detection

[RRCF](https://github.com/kyopark2014/ML-anomaly-detection/blob/main/rrcf/README.md)에서는 RRCF를 이용한 Anomaly Detection에 대해 설명합니다.


## Reference 

[이상 탐지를 위한 Amazon SageMaker 의 Random Cut Forest 빌트인 알고리즘](https://aws.amazon.com/ko/blogs/korea/use-the-built-in-amazon-sagemaker-random-cut-forest-algorithm-for-anomaly-detection/)

[Random Cut Forest (RCF) Algorithm](https://docs.aws.amazon.com/sagemaker/latest/dg/randomcutforest.html)

[Using Random Cut Forests for real-time anomaly detection in Amazon OpenSearch Service](https://aws.amazon.com/ko/blogs/big-data/using-random-cut-forests-for-real-time-anomaly-detection-in-amazon-opensearch-service/)

[Real Time Anomaly Detection in Open Distro for Elasticsearch](https://opensearch.org/blog/real-time-anomaly-detection-in-open-distro-for-elasticsearch/)


