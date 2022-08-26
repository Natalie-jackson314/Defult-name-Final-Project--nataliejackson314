# Defult-name-Final-Project--nataliejackson314
import java.util.*;
import java.util.LinkedList;
import java.util.Scanner;
class Main {
  
  public static void main(String[] args) {
Scanner sc = new Scanner(System.in);
    Coldstone cstone = new Coldstone("Coldstone");
    System.out.println("Which ice cream shop would you like? Please select a place:\n");        
 System.out.println("1) Coldstone Creamery\n"
                  + "2) Farr Better Ice Cream\n"
                  + "3) Leatherby's Family Creamery\n"
                 );
    int choice = sc.nextInt();
     switch(choice) {
     case 1: cstone.IceCreamShopChoice();
    }
    Farr farrs = new Farr("Farr");
    switch(choice) {
    case 2: farrs.IceCreamShopChoice();
    }
    Leatherby leather = new Leatherby("Leatherby's");
    switch(choice) {
    case 3: leather.IceCreamShopChoice();
  }
    sc.close();
  
System.out.println(); 
ArrayList<Icecream> iceCream = new ArrayList <Icecream>();   

Coldstone mixin = new Coldstone("Coldstone"); 
mixin.setName("Coldstone");
    
Farr scoops = new Farr("Farr");
     scoops.name = "Farr";

Leatherby dinein = new Leatherby("Leatherby's");
    dinein.name = "Leatherby's";

iceCream.add(mixin);
iceCream.add(scoops);
iceCream.add(dinein);

for (Icecream icecream : iceCream){
      icecream.place();
    }

try {
      int[] orderNumber = {1, 2, 3};
      System.out.println(orderNumber[4]);
    } catch (Exception e) {
      System.out.println("Oops!");
    }

LinkedList<String> MostPopular = new LinkedList<String>();
System.out.println("Order of Popularity");
    
MostPopular.addLast("2) Coldstone Creamery");
MostPopular.addFirst("1) Leatherby's Family Creamery");
MostPopular.addLast("3) Farr Better Ice Cream");

for (int i = 0; i < MostPopular.size(); i++) {
  System.out.println(MostPopular.get(i));   
}
  }
}
