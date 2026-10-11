# Functions-In-C-
#include &lt;stdio.h> 

int max_of_four(int a, int b, int c, int d)
{    
  int max = a;
 
  if (b > max) max = b;   
  if (c > max) max = c;    
  if (d > max) max = d;

  return max; 
 } 

 int main()
{  
 int a, b, c, d;    
 scanf("%d %d %d %d", &amp;a, &amp;b, &amp;c, &amp;d); 

 printf("%d", max_of_four(a, b, c, d));  

 vreturn 0;
}
