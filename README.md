import java.util.Scanner;
public class test {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        float kilo,boy,inds;

        System.out.println("Boyunuzu metre cinsinden yazınız:");
        boy= input.nextFloat();

        System.out.println("Kilonuzu giriniz.");
        kilo= input.nextFloat();

        inds = kilo / (boy*boy);

        System.out.println("Vücut kitle endeksiniz:" + inds);

    }
}
