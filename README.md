import java.util.*;
import java.io.*;

public class LaundryProgram{
  public static void main(String[] args){g
    displayMainMenu();
  }
  
  public static void displayMainMenu(){ // displays main options to user
    Scanner in = new Scanner(System.in);
    System.out.printf("Please enter one of the following options:\n" + 
                      "1.) Display Clothing Status\n" +
                      "2.) Reset Laundry\n"+
                      "3.) Display Hamper Status\n" +
                      "4.) Add clothing\n"+
                      "5.) Exit Program\n";);
    int choice = in.nextInt();
    
    if(choice == 1)
      displayClothingStatus();
      
      
    
  }
  
}
