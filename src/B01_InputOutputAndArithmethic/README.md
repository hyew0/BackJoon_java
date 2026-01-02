# 입출력과 사칙연산

## 2557. Hello World!

- psvm: public static void main(String[] args) {}
- sout: System.out.println();

> ***참고*** <br>
> 자바에서는 패키지 이름과 클래스 이름이 숫자로 시작할 수 없음. 

## 1000. A+B
- scanner: Scanner sc = new Scanner(System.in);
- nextInt(): int a = sc.nextInt();
- nextLine(): String str = sc.nextLine();
- parseInt(): int num = Integer.parseInt(str);
- close(): sc.close();

## 1008. A/B
- double: 실수형 자료형
- casting: (double) a / b;
- 오차 범위: 10^-9 이면 -> 대체로 소수점 9번째 자리까지 출력
  - float: 대체로 6~7자리까지 정확성 보장 
  - double: 대체로 15~16자리까지 정확성 보장
  - 따라서 정확한 실수 계산이 필요한 경우 double 사용 권장
- printf: System.out.printf("%.9f\n", result);
  - %.9f: 소수점 9자리까지 출력