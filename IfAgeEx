package test.ifex.day0105;

import java.util.Scanner;

public class IfEx2 {
//if(조건식){
//	조건식 true일 떄 실행하고 if문 끝
//	flase인 경우 다음 조건식을 실행한다.	
//}else if(조건식) {
//}else if(조건식) {
//}else { 
//	모든 조건이 false일 때 실행. 생략 가능
//}
	public static void main(String[] args) {
		// 나이를 저장하고 20살 이상이면 "성인"
		// 17살 이상이면 "고등학생"
		// 14살 이상이면 "중학생"
		// 8살 이상이면 "초등학생"
		// 그 외 나이라면 "아동"을 출력하세요.
		Scanner s = new Scanner(System.in);
		System.out.print("값을 입력하세요. >");
		int age = s.nextInt();
		String student = "";// *나는 이 부분을 놓침
		/*
		 * if (age >= 20) {System.out.println("성인");} else if (age >=17)
		 * {System.out.println("중학생");} else if (age >=8) {System.out.println("초등학생");}
		 * else {System.out.println("아동");}
		 */
		if (age >= 0 && age < 120) {
			if (age >= 20) {
				student = "성인";
			} else if (age >= 17) {
				student = "고등학생";
			} else if (age >= 14) {
				student = "중학생";
			} else if (age >= 8) {
				student = "초등학생";
			} else {
				student = "아동";
			}

			System.out.println(student + "입니다.");
		} else {
			System.out.println("나이를 잘못 입력했습니다.");
		}
		s.close();

	}

}
