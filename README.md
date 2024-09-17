import java.util.Scanner;
public class Main
{
    
    
    
    public static void main(String[] args) {
    Scanner scan = new Scanner(System.in);
    System.out.println("Digite as suas 4 notas bimestrais: ");
    int N1 = scan.nextInt();
    int N2 = scan.nextInt();
    int N3 = scan.nextInt();
    int N4 = scan.nextInt();
    
    float Media = (N1 + N2 + N3 + N4)/4f;
    System.out.println(Media);
    
    if (Media >= 70){
        System.out.println("APROVADO");
    }
    else{
        System.out.println("REPROVADO");
    }
    }
}
