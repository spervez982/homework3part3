# homework3part3
days and numbers
import java.util.Scanner; // Import the Scanner class

public class java2 {
	 public static void main(String[] args)

	   {

	       Scanner keyboard = new Scanner(System.in);

	       System.out.print("Input number: ");

	       int day = keyboard.nextInt();

	       System.out.println(getDayName(day));

	   }

	   // Get the name for the Week

	   public static String getDayName(int day) {

	       String dayName = "";

	       switch (day) {

	           case 1: dayName = "Monday"; break;

	           case 2: dayName = "Tuesday"; break;

	           case 3: dayName = "Wednesday"; break;

	           case 4: dayName = "Thursday"; break;

	           case 5: dayName = "Friday"; break;

	           case 6: dayName = "Saturday"; break;

	           case 7: dayName = "Sunday"; break;

	           default:dayName = "Invalid day range";

	       }

	       return dayName;

	   }

	}

