#include<stdio.h>

int main()
{

/*Declare varaibles*/
float A[4][3], B[4][3];
printf("\nStart Entering the value for first the Matrix");
for(int x=0;x<4;x=x+1)
{
    for(int y=0;y<3;y=y+1)
{
    scanf("%f",&A[x][y]);
}
}

printf("\nStart Entering the value for second the Matrix");
for(int x=0;x<4;x=x+1)
{
    for(int y=0;y<3;y=y+1)
{
    scanf("%f",&B[x][y]);
}
}
// Display Matrix A
printf("\n A=\n");
for(int x=0;x<4;x=x+1)
{
for(int y=0;y<3;y=y+1)
{
    printf("%f", A[x][y]);
}
    printf("\n");
}
// Display Matrix B
printf("\n B=\n");

for(int x=0;x<4;x=x+1)
{
    for(int y=0;y<3;y=y+1)
{
    printf("%ssf", B[x][y]);
}
    printf("\n");
}

}
