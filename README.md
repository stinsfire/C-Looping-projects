# C-Looping-projects
source codes for projects done on C++ looping
#include <iostream>
using namespace std;
int main() {
  cout<<"This program calculates the sum of the digits of an inputed number"<<endl;
   cout<<"Enter a number with at least two digits"<<endl;
   long long int num{};
   bool validator {false};
   cin>>num;
   while (num>10==validator){
   cout<<"Invalid number entered. You must enter a number with at least two digits "<<endl;
   cin>>num;
   }
   long long int digit{};
   long long int i=num;
   while(i<10==false){
     digit+=i%10;
     i=i/10;
   }
  digit+=i;
  cout<<"The sum of the digits of "<<num<<" is "<<digit<<endl;
     
   }
