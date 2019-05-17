## if - else if - else

Write a program to read the value of an integer m (from 1 to 7) from the user and print the name of the weekday.
Example:
Enter number (1 – 7): 2
Today is Tuesday.
        int password = 6;
        Scanner input = new Scanner(System.in);
        int password = 5;
        int userInput = input.nextInt();
        int i = 3;
        while(i>0 && useInput != password){
            System.out.println("Your password is wrong, try again.");
            userInput = input.nexInt();
            i = i - 1;
        }
        if(password = userInput){
            System.out.println("You get 1000$");
        }
        else
        System.out.println("You can not get money, bye bye.");
    }
}
