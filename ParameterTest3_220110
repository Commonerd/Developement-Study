package methodex.day0110;

class ParameterTest3 {
	public static void main(String[] args) {
		int[] x = {10};  // 
		System.out.println("main() : x = " + x[0]);

		change(x);//메서드 호출. 끝나고 다시 돌아와서 여기서 시작.
		System.out.println("After change(x)");
		System.out.println("main() : x = " + x[0]);
	}
	static void change(int[] x) { // 배열도 참조형 변수
		x[0] = 1000;
		System.out.println("change() : x = " + x[0]);
	}
}


