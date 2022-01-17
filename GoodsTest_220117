package modifier.day0112;
import java.util.Scanner;

public class GoodsTest {

	public static void main(String[] args) {
		System.out.println("다음 항목의 값을 입력하세요.");
		
		Scanner s = new Scanner(System.in);
		System.out.println("상품명 : ");	
		String n = s.nextLine(); //공백까지 포함해서 읽어온다.
		System.out.print("가격 : ");
		int p = s.nextInt();
		System.out.print("수량 : ");
		int q = s.nextInt();
		
		Goods goods = new Goods(n,p,q);
		System.out.println("입력된 결과는 다음과 같습니다.");
		System.out.println(goods);//참조변수 출력 -> toString()호출
		
		System.out.printf("총 구매가격 : %d원", goods.getPrice() * goods.getQuantity());
		s.close();
	}

}
