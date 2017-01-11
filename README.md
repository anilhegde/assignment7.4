package session7;

import java.util.Scanner;

public class Assignment73 {

	public static void main(String[] args) {
		Scanner in = new Scanner(System.in);
		System.out.println("Enter the main string: ");
		String string =in.nextLine();
		System.out.println("Enter sub string to be find: ");
	    String apple = in.nextLine();
	    char[] strArr = string.toCharArray();
	    char[] subArr = apple.toCharArray();
	    if(isPresent(subArr, strArr)){
	    	System.out.println("Sub string present in main string");
	    }
	    else{
	    	System.out.println("Substring not found!!");
	    }
	}
