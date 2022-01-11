package constructor.day0111;

public class Song {//1.필드 2. 생성자 3. 메서드 순서로 작성.
	String title;
	String artist;
	int year;
	String country;

	Song() {}

	Song(String title, String artist, int year, String country) {
		this.title = title;
		this.artist = artist;
		this.year = year;
		this.country = country;
	}//생성자의 역할: 인스턴스 변수에 대하여 값을 저장시켜 주는 애.
	
	void show(){
		System.out.printf("%s, %d년 %s [%s] \n",country, year, artist, title);	
	}
	

	public static void main(String[] args) {
		Song s = new Song("Dancing Queen","ABBA",1978,"스웨덴");
		s.show();
	}
	

}
