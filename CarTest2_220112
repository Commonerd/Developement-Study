package modifier.day0112;

abstract class Car {
	int speed;
	String color;

	abstract void upSpeed(int speed); 
	abstract void work();
}

class Sedan extends Car {
	@Override
	void work() {
		System.out.println("사람을 태웁니다.");
	}

	@Override
	void upSpeed(int speed) {
		this.speed += speed;
		if(this.speed > 150) {
			this.speed = 150;
		}
	}
}//Sedan

class Truck extends Car{

	@Override
	void work() {
		System.out.println("짐을 싣습니다.");
	}

	@Override
	void upSpeed(int s) {
		speed += s;
		if(speed > 130) {
			speed = 130;
		}
	}
}

public class CarTest2 {
	public static void main(String[] args) {
		Sedan s = new Sedan();
		s.work();//오버라이딩 된 메서드가 실행됨
		s.upSpeed(200);
		System.out.println("세단 속도 : "+s.speed);
		Truck t = new Truck();
		t.work();//오버라이딩 된 메서드가 실행됨
		t.upSpeed(100);
		System.out.println("트럭 속도 : "+t.speed);
		t.upSpeed(50);  
		System.out.println("트럭 속도 : "+t.speed);
	}
}






