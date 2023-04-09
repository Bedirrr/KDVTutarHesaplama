import java.util.Scanner;

public class KDV {
    public static void main(String[] args) {
        double tutar,kdvOran = 0.18;
        Scanner input = new Scanner(System.in);
        System.out.print("Ücret Tutarını Giriniz : " );
        tutar = input.nextDouble();
        double kdvTutar = tutar * kdvOran;
        System.out.println(kdvTutar);
        double kdvliTutar = tutar + kdvTutar;
        System.out.println(kdvliTutar);
        System.out.println("KDV'siz Tutar :" + tutar);
        System.out.println("KDV Oranı :" + kdvOran);
        System.out.println("KDV Tutarı :" + kdvTutar );
        System.out.println("KDV'li Tutar:" + kdvliTutar);

    }
}
