package inheritance.day0112;

public class PointTest{
	PointTest(){
		super();// Object();
	}

	public static void main(String args[]) {
		Point3D p3 = new Point3D(1, 2, 3);
	}
}

class Point extends Object {
	int x;
	int y;
	Point(){};
	Point(int x, int y) {
		super();// Object(); 
		this.x = x;
		this.y = y;
	}

	String getLocation() {
		return "x :" + x + ", y :" + y;
	}
}

class Point3D extends Point {
	int z;

	Point3D(int x, int y, int z) {
		super(x, y);//Point(); 를 호출한다.
		this.z = z;
	}

	String getLocation() { // 오버라이딩
		return "x :" + x + ", y :" + y + ", z :" + z;
	}
}




