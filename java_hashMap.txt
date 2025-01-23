import java.util.HashMap;

public class Main {
  public static void main(String[] args) {
   HashMap<Integer, String> hm = new HashMap<>();
      
        hm.put(1, "Krishna");
        hm.put(2, "Harsha");
        hm.put(3, "Rama");
        hm.put(4, "Arfan khan");
        hm.put(5, "Joseph");
      
        hm.forEach((key, value) -> {   
        
        
            System.out.println("Key : " + key + " Value : " + value);
        });
}
}