package arrayex.day0106;

public class ArrayEx1 {

	public static void main(String[] args) {

		char[] ch = new char[4];// 캐릭터 타입이 아니라, 캐릭터 '배열'타입
		// 참조형: 주소를 저장한다.

		ch[0] = 'J';
		ch[1] = 'a';
		ch[2] = 'v';
		ch[3] = 'a';
//		ch[4] = '!'; //ArrayIndexOutOfBoundsException
		//배열의 크기는 고정, 늘어나거나 줄어들지 않는다. 
//		for(int i = 0; i <4; i++ ) { 
//		System.out.println(ch[i]);
//		}
		
		for(int i = 0; i < ch.length; i++ ) { //캐릭터 수를 모를 때 length를 사용하면 몰라도 그냥 됨.
			System.out.println(ch[i]);
			}
		
		int[] iArr = {1,2,3,4};//index 0,1,2,3; 배열을 저장하는 게 아니라, '주소값'을 저장한다.
		for(int i =0; i < iArr.length; i++) {
			System.out.println(iArr[i]);
		}// 값이 정해져 있는 배열이라면, 이 방식이 많이 쓰인다. 위의 것보다 간단. 
		//단점은? 선언과 배열을 동시에 해야만 사용가능. 선언과 배열이 떨어지게 되면 곤란.
		
		int[] iArr2 = new int [] {5,6,7,8,9}; // 3번쨰 방법은 2번쨰 방법 단점 보완.
		for(int i=0; i<iArr2.length; i++) {
			System.out.println(iArr2[i]);
		}
	}

}
