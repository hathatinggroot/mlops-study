# Machine Learning Quality Management

<br/>
<hr/>


## Code Quality

### 문제 
1. 코드 중복
   1. 라이브러리
   2. 추상화
2. 전역 변수의 과도한 사용
3. 너무 긴 코드
4. 꼬여있는 import   
   1. relative + absolute
5. 명확하지 않은 변수명


### 린트와 유닛 테스트
#### 린트      
* __python black__        
* __flake8__
* __mypy__ : type check


#### practice
* [github actions practice](https://github.com/hathatinggroot/github-actions-practice)
* [python unittest pratice](https://github.com/hathatinggroot/python-unittest-practice)


### Continuous Integration   
lint, unittest 등을 통해 지속적인 코드 품질 관리        

1. Github Actions          
2. Gitlab-ci


<br/>
<hr/>

## Data Validation       
* ml 프로세스에서 데이터가 잘못 들어와도 서비스 장애가 나지 않고, 눈에 보이지 않는다.
* 하지만 기대한 학습효과가 떨어진다.
* 따라서 DataValidation이 필요하다.        
* TensorFlow Data Validation
  * basic statistics
  * anomaly
  * schema
  * drift & skew

### [TFDV(TensorFlow Data Validation)](https://colab.research.google.com/github/tensorflow/tfx/blob/master/docs/tutorials/data_validation/tfdv_basic.ipynb#scrollTo=8Ftd5k6AMkPV)         


<br/>
<hr/>



## Model Analysis      


