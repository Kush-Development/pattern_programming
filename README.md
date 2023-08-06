# pattern_programming
//I aim to solve some patterns in java language which help to my logic building.


public class App {
    public static void main(String[] args) throws Exception {
        System.out.println("Hello, World!");

       

       

         pattren star = new pattren();
         star.blank();


    }

   
        
    }


import java.util.Scanner;

public class pattren {

 public void blank() 
 {
    try (Scanner scan = new Scanner(System.in)) {
      int n = scan.nextInt();

 for ( int i = 0 ; i<=n ; i++ )
 {

          for (int j = 0 ; j <=  n ; j++ )

             {
              if( i == 0 || i == n || j == 0  || j == n || i ==n/2 || j== n/2 || i+ j == n/2|| j-i == n/2  || i+ j == (2*n-2+n-1)/2 || i-j==n/2 || i==j || i+ j == n-1)
               {

               System.out.print("* ");
               } 
               else 
               { System.out.print("  ");

               }
                 
              } 

          System.out.println();

  }
    }

 }


   
}



