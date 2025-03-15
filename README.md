# c-26
no arg - return values
#include<stdio.h>
int number(){
	return 99;
}
int main(){
	int n= number();
	printf("the number from sub function is %d \n",n);
	return 0;
