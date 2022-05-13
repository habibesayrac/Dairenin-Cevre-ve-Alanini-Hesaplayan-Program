# Dairenin-Cevre-ve-Alanini-Hesaplayan-Program

import java.util.Scanner;
public class Main {

    public static void main(String[] args) {

   double radius, pi ,circum,area;
   pi=3.14;
   Scanner input = new Scanner(System.in);
        System.out.println("Lütfen yarıçapı Giriniz: ");
        radius = input.nextDouble();
        circum = 2*pi*radius;
        area = pi*Math.pow(radius,2);
        System.out.println("Dairenin Çevresi : " + circum);
        System.out.println("Dairenin alanı : " + area);
        }
}
