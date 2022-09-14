import java.util.*;
class details
{  
	void det()
	{	
		int ac;
		Scanner sc=new Scanner(System.in);
		Scanner c=new Scanner(System.in);
		System.out.print("Account no.: ");
		if(!sc.hasNextInt())
		{
			System.out.print("Invalid");
			System.exit(0);
		}
		ac=sc.nextInt();
		System.out.print("Depositor name: ");
		if(!c.hasNextLine())
		{
			System.out.print("Invalid");
			System.exit(0);
		}
		String na=c.nextLine();
		System.out.print("Type of account: ");
		char ty=sc.next().charAt(0);
		if(ty=='S')
		{
			System.out.print("");
		}
		else
		{
			System.out.print("Invalid");
			System.exit(0);
		}
	}
}
class balance extends details
{
	void cal()
	{
	int b=1000,de,wi,ba=0;
	Scanner s=new Scanner(System.in);
	System.out.print("Deposit an amount: ");
	de=s.nextInt();
	ba=b+de;
	if(ba>500)
	{
		System.out.print("Withdraw an amount: ");
		wi=s.nextInt();
		ba=ba-wi;
		System.out.print("Balance= "+ba);
	}
	else
	{
		System.out.print("No minimum balance");
	}
	}
}
class in
{    
	public static void main(String args[])
	{
		balance x=new balance();
		x.det();
		x.cal();    
	}
}
