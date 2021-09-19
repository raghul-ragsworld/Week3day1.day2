package week3.day1;// package

public class BankInfo {
	
	public void saving()
	{
		System.out.println("this is saving account");
	}
	public void fixed()
	{
		System.out.println("this is fixed account");
	}
	public void deposit()
	{
		System.out.println("This is deposit account");
	}
	

	public static void main(String[] args) {
		
		
	

	}

}
-------------------------------------------------------------------

package week3.day1;

public class AxisBank extends BankInfo {

public void deposit() {

	System.out.println("This is axis bank deposit account");
	}

	public static void main(String[] args) {

		AxisBank axis = new AxisBank();

		axis.deposit();

	}

}
