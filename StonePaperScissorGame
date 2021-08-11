//stone paper scissors game in java language

import java.util.Scanner;

import java.util.Random;

public class StonePaperScissors {
    static int Fun(char a, char b) {
        if(a==b)
        return 0;
        if (a == 'P' && b == 'S')
            return 1;
        else if (a == 'C' && b == 'P')
            return 1;
        else if (a == 'S' && b == 'C')
            return 1;
        else if (a == 'S' && b == 'P')
            return -1;
        else if (a == 'P' && b == 'C')
            return -1;
        else
            return -1;

    }

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        Random rand = new Random();
        boolean indicator=true;
        while(indicator==true){
        indicator=true;
        System.out.println("enter S for Stone , P for paper , C for scissors");
        char myChar = input.next().charAt(0);
        int ran = rand.nextInt(100);
        char comChar;
        if (ran <= 33)
            comChar = 'S';
        else if (ran > 34 && ran <= 66) {
            comChar = 'P';
        } else
            comChar = 'C';

        System.out.println("I choose " + myChar);
        System.out.println("computer choose " + comChar);
        int result = Fun(myChar, comChar);
        if (result == 1){
            System.out.println("you win");
            indicator=false;
        }
        else if(result==0)
        System.out.println("draw!");
        else
            System.out.println("you lose");
    }
        input.close();

    }
}
