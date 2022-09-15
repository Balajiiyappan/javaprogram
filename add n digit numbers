import java.util.*;
class digit
{
	public static void main(String[] args)
	{
		int x,sum=0,i,z,g;
		String n;
		Scanner c=new Scanner(System.in);
		Scanner sc=new Scanner(System.in); 
		System.out.print("Enter the N value:  ");
		if(!sc.hasNextInt())
		{
			System.out.println("Invalid data");
			return;
		}
		x=sc.nextInt();
		if(x<=0)
		{
			System.out.println("Invalid data");
			return;
		}
		System.out.print("Enter "+x+" digit value:  ");
		n=c.nextLine();
		if(x!=n.length())
		{
			System.out.println("Invalid");
			return;
		}
		int s=Integer.parseInt(n);
		g=s;
		for(i=1;i<=x;i++)
		{
			z=g%10;
			sum=sum+z;
			g=g/10;
		}
		System.out.println("Sum of  "+x+" digit value = "+(sum));
	}
}
