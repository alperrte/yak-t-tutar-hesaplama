
import java.util.Scanner;

public class Main {

    public static void main(String[] args){
        Scanner scanner=new Scanner(System.in);
        System.out.print("Araciniz kilometrede ne kadar yakiyor?(Ornek: 5,32) ");
        double kmYakit = scanner.nextDouble();
        System.out.print("Toplamda kac kilometre yol yaptiniz ? (Ornek: 532,3) ");
        double yol=scanner.nextDouble();
        double masraf=kmYakit*yol;
        System.out.println("Toplam yaptiginiz yol icin yakit masrafiniz:  "+masraf +"TL");
        scanner.nextLine();
    }
}
