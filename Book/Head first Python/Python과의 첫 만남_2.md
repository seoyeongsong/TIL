# List data로 작업하기
### 1. 나열하기 - for 루프 사용하기
    >>> fav_movies = ["The Holy Grail", "The Life of Brain"]
    >>> print(fav_movies[0])
    The Holy Grail
    >>> print(fav_movies[1])
    The Life of Brain
   
##### 위와 같은 코드의 경우는 list에 항목이 추가되면 작동할 수 없다. 
##### for 루프를 사용하면 list의 크기에 상관없이 작동한다. list를 나열할 때 for를 사용하자.
  
    >>> fav_movies = ["The Holy Grail", "The Life of Brain"]
    >>> for each_flick in fav_movies:
	           print(each_flick)

	
    The Holy Grail
    The Life of Brain
* for 루프 구조 : for / 타깃 식별자 / in / List:
  * for : 루프의 시작을 알려주며, 타깃 식별자 앞에 온다.
  * in : 타깃식별자와 List를 구별한다.
  * 타깃식별자 : List 나열 시, 각 항목 data 값이 차례로 대입되며 루프가 순환하면서 타깃식별자는 매번 다른 data를 가리킨다.
  * List 처리코드(=suite) : for 루프 안에 들여써야 한다.
  * :(colone) : List 처리코드가 시작됨을 알려주며 List 이름 뒤에 위치한다.
  
