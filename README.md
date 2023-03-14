# Assignment-Submission-Day-3
Question 1.
#include <stdio.h>

int main() {

    int M;

    printf("Enter a number: ");

    scanf("%d", &M);

    if (M % 3 == 0 && M % 5 == 0) {

        printf("Good Number\n");

    }

    return 0;

}

Question 2.

#include <stdio.h>

int main() {

    int num;

    printf("Enter a number: ");

    scanf("%d", &num);

    if (num % 3 == 0 && num % 5 != 0) {

        printf("Bad Number\n");

    }

    return 0;

}

 Question 3.

#include <stdio.h>

int main() {

    int num;

    printf("Enter a number: ");

    scanf("%d", &num);

    if (num % 5 == 0 && num % 3 != 0) {

        printf("Poor Number\n");

    }

    return 0;

}

Question 4.

#include <stdio.h>

int main() {

    int num;

    printf("Enter a number: ");

    scanf("%d", &num);

    if (num % 3 == 0 && num % 5 != 0) {

        printf("Bad Number\n");

    }

    else if (num % 5 == 0 && num % 3 != 0) {

        printf("Poor Number\n");

    }

    else {

        printf("-1\n");

    }

    return 0;

}

