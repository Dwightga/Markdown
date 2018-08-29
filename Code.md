
~~ Block Code ~~


#include <stdio.h>
#include <time.h>
#define SIZE 100

int main(void)
{


    int size[100];
    int max;
    int i;

    printf("Enter the size of the array to be generated:\n");
    scanf ("%d" , &size);

    printf("Enter the maximum random value to be inserted in the array:\n");
    scanf("%d" , &max);

    while(max < 0 || max > 100)

    {



        printf("Invalid number ! Enter a maximum random value between 0 and 100:\n");
        scanf("%d" , &max);}


    for(i=0; i < size; i++){

        printf("%7d%13d\n", i , max[i]);
    }


    return 0;

}

Butterfly
* * *
