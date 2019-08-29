package var1;

import java.util.Scanner;

/**
 *
 * @author LENOVO
 */
public class Var1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
            int c=10;
            int d=20;
        System.out.println("Input your X: ");
        Scanner sc = new Scanner(System.in);
        int x = sc.nextInt();
        System.out.println("Input your Y: ");
        int y = sc.nextInt();
        if (x>0 && x<c && y>0 && y<c)
            System.out.println("Point in A");
        else if (x>-d && x<0 && y<0 && y>-d  && !(x>-c && x<0 && y>-c && y<0))
            System.out.println("Point in B");
        else System.out.println("Point not at A and B");
    }
    
}
