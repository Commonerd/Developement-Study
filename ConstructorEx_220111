package constructor.day0111;

class Data1{
	int x;
	//Data(){} 이렇게 컴파일러가 생성자를 자동으로 추가해놓음.
}

class Data2{
	int x;//인스턴스 변수-선언된 위치에 따름. 
	//별도 적은 거 없으니 x에는 0이 저장되어있음
	Data2(){};//매개변수 없는 생성자를 만들거나.
	Data2(int i){ //생성자 아니면, 메서드다.
		//이름이 클래스 이름 같으니 생성자.
		//이걸로 객체 그대로 만들면 된다.
		x = i;
	}
	
}
public class ConstructorEx {

	public static void main(String[] args) {
		Data1 d1 = new Data1();
		//Data2 d2 = new Data2();//error 생성자의 매개변수가 안맞기 떄문.
		Data2 d3 = new Data2(10);// (11번줄에 이어서) 인트타입 값을 넣어주거나.
	} // '='는 주소값 저장. 
// ConstructorEx(){}//생성자. 자동 생성. 
//클래스에는 하나 이상의 생성자가 있어야 되기 때문에 추가된다.
//생성자는 객체로 올라가지 않는다.
//메서드건 생성자건 끝나면 호출했던 지점으로 돌아온다. 
// 
}
