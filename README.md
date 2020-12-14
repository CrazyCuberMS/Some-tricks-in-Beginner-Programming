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
