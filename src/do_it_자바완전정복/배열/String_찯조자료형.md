
# 250627 금요일 위키 

# String 참조자료형

## String 클래스
- 문자열 저장 클래스 타입
- 문자열은 쌍따움표("")안에 표기

## String 객체 만드는 2가지 방법

방법 1 : new 객체를 이용하여 만드는 방법
- String str = new String("문자열");

방법 2 : 참조변수에 바로 문자열 리터럴 입력
- String str = "문자열";


## 일반적인 참조자료형과 다른 String만의 특징

1. 객체 내의 값 변경 불가능 -> 값 변경시 새로운 객체 생성하여 작성
2. 리터럴을 바로 입력한 데이터는 문자열이 같은 경우 같은 객체 공유

## String 객체의 + 연산

1. 문자열 + 문자열 -> 문자열을 연결
2. 문자열 + 기본자료형 또는 기본자료형 + 문자열 -> 기본자료형을 문자열로 변경 + 문자열 변경

## String의 주요 메서드
[문자열 길이]
- length() : 문자열의 길이
[문자열 검색]
- charAt(int index) : 인덱스 위치에서의 문자
- indexOf : 문자열에 포함된 문자 또는 문자열의 위치를 앞에서부터 검색하였을 때 일치하는 인덱스 값
- lastIndexOf : 문자열에 포함된 문자 또는 문자열의 위치를 뒤에서부터 검색하였을 때 일치하는 인덱스 값
[문자열 변환 및 연결]
- String.valueOf(자료형) : boolean, char, int, long, float, double 값을 문자열로 변환하기 위한 정적 메서드
- concat : 문자열의 연결
[문자열 배열 변환]
- getBytes() : 문자열을 byte[]로의 변환
- getChar() : 문자열을 char[]로의 변환
[문자열 수정]
- toLowerCase() : 영문 문자를 모두 소문자로 변환
- toUpperCase() : 영문 문자를 모두 대문자로 변환
- replace(char oldChar, char newChar) : oldChar 문자열을 newChar로 변환한 문자열 생성
- subString(int beginIndex) : beginIndex부터 끝까지의 문자열을 생성
  subString(int beginIndex, int endIndex) : beginIndex부터 endIndex-1까지의 문자열을 생성
- split(String regex) : regex를 기준으로 문자열을 분할하며 분할한 문자열 배열을 생성
[문자열 내용 비교]
- trim() : 문자열의 앞 뒤 공백을 제거
- equals() : 문자열의 실제 내용 비교
- equalsIgnoreCase() : 대소문자 상관 없이 내용 비교



