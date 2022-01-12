package Importex.day0112;

import java.text.SimpleDateFormat;
import java.util.Date; //이렇게 쓰면 아래에 일일이 패키지명 안써도 된다.

public class ImportDate {

	public static void main(String[] args) {
		Date d = new Date(); //패키지명 다 적어줌
		//Date도 Object를 상속함
		System.out.println(d);//참조변수 출력
		//날짜값에 대해서 포맷 바꿔주는 클래스
		SimpleDateFormat sdf = new SimpleDateFormat("yyyy/MM/dd hh:mm a");
		String now = sdf.format(d);
		System.out.println("현재시간 : "+now);
		//마우스 두고 import해도 되고,
		//import 할게 여러개면, "Ctrl+Shift+o"
		//이걸로 '뽀모도로 타임트래커'를 만들 수 있겠다.
	}

}
