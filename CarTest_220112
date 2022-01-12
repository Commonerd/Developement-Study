package modifier.day0112;

abstract class Car {// 추상 클래스가 되므로, 객체를 생성할 수 없다.

	int speed;
	String color;

	abstract void upSpeed(int speed);
	abstract void work();// 추상매서드를 하나라도 갖고 있으면 추상 클래스(l3에 추가)여야 한다.
}
	class Sedan extends Car {

		@Override
		void work() {
			System.out.println("사람을 태웁니다.");
		}

		@Override
		void upSpeed(int speed) {
			if (this.speed <= 150) {
				this.speed += speed;
			} 
		}
	}

	class Truck extends Car {

		@Override
		void work() {
			System.out.println("짐을 싣습니다.");
		}

//		@Override
//		void upSpeed(int speed) {
//			if (this.speed <= 130) { // this 붙이는 이유는 객체 안에 있는 현재속도를 갖고 검사하기 떄문.지역변수 speed에 넣은 값을 
//				this.speed += speed;
//				System.out.println(speed+"입니다.");
//			} 
		@Override
		void upSpeed(int s) {
			if (speed <= s) { // this 붙이기 싫으면 지역변수 s로 바꾸고 speed와 이름 다르게 하면 됨. 
				speed += s;
				System.out.println(speed+"입니다.");
			} 
		}

	}

	public class CarTest { // 추상매서드를 받으니까, 추상매서드 오버라이딩해야 한다. 리턴 타입 이름 매개변수

		public static void main(String[] args) {
			Sedan s = new Sedan();
			s.work(); // 오버라이딩된 메서드 실행
			s.upSpeed(130);
			Truck t = new Truck();
			t.work(); // 오버라이딩된 메서드 실행
			s.upSpeed(120);
		}

	}

