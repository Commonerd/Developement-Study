package methodex.day0110;

public class MyMath {
	// 사칙연산
	// add: int값 두개 입력받아 더한 결과 리턴
	int add(int a, int b) {
		return a + b;
	}

	// substract: int값 두개 입력받아 뺀 결과 리턴
	int substract(int i, int j) {
		return i - j;
	}

	// multiply: int값 두개입력받아 곱한 결과 리턴
	int multiply(int i, int j) { // i,j는 지역변수라 위와 같아도 상관없음.
		return i * j;
	}

	// divde: int값 두개입력받아 나눈 결과 리턴
	// boolean을 제외한 기본형이면서 작은 타입 -> 큰 타입인 경우 
	// 자동으로 형변환 후 저장됨.
	double divide(double a, double b) { //8바이트 더블.
		return a / b;
	}

	public static void main(String[] args) {
		MyMath mm = new MyMath();
		int add = mm.add(1, 2); //add(1,2)는 괄호있으니 메서드
		System.out.println(add); //add는 괄호 없으니 변수 
		System.out.println(mm.multiply(10, 20));
		System.out.printf("%.2f",mm.divide(10, 3)); //4바이트 인트. 알아서 더블로 바꿔줌(작은 것에서 큰 것으로)
		
		
	}

}
