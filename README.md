Pyramid star pattern
To print the Pyramid star pattern we need two loop. first is outer loop and second is inner loop.

first loop that is the outer loop works on the row or line and the another loop that is inner loop works on the column mean how many start you want to put in the single line.so here we need to now proper working of the loop that we can easily make a desired pattern.

Now we will discuss all possible star pattern using java. 


1. Write a Program to print the following pattern.
* 
* * 
* * * 
* * * * 
* * * * *
Working
Step 1- first you need to initialize two variable for loop.

Step 2- the first loop  for the row.

Step 3-  the second loop work for the column.

Step 4- now print the *.

Step 5- now out side of loop, put new line.

Step 5- stop.

C	JAVA	Python 1	Python 2	C++
public class Main
{
       public static void main(String[] args) 
       {
             int i,j;
             //this loop work on the row 
             for(i=0;i<5;i++)
             {
                   //this loop work on the column 
                   for(j=1;j<=i;j++)
                   {
                         System.out.print("* ");
                   }
                   System.out.println();
              }
        }
}
2. Write a program to print the following pattern
* 
* * * 
* * * * * 
* * * * * * * 
* * * * * * * * *
C	JAVA	Python 1	Python 2	C++
public class Main
{
	public static void main(String[] args) {
		int i,j,k=1;
                //this loop work on the row
		for(i=0;i<5;i++)
		{
                        //this loop work on the column
                        //here we want to print * two more than previous row
                        //so this loop work on the k
			for(j=0;j<k;j++)
				System.out.print(" * ");
                        //increment k with 2 
			k=k+2;
			System.out.println();
		}
	}
3. Write a program to print the following pattern
        * 
      * * 
    * * * 
  * * * * 
* * * * *
C	JAVA	Python 1	Python 2	C++
public class Main
{
    public static void main(String[] args) 
    {
          int i,j,k=8;
            //this loop work on the row
           for(i=0;i<5;i++)
           {
                  //this loop work for spaces
                  for(j=0;j<k;j++)
                          System.out.print(" ");
                  //decrement k for reduce the spaces in next row
                  k=k-2;
                  //this loop work for print the *
                  for(j=0;j<=i;j++)
                          System.out.print("* ");
                  System.out.println();
             }
       }
}
4. Write the code to print the following patter
                * 
            * * * 
        * * * * * 
    * * * * * * * 
* * * * * * * * *
C	JAVA	Python 1	Python 2	C++
public class Main
{
     public static void main(String[] args) 
     {
           int i,j,k=16,s=1;
           //this loop work on the row
           for(i=0;i<5;i++)
           {
                //this loop work on space
                for(j=0;j<k;j++)
                    System.out.print(" ");
                    //decrement k for reduce the spaces in the next row
                k=k-4;
                //this loop work on the column
                //here we want to print * two more than the previous row
                //so this loop work on the k
                for(j=1;j<=s;j++)
                     System.out.print("* ");
                 //increment s with 2
                 s=s+2;
                 System.out.println();
            }
       }
}
5. Write the code to print the following pattern.
    *
   ***
  *****
 *******
*********
C	JAVA	Python 1	Python 2	C++
public class Main
{
   public static void main(String[] args)

   {
       int i,j,k=0,row=5;

      //this loop work on the row
       for (i=1;i<=row;i++)
      {

           //this loop work for both the space and print *
            for(j=1;j<=row-i;j++)
                    System.out.print(" ");

           //until value of the k is not equal to 2*i-i, it print star
            while(k!=(2*i-1))
            {
                  System.out.print("*");
                   k++;
            }
           k=0;
          System.out.println();
       }
    }
}
