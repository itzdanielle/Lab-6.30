# Lab-6.30
#include <iostream>
using namespace std;

int main() {
  int num1;				// num1 is not initialized
	int num2;     // num2 has been initialized to 5

    cout << "Please enter an integer" << endl;
	  cin >> num1;

    cout << "Please enter an integer" << endl;
    cin >> num2;

	  cout << "num1 = " << num1 << " and num2 = " << num2 << endl;
    
    if (num1 == num2)
    {
		  cout << "The values are the same." << endl;
      cout << "Hey that's a coincidence!\n";
    }
    
    else  
	  	cout << "The values are NOT the same" << endl;
    
    
    
}
