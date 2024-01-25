import java.util.Scanner;

public class Main
{
	public static void main(String[] args) {
	 int[] nums= new int[4];
	 double sum=0;
	int target;
	Scanner scanner = new Scanner(System.in);
	
	
      	 
	 for ( int i=0;i<4;i++)
	 {
	    nums[i]=scanner.nextInt();
	    
	 }
	System.out.println("please input target:");
	target=scanner.nextInt();
	
	 for ( int i=0;i<4;i++)
	 {
	     sum+=nums[i];
	     if (sum==target)
	     System.out.println(i+","+(i-1));
	}

}}
