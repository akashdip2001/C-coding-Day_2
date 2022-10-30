Coding by Akashdip Mahapatra

[![YouTube](https://yt3.ggpht.com/7tPHyFi7-QyTnhpc484ZzTuRp0fZSY-CUuykvzuKdKYIwt0fmw98SWMqwRy_7pZ6LQzEYJlvXA=s88-c-k-c0x00ffffff-no-rj-mo)](https://www.youtube.com/channel/UCxvmp634YDc41xCWOdvWqoQ)

<p align="left"> <img src="https://komarev.com/ghpvc/?username=akashdip2001&label=Profile%20views&color=0e75b6&style=flat" alt="akashdip2001" /> </p>

 🔭 I’m currently working on [**my web-site**](https://akashdip2001.github.io/linktree/)
 <h3 align="right">Connect with me:</h3>
 
<h1 align="right">AKASHDIP MAHAPATRA</h1>
<p align="right">

 <a href="https://akashdip2001.github.io/linktree/" target="blank"><img align="right" src="https://yt3.ggpht.com/7tPHyFi7-QyTnhpc484ZzTuRp0fZSY-CUuykvzuKdKYIwt0fmw98SWMqwRy_7pZ6LQzEYJlvXA=s88-c-k-c0x00ffffff-no-rj-mo" alt="akashdip2001" height="40" width="40" /></a>
<a href="https://twitter.com/akashdipaot2001" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="akashdipaot2001" height="30" width="40" /></a>
<a href="https://linkedin.com/in/akashdip-mahapatra-330687204" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="akashdip-mahapatra-330687204" height="30" width="40" /></a>
<a href="https://fb.com/drawing.hobby.37" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="facebook" height="30" width="40" /></a>
<a href="https://instagram.com/akashdip_2001" target="blank"><img align="right" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="insta" height="30" width="40" /></a>
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
        float s,a,l;
        printf("Enter a side of squre\n");
        scanf("%f",&s);

        a=s*s;
        l=sqrt(a/0.5);  //because 1/2 = 0.5


        printf("The area of this circle is %f",l);
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
6) Write a C program to take a floating-point number from user and show its value.
``` #include<stdio.h>
   int main()
   {
       float a,b;
        printf("Enter Two integers \n");
        scanf("%f %f",&a,&b);
   
       printf("Two integers is %f & %f ",a,b);
       return 0;
    }
 ```
 ---
 7) Write a C program to take a character variable from user and show its value.
 ```
       #include<stdio.h>
       int main()
       {
              char name;
              printf("Enter your name \n");
              scanf("%c",&name);
       
              printf("The first later of your name is %c",name);
              
       return 0;
       }
```
---
8) Chack the validity of following identifiers (mentioned below) through the compilation of C. <br/>
       i)   a2 <br/>
       ii)  2a <br/>
       iii) @b <br/>
       iv)  b_2 <br/>
       v)   1_c <br/>
```
```
