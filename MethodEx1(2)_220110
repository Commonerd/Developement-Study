package methodex.day0110;

import java.util.Scanner;

public class MethodEx1 {

	int max(int a, int b) {
		int result = 0;
		if (a > b) {
			result = a;
		} else {
			result = b;
		}
		return result;
	}

	// 2. print String 값 1개 입력 받아 해당 문자열 출력하는, 리턴값 없는 메서드
	void print(String str) {
		System.out.println(str);
	}

	// 3. int Arr int 배열을 입력 받아 그안에 있는 모든 숫자 더하고 그 값을 리턴하는 메서드
	int intArr(int[] arr) {
		int sum = 0;
		for (int i : arr) {
			sum += i;
		}
		return sum;
	}

	// 4. random_10 랜덤값(1~10)사이의 값을 리턴
	int random_10() {
		return (int) (Math.random() * 10) + 1;
	}

	

	public static void main(String[] args) {
		MethodEx1 m1 = new MethodEx1();
		int max = m1.max(10, 5);
		System.out.println("10과 5중 더 큰 숫자는" + max + "입니다.");
		m1.print("test");
		int sum = m1.intArr(new int[] { 1, 2, 3, 4 });
		System.out.println(sum);
		System.out.println(m1.random_10());
	}

}
