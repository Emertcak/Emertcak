int main ( )
{
   int i, factorial number ; 
   factorial = 1 ;

   print (" Enter a number: " );
   scanf (" %d ",  number) ; 

   for ( i=number ; i >=1 ; i-- ) {
       factorial * = i ;
}
printf (" %d! = %d\n", number, factorial ) ;
return 0;
}
