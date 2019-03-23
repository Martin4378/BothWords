# BothWords

import java.util.Scanner;

public class P18_BothWords {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        String firstWord = scanner.nextLine();

        String secondWord = scanner.nextLine();

        if(secondWord.equalsIgnoreCase(firstWord)){
            System.out.println("yes");
        }
        else{
            System.out.println("no");
        }

    }
}
