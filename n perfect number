import java.util.*;
public class per
{
    public static long it(long n) 
    {
    	long dsum = 0;
    	long i;
    	for (i=1;i<=Math.sqrt(n);i++) 
    	{
    		if(n%i==0) 
    		{
    			if(i==n/i)
    			{
    				dsum += i;
    			}
    			else 
    			{
    				dsum += i;
    				dsum += n / i;
    			}
    		}
    	}
    	dsum=dsum-n;
    	if(dsum==n)
    	{
    	    return 1;
    	}
    	else
    	{
    	    return 0;
    	}
    }
	public static void main(String[] args) 
	{
	    Scanner sc=new Scanner(System.in);
		long i,temp;
    	System.out.print("Enter n: ");
      if(!sc.hasNextLong())
	    {
		        System.out.print("Invalid Enter only integers");
            return;
	    }
    	long n=sc.nextLong();
      if(n==0 || n<0)
      {
        System.out.print("Invalid");
        return;
      }
    	i=1;
      System.out.print("First "+n+" perfect numbers are: ");
    	while(n>0) 
    	{
    		if(it(i)==1) 
    		{
    			System.out.print(i+" ");
    			n=n-1;
    		}
    		i=i+1;
    	}
    	System.out.println();
	}
}
