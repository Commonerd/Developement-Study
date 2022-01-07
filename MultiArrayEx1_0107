package arrayex.day0107;

public class MultiArrayEx1 {

	public static void main(String[] args) {

		int[][] test = new int[2][3];

		test[0][0] = 100;
		test[0][1] = 200;
		test[0][2] = 300;
		test[1][0] = 111;
		test[1][1] = 222;
		test[1][2] = 333;
		
		//아래와 같이 배열을 선언하는 게 더 간단하다. 
		int[][] test2= {{1,2,3},{11,22,33},{111,222,333}};
		
		// 다중 foreach문 사용해서 저장된 데이터 전부 출력
		for(int i = 0; i < test.length ; i++ ) {
			for(int j = 0; j < test[i].length; j++) {
				System.out.println(test[i][j]);
			}
		}
		for(int[] arr :test) {
			for(int i : arr) {
				System.out.println(i);
			}
		}
	}
}
