public class ArrayList {
    
    public static void main (String[] args) {
        String[] fruits = new String[5]; //added the amount of element
        fruits[0] = "Grapes";
        fruits[1] = "Bannanas";
        fruits[2] = "Apple";
        fruits[3] = "Melon";
        fruits[4] = "Orange";
        System.out.println(fruits);

        java.util.ArrayList fruitList = new java.util.ArrayList();
        fruitList.add("Grapes"); //adding fruit to list
        fruitList.add("Bannanas");
        fruitList.add("Apple");
        fruitList.add("Melon");
        fruitList.add("Orange");
        System.out.println(fruitList); 
    }
}
