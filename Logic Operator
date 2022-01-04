package test.operation.day0104;

public class OperEx4 {

	public static void main(String[] args) {
		int a = 10;
		int b = 20;
		
		
		//boolean c = (a += 12) > b && (a ==(b+2));
		// 1. a 22 >20  => true  => 뒤에 식 실행
		// 2. 22(a)=22(b+2) => true
		// 3. c= true
		//boolean c = !((a += 12) > b) && (a ==(b+2));
		// 1. 22(a)>20 ? => true
		// 2. !true => false
		// 3. 실행 안하고, 그대로 false로 끝남. 
		//boolean c = ((a += 12) > b) && (a ==(b+2));
		// 1. a==22
		// 2. 22>20 => true
		// 3. 22 == 22 => true 
		boolean c = ((a += 12) > b) || (a ==(b+2));
		// 1. a==22
		// 2. 22 > 20 => true
		// 3. 선조건이 참이라 후조건 실행 안함. 
		
		System.out.println("c:"+c);
		System.out.println("a:"+a);
		System.out.println("b:"+b);

		
	}

}
