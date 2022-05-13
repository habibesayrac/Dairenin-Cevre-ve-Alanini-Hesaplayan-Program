# Dairenin-Cevre-ve-Alanini-Hesaplayan-Program

import java.util.Scanner;
public class Main {

    public static void main(String[] args) {

   double radius, pi ,circum,area,area1;
   int aci;
   pi=3.14;
   Scanner input = new Scanner(System.in);
        System.out.println("Lütfen yarıçapı Giriniz: ");
        System.out.println("Lütfen Merkez Açı Değerini Giriniz :");
        radius = input.nextDouble();
        aci= input.nextInt();
        circum = 2*pi*radius;
        area = pi*Math.pow(radius,2);
        area1 = area*aci/360;

        System.out.println("Dairenin Çevresi : " + circum);
        System.out.println("Dairenin alanı : " + area);
        System.out.println("Daire Diliminin Alanı : " + area1);
        }
}
