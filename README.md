# Program-Analysis-Project
Use bitwise algorithm to create reaching definitions and live variable analysis for the following C program 
<br>
int main()
{
    // variable declaration
    int i, number;

    // take user input
    printf("Enter a number: ");
    scanf("%d", &number);

    // loop to check number is perfect square or not
    for(i = 0; i <= number; i++)
    {
        if(number == i*i)
        {
            printf("%d is a perfect square\n", number);

            printf("Coding is Fun !");
            return 0; 
        }
    }
    printf("%d is not a perfect square\n", number);
    printf("Coding is Fun !");
    return 0;
}

