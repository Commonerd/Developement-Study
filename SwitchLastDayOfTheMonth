package Switchex.day0105;

import java.util.Scanner;

public class SwitchEx2 {

	public static void main(String[] args) {
		System.out.println("월을 입력하면 해당 월의 마지막날을 알려줍니다.");
		
		Scanner s = new Scanner(System.in); //스캐너하면, 상단에 임포트!
		System.out.println("월 > ");
		int month = s.nextInt();
		String day = "";//반드시 지정. 나는 항상 잘 까먹는다.
		switch(month) {
		case 1: case 3: case 5: case 7: case 8: case 10: case 12:
			day = "31"; break;
		case 2: 
			 day = "21"; break;
		case 4: case 6: case 9 : case 11:
			day = "30";
			default :
				day="no";
		
		}
		System.out.printf("%d월의 마지막 날은 %s일입니다.", month, day);
		s.close();

	}

}
