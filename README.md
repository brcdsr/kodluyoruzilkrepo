# kodluyoruzilkrepo
Kodluyoruz Eğitimi kapsamında açtığım ilk repo
import java.util.Scanner;

public class Burcux {
    public static void main(String[] args) {
       int Matematik, Fizik, Kimya, Türkçe, Tarih, Müzik ;

        Scanner Mari = new Scanner(System.in);
        System.out.println("Matematik notu : ");
        Matematik = Mari.nextInt();

        System.out.println("Fizik notu : ");
        Fizik = Mari.nextInt();

        System.out.println("Kimya notu : ");
        Kimya = Mari.nextInt();

        System.out.println("Türkçe notu : ");
        Türkçe = Mari.nextInt();

        System.out.println("Tarih notu : ");
        Tarih = Mari.nextInt();

        System.out.println("Müzik notu : ");
        Müzik = Mari.nextInt();

        int T = (Matematik + Fizik + Kimya + Türkçe + Tarih + Müzik) ;
        double Ortalamanız = T/6;
        System.out.println("Not Ortalamanız : " + Ortalamanız);

        String Durum =  ( Ortalamanız > 60 ) ? "Sınıfı Geçti" : "Sınıfta Kaldı";
        System.out.println(Durum);
