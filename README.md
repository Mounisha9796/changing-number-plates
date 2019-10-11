package programs;

public class StateBikeconversion {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		String s1="AP 23 C 4576";
		String s2="AP 20 C 2312";
		String s3="AP 20 C 2312";
		String s4=s1.replace("AP", "TS");
		System.out.println(s4);
		
		String s5=s2.replace("AP", "TS");
		System.out.println(s5);
		
		String s6=s3.replace("AP", "TS");
		System.out.println(s6);

	}

}
