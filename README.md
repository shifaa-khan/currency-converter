# currency-converter
#include<stdio.h>
int main() {
  float inr,qar,rate;
  printf("enter amount in rs:");
  scanf("%f",&inr);
  rate=25;
  qar=inr*rate;
  printf("amount in qar:%f",qar);
  return 0;
 
}