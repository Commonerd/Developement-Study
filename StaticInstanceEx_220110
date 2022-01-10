package methodex.day0110;

public class StaticInstanceEx {

		static int cv = 1; //(클래스변수, 즉 스태틱변수)
		int iv = 2; // 인스턴스변수
		
		static int cv2 = cv; // 
		//static int cv3 = iv; 
		//cv3가 올라간 시점에 iv없다
		//error static은 instance 사용X
		
		int iv2=cv;
		int iv3=iv;
		// s->s ; i -> i, s 둘다 가능 
	public static void main(String[] args) {
		System.out.println(cv);
		//System.out.println(iv);
		//static에서 인스턴스 변수인 iv는 불가. 나 올라간 시점에 iv 없어. 
		//굳이 iv를 써야겠다면, 해당클래스를 객체로 생성한 다음
		StaticInstanceEx si = new StaticInstanceEx();
		System.out.println(si.iv);
	}

}
