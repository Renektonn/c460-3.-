# c460-3.-
如何sort Object array?
import java.util.*;

public class Main {

	public static void main(String[] args) {
		Scanner cin = new Scanner(System.in);
		
		int n = cin.nextInt();
		
		Data [] data = new Data [n+1];
		
		for(int i = 1 ; i <= n ; i++) { // input
			
			data [i] = new Data (cin.nextInt() , cin.nextBoolean() , cin.nextBoolean() , cin.nextBoolean());
			
		}

		
		
	}

}

class Data{
	
	int racial;
	boolean airAtt;
	boolean rangeAtt;
	boolean farAtt;
	
	public Data(int racial , boolean airAtt , boolean rangeAtt , boolean farAtt) {
		this.racial   = racial;
		this.airAtt   = airAtt;
		this.rangeAtt = rangeAtt;
		this.farAtt   = farAtt;
	}
}
