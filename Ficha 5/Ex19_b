#include <stdio.h>
int fatorial(int fatorizar);

int main(void) {

  int fatorizar1,fatorizar2,formula=0;

  printf("Insira um número(n): ");
  scanf("%d",&fatorizar1);
  printf("Insira um número(p): ");
  scanf("%d",&fatorizar2);

  if(fatorizar1 > 0 && fatorizar2 > 0 && fatorizar1 > fatorizar2){
    
    formula = fatorial(fatorizar1)/(fatorial(fatorizar2) * fatorial((fatorizar1-fatorizar2)));
    printf("%d",formula);
  }
}

int fatorial(int fatorizar){
  int multipli=1, n=fatorizar;

  for(int i=0;i < fatorizar-1;i++){
    multipli = multipli*n;

    n--;
  }

  return multipli;
}