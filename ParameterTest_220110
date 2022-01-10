package methodex.day0110;

class Data { int x; }
class ParameterTest {
	public static void main(String[] args) {
		Data d = new Data();
		d.x = 10;
		System.out.println("main() : x = " + d.x);

		change(d.x);
		System.out.println("After change(d.x)");
		System.out.println("main() : x = " + d.x);
	}
	static void change(int x) {  //매개변수, 파라미터. 
		// 매개변수는 메서드 영역안에서 선언되었으므로 지역변수다. 
		x = 1000;//인트값 저장.
		System.out.println("change() : x = " + x);
	}
}








