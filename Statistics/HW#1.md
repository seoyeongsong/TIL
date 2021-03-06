## 통계학이란 무엇인가?
### 1. 통계학(Statistics)의 정의

- Wikipedia 에서는 다음과 같이 정의하고 있다.

  : Statistics is a branch of mathematics dealing with the collection, organization, analysis, interpretation and presentation of data.

- 나의 생각 : 통계학은 사회현상을 수치화하여 분석할 수 있는 기초를 제공한다. 예를 들면, 고객만족도와 같이 수치화하기 힘든 지표에 대하여 조사자의 기준에 따라 일정 간격과 등급을 설정함으로써 정량적인 데이터로 수집할 수 있다. 이는 자연과학에서 측정되는 물리량과는 차이점이 있는 실험방법이다. 불규칙해보이는 데이터를 대상으로 규칙성을 발견하고 이를 통해 사회현상을 이해함을 넘어 미래의 발생가능한 사건을 예측할 수 있는 장치가 그 목적이라 생각한다. 자연과학서는 몇 가지 통제된 간단한 문제들을 해결해봄으로써 자연현상을 이해하고 분석하며 이를 기반으로 더 복잡한 자연현상에 대해 '예측'을 제시할 수 있어야 가치가 있다. 이 과정에서 수학으로 기술하게 되고 이는 약속이자 제일 명확하게 기술할 수 있는 방법이다. 비슷한 맥락으로, 사회과학에서 사회문제를 수학적으로 접근하여 해결하고자 함에 있어 필요한 것이 통계학이라 생각한다. 이는 데이터를 분석하는 첫 과정에서 반드시 필요한 것이라 생각한다.


### 2. 모집단과 표본

- Wikipedia에서는 다음과 같이 정의하고 있다.

  모집단 : 정보를 얻고자 하는 관심 대상의 전체 집합, 알고자 하는 것에 의해 다르게 정의되기 때문에 모집단을 명확하게 정의하는 것은 매우 중요하다.

  표본 : 모집단의 부분집합이다. 일반적으로 모집단은 매우 크기 때문에 전수조사를 하기에는 불가능하므로 다룰 수 있을 만한 크기의 부분집합을 나타낸다.

  Sampling : 표본이 얻어지면 얻은 표본에 대해 추론을 하기 위해 통계적 계산이 수행된다. 표본으로부터 정보를 얻기 위한 과정을 표집(sampling)이라고 한다. 표집은 모집단에서 표본을 추출하는 일이다. 관심 대상의 모집단에 관한 정보를 얻기 위하나 의도로 개별적 관측을 선택하는 통계적 수행의 일부이다.
  표집과정은 다음 7단계로 구성된다.
  - 모집단에 대한 정의
  - 측정 가능한 항목이나 사건의 집합인 표집틀의 상술
  - 틀로부터 항목이나 사건을 선택하기 위한 표집 방법의 상술
  - 표본 크기의 결정
  - 표집 계획의 구현
  - 표집 및 자료의 수집
  - 표집 과정의 재검토

- 나의 생각 : 모집단과 표본은 일단 크기에서 상당한 차이를 보이고 표본은 모집단의 부분집합이고 모집단은 전체 집합을 말한다. 현실적으로 모집단을 조사할 수 없기에 우리는 표본집단을 통해 모집단의 성격을 파악하고자 한다. 표본은 모집단의 성격을 잘 나타낼 수 있어야 '추정'이 가능하기 때문에 표본 집단을 추출할 때 고려해야 할 사항이 있을 것이다. 고려할 사항에는 표본 집단의 크기도 있을 것이고, 표본을 추출하는 방법을 어떻게 설계할 것인지도 포함될 것이라 생각한다.

### 3. 박스플롯

- Wikipedia : In descriptive statistics, a box plot or boxplot is a method for graphically depicting groups of numerical data through their quartiles. Outliers may be plotted as individual points. Box plots are non-parametric: they display variation in samples of a statistical population. The spacings between the different parts of the box indicate the degree of dispersion (spread).

- 나의 생각 : Box plot은 사분위수를 사용하여 최대/최소값을 구하여 그릴 수 있다. 이는 데이터의 분산형태를 살펴볼 수 있는 방법이다. 우리가 box plot을 사용하는 이유에는 사분위수를 사용하기 때문에 시각적으로 하나의 집단의 중앙값과 평균값의 위치를 알 수 있으며 이것이 box내에서 치우친 정도에 따라서 전체 데이터에 대한 개요를 쉽게 확인할 수 있다. 또한 outlier의 위치도 알 수 있다. 데이터의 분포를 알 수 있는 다른 형태인 히스토그램과 비교하자면, 히스토그램은 하나의 그래프로 하나의 집단 데이터 분산 형태만 알 수 있지만 box plot은 서로 다른 집단을 함께 그려줌으로써 한 눈에 비교가 가능한 점에서 차이점이 있다. 만약 데이터가 정규부포를 따를 경우, box plot의 IQR은 50%의 면적을 차지하고 최대값과 최소값을 모두 고려하면 3sigma(신뢰구간 99%)구간과 일치함을 알 수 있다. box plot 자체는 많은 통계량이 시각적으로 간략하면서도 명료하게 표현되므로 데이터를 파악하는 데에 사용한다.


### 4. 데이터 시각화

- Wikipedia : To communicate information clearly and efficiently, data visualization uses statistical graphics, plots, information graphics and other tools. Numerical data may be encoded using dots, lines, or bars, to visually communicate a quantitative message. Effective visualization helps users analyze and reason about data and evidence.
- 나의 생각 : 우리는 데이터 시각화를 생활에서 많이 접하고 있다.  뉴스를 통해 주가나 유가의 변동 그래프를 볼 수 있고, 기상청으로부터 등온선이나 해류의 방향 등 다양한 정보를 보기 쉽게 그래프와 지형도에 나타낸 자료를 접하고 있다. 많은 자료를 table형태로 만들어 보는 것도 하나의 방법이겠지만 데이터 전체가 유의미한 관계를 가지고 있는지를 단순히 table을 보고 알아차리기는 어렵다. 그래서 우리는 관계식을 직선이나 곡선의 형태로 plotting을 함으로써 분석에 활용한다. 이는 복잡한 데이터에 대해 접근성을 높일 수 있고, 두 집단을 비교하기에 용이하다.  정리하면 데이터 시각화는 정보의 인지와 그것을 활용한 분석, 그리고 의사소통에 사용되므로 효율적으로 정보를 다루기 위해서는 필요한 요소이다. 데이터 시각화와 관련하여 인포그래픽도 비슷한 맥락이라 할 수 있다.

### 5. 통계적 사고

- 현대 사회에서 우리는 많은 정보를 접하고 있다.
- 빠른 속도로 변화는 사회에서 효과적인 의사결정을 하기 위해 필요한 데이터만을 추출하는 것과 그것으로 신뢰성 있는 분석을 할 줄 알아야한다.
- '통계적으로' 사고할 수 있다는 것은 통계학적인 용어를 알고 계산을 할 줄 아는 것만을 의미하는 것은 아니라고 생각한다. 주어진 자료를 보고 어떤 상관관계를 보이는지를 알아보기 위해 산포도나 히스토그램을 그려보는 것과 같은 행위도 넓은 의미에서 포함될 것이다.





### 6. 정규분포
- Wikipedia : Gaussian distribution이라고도 하며, 연속 확률 분포의 하나이다. 정규분포는 수집된 자료의 분포를 근사하기 위해 사용되며 중심극한정리에 의해 독립적인 확률변수들의 평균이 정규분포에 가까워지는 성질이 있기 때문이다. 정규분포는 2개의 매개 변수에 의해 모양이 결정된다. 특별히 평균과 표준편차가 각각 0과 1인 정규분포를 표준정규분포라고 한다.
- 나의 생각 : 
