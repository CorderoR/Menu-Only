# Menu-Only

import java.util.Scanner;


public class VendingMachine{
	String type;
	int BillContent;
	Double CoinContent;
	
	int[] Sodaslot=new int[8];
	int[] SnackSlot= new int[40];
	
	public void refill() {
	    int sodaSlotCapacity=30;
		int snackSlotCapacity=60;
	}
	
	
	
	public static void main (String args[]) {
		String option;

		do{
			System.out.println("*******Vending Machine Manager********");
			System.out.println("1- To Add a Machine, enter 1 and press Enter");
			System.out.println("2- To Modify a Machine, enter 2 and press Enter");
			System.out.println("3- To Delete a Machine, enter 3 and press Enter");
			System.out.println("4- To Delete a Machine, enter 4 and press Enter");
		    System.out.println("5- To Simulate purchase and refill , enter 5 and press Enter");
		    System.out.println("6- For Audit reports , enter 6 and press Enter");
		    System.out.println("7- To Exit the menu , enter 7 and press Enter");
		    Scanner scan = new Scanner(System.in);
}		    option= scan.nextLine();
		
		
	}while(!option.equals("7"));
	
  }
 public class VendingMachine()
 {	//Member Variables
  	String type:
	int machineID;
	int billContain;
	Dooble coinContain;
	//Constructor
	public VendingMachine()
	{
		
	}
	//Method to add a Machine
	public void addMachine()
	{
		
	}
	//Method to refill a Machine
	public void refillMachine()
	{
	
	}
        //Method to remove a Machine
	public void deleteMachine()
	{
	
	}
	//Method that shows the inventory of a Machine
	public void inventory()
	{
	
	}
	//Method that simulate the use of a machine
	public void simulation()
	{
	
	}
	//Method that shows the inventory of a Machine
	public void audit()
	{
	
	}
	
}
public class sodaMachine extends VendingMachine
{	
	int[] slot=new int[8];
	dooble[] cost=new int[8];
}
public class snackMachine extends VendingMachine
{	
	int[] slot=new int[40];
	dooble[] cost=new int[8];
}
public class comboMachine extends VendingMachine
{	
	int[] SodaSlot=new int[8];
	int[] snackSlot=new int[20];
	dooble[] sodaCost=new int[8];
	dooble[] sodaCost=new int[20];
}
	
	

	
	
  }
	
}
