# AsalSayiBulma

import java.util.Scanner;

public class main {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		
		int n=1;
		int m=100 ;
		
		for (int i=n; i<=m; i++) {
			boolean asal = true;
			if(i<=1) {
				asal = false;
			}
			else {
				for(int sayi = 2; sayi<i; sayi++) {
					if (i % sayi ==0) {
						asal = false;
						break;
				}
			  }	 
			}
		 if (asal) {
	                System.out.print(i + " ");
		 }
	  }
   }
}

