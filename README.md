Q  1.      #include <stdio.h>
             #include <conio.h>

void main() {
    int i, j;
    clrscr();
    for(i = 1; i <= 5; i++) {
        for(j = 41; j < 41 + i; j++) {
            printf("%d ", j);
        }
        printf("\n");
    }
    getch();
}                                                                                                                                                                                                                                                                                                                                                                                              Q 2.    #include <stdio.h>                                                                                                             
     #include <conio.h>

void main() {
    int i, j, num = 11;
    clrscr();
    for(i = 1; i <= 4; i++) {
        for(j = 1; j <= i; j++) {
            printf("%d ", num);
            num++;
        }
        printf("\n");
    }
    getch();
} 
Q 3.                                                                                                                                                                                                #include <stdio.h>                                                                                                                                                                          
#include <conio.h>

void main() {
    int i, j, space;
    clrscr();

    for(i = 5; i >= 1; i--) {
        // Print leading spaces
        for(space = 1; space < i; space++) {
            printf("  ");
        }

        // Print numbers from i to 5
        for(j = i; j <= 5; j++) {
            printf("%d ", j);
        }

        printf("\n");
    }

    getch();
}                                                                                                                                                                                                                                                                                                                                                                                           
Q 4.      #include <stdio.h>                                                                                                         
     #include <conio.h>

void main() {       
    int i, j;
    clrscr();
    for(i = 5; i >= 1; i--) {
        for(j = 1; j <= i; j++) {
            printf("%d ", (i + j) % 2);
        }
        printf("\n");
    }
    getch();
}                                                                                                                                                                                                                                                               Q  5.                                                                                                                                                                                                                                               #include <stdio.h>

void main() {
    int i, j;

    for(i = 5; i >= 1; i--) {
        for(j = 1; j < i; j++)
            printf("  ");  // spaces for pyramid shape
        for(j = i; j <= 5; j++)
            printf("%d ", j);  // ascending
        for(j = 4; j >= i; j--)
            printf("%d ", j);  // descending
        printf("\n");
    }
}                                                                                                                                                                                                                                                                 Q  6.                                                                                                                                                                                                                                               #include <stdio.h>

void main() {
    int i, j;

    for(i = 1; i <= 5; i++) {
        // Ascending part
        for(j = 1; j <= i; j++)
            printf("%d ", j);

        // Gap
        for(j = 1; j <= 2 * (5 - i); j++)
            printf("  ");

        // Descending part
        for(j = i; j >= 1; j--)
            printf("%d ", j);

        printf("\n");
    }
}                                                                                                                                                                                                                                                                  Q  7.                                                                                                                                                                                                                                               #include <stdio.h>

void main() {
    int i, j;

    for(i = 1; i <= 5; i++) {
        for(j = 1; j <= 5; j++) {
            if(j == 1 || (i == 1 && j <= 4) || (i == 3 && j <= 4) || (i == 2 && j == 5))
                printf("* ");
            else
                printf("  ");
        }
        printf("\n");
    }
}
