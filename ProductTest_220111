package initvariable.day0111;
//각각의 객체 안에 있는 인스턴스 변수가 다 다른 값을 가져야 하는 경우 
//있으면 지정한 이름. 
class Product{
	static int count = 0;
	int serialNo;
	
	{	++count;
		serialNo = count;
	}
	Product(){}//기본생성자 추가
}
public class ProductTest {

	public static void main(String[] args) {
		Product p1 = new Product();
		Product p2 = new Product();
		Product p3 = new Product();
		
		System.out.println("p1의 제품번호는 "+p1.serialNo);
		System.out.println("p2의 제품번호는 "+p2.serialNo);
		System.out.println("p3의 제품번호는 "+p3.serialNo);
		
		System.out.println("모두 "+Product.count+"개 생산");
	}
}
//나의 이해 > 
