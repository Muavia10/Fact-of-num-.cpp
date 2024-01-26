# Fact-of-num-.cpp
//# Factorial-of-number-using-loop
#include<iostream>
using namespacestd;
int main()
{
int x,fact=1;
cout<<"enter a number";
cin>>x;
for(int i=x;i>=1;i--)
{
fact=fact*i;
}
cout<<"the factorial is "<<endl<<fact;
return 0;
}
