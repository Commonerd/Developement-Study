package test.ifex.day0105;

import java.util.Scanner;

public class ifEx4 {
//2.성적을 입력하면 성적에 맞는 학점을 출력하세요
//	90~100 : "A", 80~89 : "B", 70~79:"C",그외 나머지는 "F"
	public static void main(String[] args) {

		Scanner s = new Scanner(System.in);// 스캐너 쓸 떄 임포트문 빼먹으면 안된다!
		System.out.println("성적를 입력하세요. >");
		int score = s.nextInt();
		String grade = "";

		if (90 <= score && score <= 100) {
			grade = "A";
		} else if (score >= 80) {
			grade = "B";
		} else if (score >= 70) {
			grade = "C";
		} else {
			grade = "F";
		}

		System.out.println("당신의 성적은 "+grade + "입니다.");

		s.close();

	}

}
