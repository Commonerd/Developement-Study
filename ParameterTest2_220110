package methodex.day0110;

class ParameterTest2 {
	public static void main(String[] args) {
		Data d = new Data();
		d.x = 10;
		System.out.println("main() : x = " + d.x);//10

		change(d);
		System.out.println("After change(d)");
		System.out.println("main() : x = " + d.x);//1000
	}
	static void change(Data d) { //Data는 참조형 변수. 주소값 저장
		d.x = 1000;//주소값 저장.
		System.out.println("change() : x = " + d.x);//1000
	}
}
