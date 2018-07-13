# DOg
DOg 는 The Programming Language Based on **D**og's **O**ral Lan**g**uage의 약자입니다.
# 구현
DOg 는 GCC 컴파일러 기반으로 만들어질 예정입니다. 이로 인해 GNU 라이선스를 채택하였습니다.
# 변수
변수는 C++의 변수 타입과 같다.  
## 변수 선언하기
변수 선언은 [왈왈 명령어](https://github.com/OlliStudio/DOg/blob/master/README.md#%EC%99%88%EC%99%88)를 통해 할 수 있다.  
# 기본 명령어
## 멍멍
`멍멍,<문자열>;`  
멍멍은 자신의 뒤에 있는 문자열을 출력하는 함수이다.  
멍멍 자체와 문자열은 쉼표로 구분한다.  
### 사용 예시
명령어 : `멍멍,그르르르왈왈멍멍;`  
출력 : `그르르르왈왈멍멍`  
이처럼 출력하는 문자열에 다른 함수명이 있더라도 무시하고 출력한다.
## 엉엉
`엉엉,<변수명>,<변수타입>;`  
엉엉은 변수를 입력받는 함수이다.  
### 사용 예시
명령어 : `엉엉,A,정수;`  
효과 : 실행창을 통해 정수 변수 A 를 입력받는다.
## 왈왈
`왈왈,<변수명>,<변수타입>,<변수값>;`  
왈왈을 이용하여 DOg의 변수를 선언할 수 있다.  
### 사용 예시
명령어 : `왈왈,A,int,3;`  
효과 : C++에서의 int A = 3; 과 효과가 같다.  
명령어 : `왈왈,a,char;`  
효과 : char a; 와 같다.  
**주의점 : <변수값>을 생략한 채로 지역 변수를 선언할 경우 쓰레기 값이 들어가게 됩니다.**
