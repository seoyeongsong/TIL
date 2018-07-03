### 1. Python의 구조
- 문장 (statement)
- 식
- 연산자 (operator)
- 함수
- 모듈 (module)
- method
- class
### 2. Python 설치 - IDLE
- 통합 개발 환경으로 구문 강조 편집기, 디버거, python shell, python 온라인 문서를 포함
- python shell : 코드를 실험하고 편집기로 코드를 작성
- 실행 시 (>>>)의 프롬프트가 보이고 여기에 코드를 입력
- shell은 코드 문장을 입력 받아 바로 실행하고 결과를 화면에 보여줌
- 내장함수 (built-in-function = BIF), 자동완성목록  ex.print()
- 보라색 = 내장함수, 녹색 = 문자열, 주황색 = 언어 키워드
- 코드 블록의 들여쓰기
- 코드 문장 기억 : Alt+P (이전에 입력한 코드 문장이 과거순으로), Alt+N (최근순)
- 변수 식별자 선언 X
### 3. List : 복잡한 data 처리하기
### List는 배열과 같다.
- list 생성 시, interpreter는 memory에 배열과 같은 data 구조체를 생성
- data는 밑에서부터 쌓이고, 첫 번째 항목은 0, 두 번째는 1, 세 번째는 2의 index가 붙음
- 하나의 list 안에 여러 형태의 data(문자열, 숫자)를 추가
### How to
- data를 ("")로 둘러싸서 이름을 문자열로 변환
- 각 list 항목을 (,)로 분리
- 전체 list를 ([])로 둘러싸기
- 대입 연산자 (=) 사용해 식별자에 list 대입(assign)
### 실습_1
    >>> cast = ["Cleese", "Palin", "Jones", "Idle"]'
    >>> print(cast)
        ['Cleese', 'Palin', 'Jones', 'Idle']
    >>> print(len(cast))
        4
    >>> print(cast[1])
        Palin
- print : 화면에 출력
- len : list안에 몇 개의 항목이 있는지 확인
### 실습_2
    >>> cast.append("Gilliam")
    >>> print(cast)
        ['Cleese', 'Palin', 'Jones', 'Idle', 'Gilliam']
    >>> cast.pop()
        'Gilliam'
    >>> print(cast)
        ['Cleese', 'Palin', 'Jones', 'Idle']
    >>> cast.extend(["Gilliam", "Chapman"])
    >>> print(cast)
        ['Cleese', 'Palin', 'Jones', 'Idle', 'Gilliam', 'Chapman']
- method 호출은 (.)을 이용
- append("") : list 마지막 data 항목 1개를 추가
- pop() : list 마지막 data 항목을 삭제
- extend([""]) : list 마지막 data 항목 여러개를 추가
### 실습_3
    >>> cast.remove("Chapman")
    >>> print(cast)
        ['Cleese', 'Palin', 'Jones', 'Idle', 'Gilliam']
    >>> cast.insert(0, "Chapman")
    >>> print(cast)
        ['Chapman', 'Cleese', 'Palin', 'Jones', 'Idle', 'Gilliam']
- remove("") : 특정 data 항목을 찾아 제거
- insert( ,"") : 특정 data 항목 앞에 data를 추가
