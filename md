#include<stdio.h>
void main(){
    int arr[50], sum=0, a, k, j;
    printf("n: ");
    scanf("%d",&a);
    printf("k: ");
    scanf("%d",&k);
    printf("Enter array: \n");
    for(j=0;j<a;j++){
        scanf("%d",&arr[j]);
    }
    for(j=0;j<k;j++){
        sum = sum + arr[j];
    }
    printf("%d\n",sum);
}
