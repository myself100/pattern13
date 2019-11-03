# pattern13

import java.util.Scanner;
public class pattern12 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner s=new Scanner(System.in);
		int n=s.nextInt();

		for(int i=1;i<=n;i++) {
			for(int j=1;j<=i;j++) {
				if(i%2==0) {
					System.out.print(j);
				}
				else {
					System.out.print((char)(64 +j));
				}
			}
			System.out.println();
		}
	}

}

output::                  ////when n is 5 
5
A
12
ABC
1234
ABCDE
