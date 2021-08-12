#include <stdio.h>
#include <stdlib.h>
int main()
{
    FILE *ptr = NULL;
    char name[30];
    int n, i;
    float marks;
    ptr = fopen("E:Marks.txt", "a");//append mode
    if (ptr == NULL)
    {
        printf("file is not opened ");
        exit(1);
    }
    printf("enter the number of students :\n");
    scanf("%d", &n);
    for (i = 0; i < n; i++)
    {
        printf("enter name of %d student : ", i + 1);
        scanf("%s", name);
        printf("enter its marks :");
        scanf("%f", &marks);
        fprintf(ptr, "name is %s and its marks is %f\n", name, marks);
    }
    fclose(ptr);
    return 0;
}
