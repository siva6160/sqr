package monday;

import java.util.Scanner;
import java.math.*;
public class loops {

	public static void main(String[] args) {
			int num;
			int s;
			int i=0;
			Scanner sc=new Scanner(System.in);
			num=sc.nextInt();
			while(i<=num){
				i++;
				
				System.out.println((Math.pow(i, 2)));
			}
	}

}
