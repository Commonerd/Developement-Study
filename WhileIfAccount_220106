package whileex.day0106;

import java.util.Scanner;

public class WhileEx3 {
// 1.예금 | 2. 출금 | 3. 조회 | 4.종료
// 마이너스 통장 금지!!
	public static void main(String[] args) {
		Scanner s = new Scanner(System.in);
		
		int balance = 0;//계좌 잔액
		boolean flag = true ;// true : 실행, false : 중지 
		
		while(flag) {
			System.out.println("==============================");
			System.out.println("1.예금 | 2. 출금 | 3. 조회 | 4.종료");
			System.out.println("==============================");
			System.out.println("선택 > ");
			
			int menu = s.nextInt();
			
			if(menu ==1) {
				System.out.println("예금액 >");
				int money = s.nextInt();
				balance += money; // 나는 +=가 아니라 +를 해서 실수.
				System.out.println(money+"원이 입금되었습니다.");
			} else if(menu ==2) {
				System.out.println("출금액 > ");
				int money = s.nextInt();
				if((balance - money) >= 0) {
					balance -= money;//나는 -=가 아니라 -를 해서 실수.
					System.out.println(money+"원이 출금되었습니다.");;
				} else {
					System.out.println("잔액이 부족합니다.");
				} 
			} else if(menu ==3) {
				System.out.println("잔액 > "+balance);
			} else { 
				System.out.println("프로그램 종료");
				flag = false;
			}
		}//while
		s.close();
	}
}
			
				
				
			/*int num = s.nextInt();
			if(num == 1) {
				System.out.println("예금을 얼마하시겠습니까? >");
				int num1 = s.nextInt();
			} else if(num == 2) {
				System.out.println("얼마를 출금하시겠습니까? >");
				int num2 = s.nextInt();
				if (num2 >= balance) {
					System.out.println(num2+"를 출금하였습니다.");
				} else { System.out.println("잔액이 부족합니다");}
			} else if(num == 3) {
				System.out.println(balance);
			} else if(num == 4) {
				System.out.println("종료합니다.");
				flag = false;
			}
		}
		System.out.println("서비스를 종료합니다.");*/


