# first-year-c-coding
#include<studio.h>
#include<conio.h>
 Void main()
{
   int big,a[20],i,n;
   Print("enter number of elements in an array\n");
   Scant("%d",&n);
   Print("enter the %d elements",n);
   For(i=0;i<n;i++)
      Scanf("%d",&a[i]);
   big=a[0];
   For(i=0;i<n;i++)
 {
     if (a[i]>big);
   {
      big=a[i];
    }
  }
   Print("Biggest element of array is %d\n",big);
   getch();
}
