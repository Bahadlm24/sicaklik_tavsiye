# sicaklik_tavsiye

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
    int heat ;

        Scanner input = new Scanner(System.in);
        System.out.print("sıcaklık giriniz");
        heat = input.nextInt();

        if (heat<5){
            System.out.println("kayak yapabilirsin");
        } else if (heat<=25) {
            if (heat<=15){
                System.out.println("sinemayya gidebilirsiniz");
            }
            if (heat>=10){
                System.out.println("pikniğe gidebilirsiniz");
            }
        } else if (heat>25) {
            System.out.println("yüzmeye gidebilirsiniz");
        }
    }
}
