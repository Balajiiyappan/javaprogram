import java.util.*;
public class com
{
	public static void main(String[] args) 
	{
	    int a,b,i,j,c,count=0,co=0;
		System.out.print("Start number: ");
		Scanner sc= new Scanner(System.in);
		a=sc.nextInt();
		System.out.print("End number: ");
		b=sc.nextInt();
		if(a==b || a>b)
		{
			System.out.print("Invalid input");
			return;
		}
		if(a==1)
		{
		    System.out.print("1 is not a prime nor a composite");
		}
		else if(a>b)
		{
		    System.out.println("Invalid input");
		}
		else
		{
    		for(i=a;i<=b;i++)
    		{
    		    c=0;
    		    for(j=1;j<=i;j++)
    		    {
    		        if(i%j==0)
    		        {
    		            c++;
    		        }
    		    }
    		    if(c==2)
    		    {
    		        count++;
    		    }
    		        
    		}
    		System.out.print("\nComposite: ");
    		for(i=a;i<=b;i++)
    		{
    		    c=0;
    		    for(j=1;j<=i;j++)
    		    {
    		        if(i%j==0)
    		        {
    		            c++;
    		        }
    		    }
    		    if(c>2)
    		    {
    		        co++;
    		        System.out.print("  "+i);
    		    }
    		}
    		System.out.print("\nNo. of composite= "+co);
		}
	}
}
