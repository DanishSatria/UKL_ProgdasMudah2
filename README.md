import java.util.Scanner;

public class Soalmudah2 {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        // Meminta pengguna untuk memasukkan sebuah bilangan
        System.out.print("Masukkan sebuah bilangan: ");
        int bilangan = scanner.nextInt();
        
       
        if (bilangan % 2 == 0) {
            System.out.println(bilangan + " adalah bilangan genap.");
        } else {
            System.out.println(bilangan + " adalah bilangan ganjil.");
        }
        
      
    }
}
