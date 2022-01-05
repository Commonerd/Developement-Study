package test.ifex.day0105;

import java.util.Scanner;

public class ifEx5 {

	public static void main(String[] args) {
		Scanner s = new Scanner(System.in);
		System.out.println("과세표준 금액을 입력해주세요. >");
		System.out.print("과세 표준금액 >");
		int money = s.nextInt();
		int tax = 0;
		if (money <= 1000) {
			tax = (int) (money*0.08); // 퍼센트 단위로 넘어왔을 때 0.0x로 변환
		} else if ( money <= 4000 ) {
			tax = (int) (money*0.17);
		} else if ( money <=8000 ) {
			tax = (int) (money*0.26);
		} else { 
			tax = (int) (money*0.35);
		}
		
		System.out.printf("근로소득세 : %d만원", tax);
	}
}
	

		
		/*int income = s.nextInt();
	    int taxRate = 
		if (income > 80000000) {
			System.out.println(35);
		} else if { income > 40000000 && income <= 80000000 ) {
			System.out.println(26);
		} else if { income > 10000000 && income <= 40000000 ) {
			System.out.println(17);
		} else { 
			System.out.println(8);
		}
		
		System.out.println("당신의 근로 소득세는"+income*"입니다.");
*/
