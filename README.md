# Devops-gitProject
import java.util.*;
public class Area {
	public static void main(String [] args)
	{
		Scanner sc = new Scanner(System.in);
		System.out.println("**************WELCOME****************");
		System.out.println("Please Enter 1 for area of circle");
		System.out.println("Please enter 2 for area of  triangle");
		System.out.println();
		int choice = sc.nextInt();
		double area = 0.0;
		switch(choice)
		{
		case 1: // Area of the circle
			System.out.println("Enter the radius of the circle: ");
			Double c_radius = sc.nextDouble();
			area = Math.PI *Math.pow(c_radius, 2.0);
			System.out.println("The area of this circle: "+ area);
			break;
			
		case 2: // Area of the triangle
		        System.out.println("Enter base of the triangle: ");
			Double base = sc.nextDouble();
			System.out.println("Enter hieght of the triangle: ");
			Double hieght = sc.nextDouble();
			System.out.println();
			area = 0.5 * (base * hieght);
			System.out.println("The area of this triangle is: "+ area);
			break;
			

		
		default:
			System.out.println("Invalid Input");
			break;
		}
		
		}
	}
