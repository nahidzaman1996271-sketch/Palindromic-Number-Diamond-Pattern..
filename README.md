# Palindromic-Number-Diamond-Pattern..
[main.c](https://github.com/user-attachments/files/23691338/main.c)
#include <stdio.h>
#include <stdlib.h>
int main(){
int i,j,n;
printf("Enter the value: ");
scanf("%d",&n);
for(i=1;i<=n;i++){
    for(j=1;j<=n-i;j++){
        printf(" ");
    }
    for(j=1;j<=i;j++){
        printf("%d",j);
    }
    for(j=i-1;j>=1;j--){
        printf("%d",j);
    }
    printf("\n");
}
for(i=n-1;i>=1;i--){
    for(j=1;j<=n-i;j++){
        printf(" ");
    }
    for(j=1;j<=i;j++){
        printf("%d",j);
    }
    for(j=i-1;j>=1;j--){
        printf("%d",j);
    }
    printf("\n");
}
return 0;
}
