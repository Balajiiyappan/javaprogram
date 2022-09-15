import java.util.Scanner;
class Main {
 public static void main(String[] args) {
      Scanner sc = new Scanner(System.in);
      System.out.println("Enter the size of the array 1:");
      int size1 = sc.nextInt();;
      int[] arrayEx1 = new int[size1];
      System.out.println("Enter the elements:");
      try {
         for(int i=0; i<arrayEx1.length; i++) {
         arrayEx1[i] = sc.nextInt();
      }
      System.out.println("Enter the size of the array 2:");
      int size2 = sc.nextInt();
      int[] arrayEx2 = new int[size2];
      System.out.println("Enter the elements:");
      for(int i=0; i<arrayEx2.length; i++) {
         arrayEx2[i] = sc.nextInt();
      }
  for(int i = 0; i < arrayEx1.length; i++){
   for(int j = 0; j < arrayEx2.length; j++){
    if(arrayEx1[i] == arrayEx2[j] && arrayEx1[i]>0){
     System.out.println("The commom elements are: "+arrayEx1[i]);
     break;
    } 
   }
  }
      } catch(Exception e) {
          System.out.println("invalid input");
      }
    }
   }
