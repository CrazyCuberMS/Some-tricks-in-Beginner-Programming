 != 3    x = x|3  >>= 3  x= x>>3    <<= 3  x= x<<3
 
 Concatenation "+"
 .append()
 firstname = "Mubin";
 lastname = "Hasan";
 firstname.append(lastname);
 
 cout<< (10>9); // Output true 1 //
 cout<< (9>10); // Output false 0 //
 
 for(int i=0; i<10; i++){
 if (i==4){break;} // Jumps out of the loop //
 else {cout << i} }

for(int i=0; i<10; i++){
 if (i==4){continue;} // Skips the value //
 else {cout << i} }

Same explanation goes in while

string name;
    cout<<"Enter your name :" ;
    getline(cin, name);
    cout<<"Hello "<<name;

std::string a;
	std::cin >> a;
	for( int i=a.size()-3 ; i >0; i= i-3 )
	{   a.insert(i ,",");   }
	std::cout << a;
	
#include <iomanip>
	cout << std::fixed<< m 
	
#include <iostream>
#include <string>



int main()
{
std::string a,b;
std::cin >> a >> b;

    std::sort(a.begin(),a.end());
    std::sort(b.begin(),b.end());

    if ( a==b)
    {
        std::cout << "Yes";
    }
    else { std::cout << "No";}

    return 0;
}

#include <bits/stdc++.h>
using namespace std;

int main()
{
    ios_base::sync_with_stdio(false);
    cin.tie(NULL);
    return 0;
}
