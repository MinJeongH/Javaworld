[Chater 02 Variable Type]
변수와 타입

(변수)
1. 변수란 하나의 값을 저장할 수 있는 메모리 공간
2. 변하는 수를 담을 수 있는 그릇
3. 메모리 번지에 대한 이름 (별칭)

(변수 작성 규칙)
1. 영문, 숫자, 특수문자($, _) 조합 etc. abc, abc123, abc_123
2. 문자의 시작이 숫자는 불가능
3. 길이의 제한은 없으나 너무 길면 가독성이 떨어져 어떤 변수인지 알아보기 힘듦
4. 자바 예약어 (Reserved Word) 사용 불가능. 교재 31p 참고
	- 컴파일 오류 발생
5. 대소문자 구별 필수

(변수 선언)
1. 타입 변수이름
2. 타입 변수이름 = 초기값
3. etc. 정수형 변수 선언
	int x;
	int y = 10;
	int z = -9;
	
(데이터 타입)
1. 정수 byte int char short long
2. 실수 float double
3. 논리 boolean
4. 사용자형 class enum

(할당 연산자)
1. 데이터를 변수에 대입
2. 기존의 변수에 있던 값은 사라지고 대입되는 값이 저장됨
3. etc
	int x = 10;
	x = 99;
	
(Literal)
1. 정수 리터럴, 실수 리터럴, 논리 리터럴, 문자 리터럴, 문자열 리터럴
etc. 10, -3, 0.43, 'a', true

(상수 constant value)
1. 변하지 않는 수, 문자, 문자열
2. 변수의 다른 형태 (변수인데 한번 지정하면 값을 바꿀 수 없음)

(원시타입 : primitive type)
boolean(1b) short(2b) char(2b) int(4b) float(4b) double(8b)

