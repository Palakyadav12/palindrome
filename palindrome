#include <stdio.h>
    #include<stdbool.h>
    #include <math.h>
    
    int reverse(int num)
    {
        int rev= 0;
        while (num > 0)
        {
            rev= rev * 10 + num % 10;
            num = num / 10;
        }
        return rev;
    }
    
    int isPalindrome(int num)
    {

      int r=  reverse(num);
      
        if (num == r)
            return true;
        else
            {return false;}
        return 0;


    }

    
    int main()
    {
        int x;
        printf("input no:");
        scanf("%d", &x);
        if(isPalindrome(x))
        printf("yes palindrome");
        else
        printf("not palindrome");
        return 0;
    }
