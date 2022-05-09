# Running-training
 that is  about energy of a person in the running training

#include<iostream>
 
 using namespaces std;
 
 int main()
 {
   int n = 10000;
   int consume = 600/60;
   int time = 0;
   while(n)
   {
     if(n-600<0)
     {
       time = time * 60 + n/consume;
       break;
     }
     n -= 600;
     n += 300;
     time += 2;
   }
   cout << time << endl;
   system("pause");
   retrun 0 ;
 }
