package arrayex.day0107;

import java.util.Arrays;

public class ArrayCopyEx2 {

	public static void main(String[] args) {
		int[] orig = { 1, 2, 3, 4, 5 };

		int[] copy = Arrays.copyOf(orig, orig.length);
		//copyOf는 0번 인덱스부터 시작. 4번까지 포함. 5번 인덱스는 포함안됨. 5번 '앞'까지만.
		for (int i : copy) {
			System.out.println(i);
		}
		System.out.println();
		
		//0~2인덱스까지 복사 
		int[] copy2 = Arrays.copyOf(orig, 3);
		//0~3번까지. 
		for (int i : copy2) {
			System.out.println(i);
		}
		System.out.println();

		//2~3번인덱스까지 복사
		int[] copy3 = Arrays.copyOfRange(orig, 2, 4);
		for (int i : copy3) {
			System.out.println(i);}
		System.out.println();
	}

}
