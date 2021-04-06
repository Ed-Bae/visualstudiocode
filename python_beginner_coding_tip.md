# 기초 팁


## 함수
### 함수정의
```
# 함수정의
def 함수명():
  print("Hello")
  
# 함수호출
함수명()
```

## 파라메터
```
# 함수정의

def 함수명(val1, val2):
  print(val1 + val2)

# 함수호출
함수명(10, 20)
```

## 변수 variable
정수, 문자열, 소수점

## 상수 constants
" 이중따옴표 사용

## 타입
정수 int
문자열 str
소수점 float
소수점이 있는 문자열은 float로 타입을 변경한다.
```
# 정수를 문자열로 
v1 = str(10)
# 문자열을 정수로
v1 = int("10")
# 문자열을 실수로
v1 = float("0.1")
```
## 반복문 

for 문
```
# 0 ~ 9까지 1증가로 출력
for num in range(0, 10 + 1):
  print(num)

# 0, 100까지 2증가로 출력
for num in range(0, 100 + 1, 2):
  print(num)
```

## format 형식

".format()" 사용 방법
문자열 내에 '{}'(중괄호)의 문자를 대체한다.
```
msg = "{}, {}".format("Hi, ", "Ed")
printMsg()

> Hi, Ed
```


