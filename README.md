import java.util.Scanner;
//TIP To <b>Run</b> code, press <shortcut actionId="Run"/> or
// click the <icon src="AllIcons.Actions.Execute"/> icon in the gutter.
public class Main {
    public static void main(String[] args) {
      Scanner sc = new Scanner(System.in);
      System.out.print("enter mark : ");
      double mark = sc.nextDouble();
      System.out.print(" enter physics ");
      double physics = sc.nextDouble();
      System.out.print("enter chemistry: ");
      double chemistry = sc.nextDouble();
      double GVA = (mark + physics + chemistry)/3;
      System.out.println("GVA =" + GVA);
      System.out.println();
      if (GVA<=5.0)
      { System.out.println("your rank is D");}
      if (GVA > 5 && GVA<=8.5)
      {
        System.out.println("your rank is C");
      }
      if  (GVA > 8.5 &&GVA<=9.5)
      {
        System.out.println("your rank is B");
      }
      if (GVA > 9.5 && GVA<=10.0)
      {
        System.out.println("your rank is A");
      }
      else  if (GVA>10.0)
      {
        System.out.println("Error");

      }


    }
}
