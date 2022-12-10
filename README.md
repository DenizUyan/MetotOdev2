# MetotOdev2

import java.util.Scanner;
public class Main {
    static void asal(){

        Scanner input = new Scanner(System.in);
        System.out.print("Sayi Giriniz: ");
        int sayi = input.nextInt();
        boolean prime = true;
        for(int a = 2; a<sayi; a++){
            if(sayi%a==0){
                 prime = false;
            }
        }
        if(prime){
            System.out.println(sayi+" asaldir");
        }
        else{
            System.out.println(sayi+" asal değildir");
        }


    }
    public static void main(String[] args) {
        asal();

    }
}
