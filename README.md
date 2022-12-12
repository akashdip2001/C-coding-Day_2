Coding by Akashdip Mahapatra

[![YouTube](https://yt3.ggpht.com/7tPHyFi7-QyTnhpc484ZzTuRp0fZSY-CUuykvzuKdKYIwt0fmw98SWMqwRy_7pZ6LQzEYJlvXA=s88-c-k-c0x00ffffff-no-rj-mo)](https://www.youtube.com/channel/UCxvmp634YDc41xCWOdvWqoQ)

<p align="left"> <img src="https://komarev.com/ghpvc/?username=akashdip2001&label=Profile%20views&color=0e75b6&style=flat" alt="akashdip2001" /> </p>

 🔭 I’m currently working on [**my web-site**](https://akashdip2001.github.io/linktree/)
 <h3 align="right">Connect with me:</h3>
 
<h1 align="right">AKASHDIP MAHAPATRA</h1>
<p align="right">

 <a href="https://akashdip2001.github.io/linktree/" target="blank"><img align="right" src="https://yt3.ggpht.com/7tPHyFi7-QyTnhpc484ZzTuRp0fZSY-CUuykvzuKdKYIwt0fmw98SWMqwRy_7pZ6LQzEYJlvXA=s88-c-k-c0x00ffffff-no-rj-mo" alt="akashdip2001" height="40" width="40" /></a>
<a href="https://linkedin.com/in/akashdip-mahapatra-330687204" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="akashdip-mahapatra-330687204" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/akash aot" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="akash aot" height="30" width="40" /></a>


</p>
<br/>

---
# C-cording-Day_2
C cording Day Day_2 

---
1) Write a C program to show the squar root of a positive integer given by the user.
```
 #include<stdio.h>
 #include<conio.h>
 #include<math.h> // I use this hadder file only for "sqrt"

int main()
{
  int n;
  printf("Enter a positive integer number\n");
  scanf("%d",&n);

  int r = sqrt(n);

  printf("Square root of %d = %d", n, r);
 return 0;
 }

 ```
 ---
 2) Write a C program to display the following statement using formatted output function " 169-AOT_B.Tech 1st Year_2022 "
 ```
 #include<stdio.h>

 int main()
 {
  printf("169-AOT_B.Tech 1st Year_2022");
  return 0;
 }
```
---
3) Write a C program to enter the radius of a circle using standard input function and show its area.
  ```
 #include<stdio.h>

 int main()
 {
 float r,A;
 printf("Enter the radius of circle\n");
 scanf("%f",&r);
        
 A=3.14*r*r;
 printf("The area of this circle is %f",A);
        
 // or printf("The area of this circle is %f",3.14*r*r); (with-out Using A, This way is easy to undersand for gcc compiler)
        
 return 0;
 }
   ```
---
4) Write a C program to enter the length of a side for a square and show the length of its diagonal using standard output function.  
```   
  #include<stdio.h>
  #include<math.h>

  int main()
  {
    float side,a,d;
    printf("Enter a side of squre\n");
    scanf("%f",&side);

    a=side*side;  //or,"a=pow(side,2);" is equal to side^2
    d=sqrt(a/0.5);  //because 1/2 = 0.5
 

     printf("The area of this circle is %f",d);
    return 0;
   }
```   
![Write a C program to enter the length of a side for a square and show the length of its diagonal using standard output function](https://user-images.githubusercontent.com/81384987/198893648-7464cde2-0954-47c2-baf0-9afe6ebb7843.png)

---
5) Write a C program to enter the length and breadth of a rectangle and show perimeter and area of rectangle.
```
 #include<stdio.h>
 int main()
 {
   float L,W,area,perimeter;
       
   printf("Enter the length\n");
   scanf("%f",&L);

   printf("Enter the breadth\n");
   scanf("%f",&W);

    area=L*W;
    perimeter=2*(L+W);

   printf("The area & perimeter of the rectangle is %f and %f",area,perimeter);
       
  return 0;
  }
```
![perimeter and area of rectangle](https://user-images.githubusercontent.com/81384987/198894416-f7acd83d-1ec0-4b65-9145-a4ce8926e03c.png)
---
6) Write a C program to find the number of subsets of a set containing 'n' elements (The value of n is given by user).
``` 
#include<stdio.h>
#include<math.h>
int main()
{
 int num,subset;
        
 printf("Enter the number\n");
 scanf("%d",&num);

 subset=pow(2,num);

 printf("Total subset of the number %d is %d",num,subset);
return 0;
}
 ```
 ![number of subsets of a set](https://user-images.githubusercontent.com/81384987/198895151-1403083c-ae2b-4d15-9e63-ee9f9897197e.png)

 ---
 7) Write a C program to check Even or Odd.
 ```
 #include<stdio.h>
 int main()
 {
    int number;
    printf("Enter the number \t");
    scanf("%d",&number);
              
    if(number%2==0)
    {
      printf("It's a even number\n");
    }
      else
    {
       printf("It's a odd number\n");
    }
   return 0;
  }
```
---
8) Write a C program to check the input is divisible by 3 or not.
```
 #include<stdio.h>
 int main()
 {
   int number;
   printf("Enter the number \t");
   scanf("%d",&number);
              
   if(number%3==0)
   {
    printf("It's divisible by 3\n");
   }
   else
   {
    printf("It's not divisible by 3\n");
   }
  return 0;
 }
```
---
9) Write a C program to check the input integer is square root or not ( Don't take imaginary value).
```
 #include<stdio.h>
 #include<math.h>
 int main()
 {
   int num;
   int iVar;
   float fVar;
      
   printf("Enter an integer number: ")
   scanf("%d",&num);  // example you enter 8
       
   fVar= sqrt((double)num); // double is use for - store the full floating value. example: 2.82842 🤔
          
   iVar = fVar;   // example: fVar= 2.82842 but iVar= 2 ( because "int iVar" )- it's save only integers 😁
   if(iVar==fVar)   // '==' chack fVar & iVar is equal or not , Example 2.82842 ≠ 2 😎
   { 
     printf("%d is a perfact squre.",num);
    } else {
      printf("%d is not a perfact aqure.",num);
     }
 return 0;
 }
```
---
10) Write a C program to swap two integers (with third varible).
```
 #include<stdio.h>
 int main() 
 {
  int a,b,temp;
       
  printf("Enter the value of A and B ");
  scanf("%d %d",&a,&b);  // Example A=4 , B=5
       
  printf("The value of A & B before is %d & %d \n",a,b);
       
  temp=a;  // value of A is copy to Temp -- Temp = 4 & A= empty
  a=b;     // value of B is copy to A  --  A = B = 5 & B= empty
  b=temp;  // value of Temp is copy to B -- B = Temp 
       
  printf("The value of A & B afterd is %d & %d \n",a,b);
       
 return 0;
}
```
![swap](https://user-images.githubusercontent.com/81384987/198898182-1d4636d1-8ed6-4e6c-9a75-66e44bc6272e.jpg)

---

| <a href="https://akashdip2001.github.io/C-coding-Day_1/" class="previous">&laquo; Previous Day</a> <br/> |
|--------------------------------------------------------------------------------------|
| <a href="https://akashdip2001.github.io/C-coding-Day_3/" class="next">Next Day &raquo;</a> |

---

<a href="https://akashdip2001.github.io/linktree/" target="blank"><img align="right" src="https://yt3.ggpht.com/7tPHyFi7-QyTnhpc484ZzTuRp0fZSY-CUuykvzuKdKYIwt0fmw98SWMqwRy_7pZ6LQzEYJlvXA=s88-c-k-c0x00ffffff-no-rj-mo" alt="akashdip2001" height="40" width="40" /></a>
<a href="https://www.youtube.com/c/akash aot" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="akash aot" height="30" width="40" /></a>


     
