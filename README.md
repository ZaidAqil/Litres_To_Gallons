# Litres_To_Gallons

// Zaid's Page 79 Exercise 3
#include <iostream>
#include <string>
using namespace std;

#define Litre_To_Gallons 0.264179
void efficiency(double,double);

int main()
{
	double litres,gallons ,kilometers ;
	cout << "What is the number of liters of petrol consumed by your car?" << endl;
	cout<<"Litres?:" ;
	cin>>litres ;
	cout<<"What is the number of Kilometers traveled by your car?"<<endl;
	cin>>kilometers;
	cout<<"The efficiency is"<<endl;
	efficiency(litres,kilometers);
	
    return 0;
}
void efficiency(double litres, double kilometers)
{
    
    cout<<(kilometers)/(litres *Litre_To_Gallons);
   
}
