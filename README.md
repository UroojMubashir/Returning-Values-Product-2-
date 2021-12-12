#include <iostream>
using namespace std;

double sumItems (double item1, double item2){ 
double total = item1 + item2; 
    return total; 
}

int main()
{
double myMoney =40.00;
double shoes,tshirt;
cout<<"Kindly enter The Amount Of Shoes:"<<endl;
cin>>shoes;
cout<<"Kindly enter The Amount Of tshirt:"<<endl;
cin>>tshirt;

if (sumItems (shoes, tshirt) <= myMoney){ 
cout << "you can afford these items" << endl; 
    
} else {
cout << "keep saving up" << endl;
}
}-
