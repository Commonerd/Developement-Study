package arrayex.day0106;
//A반 학생의 성적은 95, 71, 84, 93, 87이다.
//배열에 저장 후 점수 총합/평균을 출력하세요.(향상된 for문 사용)
public class ArrayEx3 {

	public static void main(String[] args) {
		int [] aScore = {95, 71, 84, 93, 87, 90};//세미콜론 반드시 붙이기.
		int sum = 0;
		double avg = 0.0;
		for(int score : aScore) {
			sum +=score;//+=은 덧셈 축적
			
		}
		avg = sum / (double)aScore.length;
// lengh는 인트 sum도 인트, 인트를 인트를 나누면 인트, 소수점 사라져 데이터 사라짐
//인트랑 더블이랑 계산하니까, 작은 게 큰 거 따라간다, 인트가 더블로 간다, 더블 나누기 더블되니까 소수점ㅇ ㅣ남을 것. 
//소수점 살린 상태로 나누기가 될 것. 더블 타입인 avg에 저장
		System.out.println("A반 성적 총합 : "+sum);
		System.out.printf("A반 성적 평균 : %.2f",avg);
	}

}
