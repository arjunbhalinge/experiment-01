#include <stdio.h>

int main() {
    int switch_state;

    printf("Enter 1 to turn ON the light\n");
    printf("Enter 0 to turn OFF the light\n");
    printf("Enter your choice: ");
    scanf("%d", &switch_state);

    if (switch_state == 1) {
        printf("The light is ON.\n");
    }
    else if (switch_state == 0) {
        printf("The light is OFF.\n");
    }
    else {
        printf("Invalid input! Please enter 1 or 0.\n");
    }

    return 0;
}
