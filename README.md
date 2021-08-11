# 13.-ARRAYS
accessing two dimensional arrays
#include <stdio.h> 
  int main () 
{ 
   
   int a[5][2] = { {0,0}, {1,2}, {2,4}, {3,6},{4,8}}; 
   int i, j; 
  
      for ( i = 0; i < 5; i++ ) 
   { 
      for ( j = 0; j < 2; j++ ) 
      { 
         printf("a[%d][%d] = %d\n", i,j, a[i][j] ); 
      }    }    return 0; 
} 

accessing a single dimensional
#include <stdio.h> 
  int main () 
{ 
   int n[ 10 ]; 
   int i,j; 
  
               for ( i = 0; i < 10; i++ ) 
   { 
      n[ i ] = i + 100;  	 
   } 
    
     for (j = 0; j < 10; j++ ) 
   { 
      printf("Element[%d] = %d\n", j, n[j] ); 
   }   
   return 0; 
} 
