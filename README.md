# Dairenin-Alan-n-ve-evresini-Hesaplayan-Program        
Java ile yarı çapını kullanıcıdan aldığınız dairenin alanını ve çevresini hesaplayan programı yazın.         www.patika.dev

    import java.util.Scanner;

    public class Main {
    public static void main(String[] args) {

       int r;
       double  pi=3.14;

       Scanner asd =new Scanner(System.in);

       System.out.print("Dairenin Yarı Çapını Giriniz :");
       r = asd.nextInt();
       

       double Alan= pi*r*r;
       double Cevre = 2*pi*r;

        System.out.println("Daire Alanı :" + Alan);
        System.out.println("Daire Cevresi :" + Cevre);
