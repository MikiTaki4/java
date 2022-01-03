package Excersie;
import java.util.Random;
import java.util.Scanner;

class ravi{
    public int mNumber;
    public int number ;


    public void  number(){
        Scanner num  = new Scanner(System.in);
        System.out.println("Please Enter The Any Number Under The 50  ");

        int B = num.nextInt();
        number = B;
        if (number > 50 ){
            System.err.println(" Your Are Wrong  Number Enter ");
            System.out.println("Please Right Number Enter Under The 50");
            int Right=num.nextInt();
            Right=number;
        }
        System.out.println(number+" Your Choose Number ");



    }

    public void mNumber(){
        Random rr = new Random();
       int  A=rr.nextInt(50);
        mNumber=A;
        System.out.println(mNumber+" ! Computer Choose Number ");
        reslut();

    }
    public  void reslut(){
        if (number > mNumber){
            System.err.println(" You Win");

        }
        else if(number== mNumber)  {
            System.out.println(" Match Is Draw");

        }
        else if (mNumber>number){
            System.err.println(" Computer Win");
        }

    }


}



public class Simplegame {

    public static void main(String[] args) {
        /*Random ram = new Random();
        int ravi = ram.nextInt(10);
        System.out.println (ravi+" Your Random Number ");

         */
        ravi ramj = new ravi();

        ramj.number();
        ramj.mNumber();

    }
}
