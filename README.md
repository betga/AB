# AB
#include <iostream>

/* coonvert from Celsius to Kelvin */
#include <string>
#include <vector>

using namespace std;
int main(int argc, char** argv[1]) {
float k, c;
cout<<"\n\nConverting temp. in Celsius to kelvin ";
cout<<"========================================\n";
cout<<"Enter the Celsius (Temp.) : ";
cin>>c;
k=c+273.15;
cout<<"The Celsius (Temp.): "<< c<<endl;
cout<<"The kelvin (Temp.): "<< k<<endl;
cout<< endl;
for(int i=0; i<10; i++)
std::cout<<"for loop: " <<i<<
std::endl;
	return 0;
}
