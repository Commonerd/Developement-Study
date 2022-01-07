package oopex.day0107;

class Variable {
	//멤버변수는 값을 저장하지 않으면 기본값을 저장하고 있다.
	static int cv =1; // 클래스 영역 내부. static이 있으므로, 클래스 변수.
	int iv = 2; // 클래스 영역 내부에 있지만, static이 없으므로, 인스턴스 변수.
	void method() { //인스턴스 메서드. 
		int lv = 3; // 지역변수. 
		System.out.println(lv);
		
	}
}
public class VariableTest {

	public static void main(String[] args) {
		System.out.println(Variable.cv);//cv는 바로 실행가능하다. 왜냐면 바로 메모리에 올가가기 떄문에.
		
		Variable v = new Variable(); //인스턴스 속해 있는 변수를 객체로 만들어준다. 참조변수로 만들고 객체변수로.
		System.out.println(v.iv);
		
		v.method();
	}
 
}
