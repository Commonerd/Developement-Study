package inheritance.day0111;
class Tv{
	boolean power; 	// 전원상태(on/off)
	int channel;	// 채널

	void power() { 	power = !power; }
	void channelUp() { 	++channel; }
	void channelDown() {	--channel;	}
}

class CaptionTv extends Tv {
	boolean caption;	// 캡션상태(on/off)
	CaptionTv(){}//생성자는 변수 다음.
	void displayCaption(String text) {
		if (caption) {	// 캡션 상태가 on(true)일 때만 text를 보여 준다.
			System.out.println(text);
		}
	}
}

public class CaptionTvTest {

	public static void main(String args[]) {
		CaptionTv ctv = new CaptionTv();
		ctv.channel = 10;				// 조상 클래스로부터 상속받은 멤버
		ctv.channelUp();				   // 조상 클래스로부터 상속받은 멤버
		System.out.println(ctv.channel);
		ctv.displayCaption("Hello, World");	//클래스 영역내 불리온 기본값이 false라서 실행 안됨.
		ctv.caption = true;				     // 캡션기능을 켠다.
		ctv.displayCaption("Hello, World");	// 캡션을 화면에 보여 준다.
	}

}
