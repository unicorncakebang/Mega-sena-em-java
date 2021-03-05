# Mega-sena-em-java
Compilador de loteria para os jogos da mega-sena.
//compialdor mega-sena
import java.util.*;
import java.util.Random;
import java.util.Scanner;

public class loteria {
    
    public static void main(String args[]){
         int y;
        Scanner sc = new Scanner(System.in);
        
        
        System.out.print("Quantos números:");
          y=sc.nextInt(); 
    
        int  []w = new int[y];
        Random r =new Random();
        for(int i =0; i< w.length;i++)
            
            w[i]=r.nextInt(60);
        
        for(int i =0; i< w.length;i++)
            System.out.print(w[i] + "\n ");
        if(y == 6){
            System.out.print("Boa sorte na Mega-Sena");
        }
        else{
            System.out.print("Boa sorte");
        }
    }
    
}
