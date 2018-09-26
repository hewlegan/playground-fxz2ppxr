My first real actual good script

    import java.util.Random; 

    public class Main {
       
    
    
    public static void main (String[] args) {
        Random rand = new Random();

        int  a = rand.nextInt(10) + 1;
        
        String name = "Viewer";
        if (a + 3 <= 10) {
        
        System.out.println("Hello " + name + "!");
        }
        else {
            System.out.println("Goodbye " + name + "!");
        }
    }

}
