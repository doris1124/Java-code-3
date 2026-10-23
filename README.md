# Java-code-3
package q18070;
import java.util.*;

class Main{
    public static void main(String[] args){
    	Scanner sc = new
			Scanner(System.in);
		String s = sc.nextLine();
		String rev = new
			StringBuilder(s).reverse().toString();
		if(s.equals(rev))
			System.out.println("yes");
		else
			System.out.println("no");





	}
 	
}
