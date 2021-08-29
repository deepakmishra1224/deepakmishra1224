#include<studio.h>
#include<studio.h>

int main() {
  int m, n;
  //Read m,n
  print("give values of m and n =");
  scanf("%d%" ,&m,&n);
  if (m>n) printf("%d > %d\n" ,m,n);
  else 
  if (m<n) printf("%d > %d\n" ,n,m);
  else printf("%d = %d\n" ,m,n);
  exit(0);
  }
  
