package JavaClassHomework1;
import java.util.Scanner;
public class ChiliToGo
{
public static void main(String[] args)
{
    int AdultMealprice = 7;
    int ChildMealprice = 4;
    int numb_of_Meals = 1;
    
    Scanner imp = new Scanner (System.in);
    System.out.print("How many meals do you need?");
    int meals = imp.nextInt();
    
    int total_numb_of_Adult_Meals = (meals/numb_of_Meals);
    int total_numb_of_Child_Meals = (meals%numb_of_Meals);
    
    int total_cost_for_All_Meals = 
    
    double total_cost_of_Adult_Meal = total_numb_of_Adult_Meals * AdultMealprice;
    double total_cost_of_Child_Meal = total_numb_of_Child_Meals * ChildMealprice;
    double total_cost_for_All_Meals = (total_cost_of_Adult_Meal + total_cost_of_Child_Meal);
    
    System.out.println("You ordered " + meals + " meals");
}   
}
