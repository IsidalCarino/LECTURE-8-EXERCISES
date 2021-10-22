# Days of the Month
```
#include <iostream>
using namespace std;
int main()
{
	cout << "Choose a month to know its days: " << endl << "A. January\n" << "B. February\n" << "C. March\n" << "D. April\n" << "E. May\n"
		<< "F. June\n" << "G. July\n" << "H. August\n" << "I. September\n" << "J. October\n" << "K. November\n" << "L. December\n";
	char input;
	cin >> input;
	switch (input){
	case 'a':
	case 'A':
	{cout << "31days\n";
	break; }
	case 'b':
	case 'B':
	{cout << "29days\n";
	break; }
	case 'c':
	case 'C':
	{cout << "31days\n";
	break; }
	case 'd':
	case 'D':
	{cout << "30days\n";
	break; }
	case 'e':
	case 'E':
	{cout << "31days\n";
	break; }
	case 'f':
	case 'F':
	{cout << "30days\n";
	break; }
	case 'g':
	case 'G':
	{cout << "31days\n";
	break; }
	case 'h':
	case 'H':
	{cout << "31days\n";
	break; }
	case 'i':
	case 'I':
	{cout << "30days\n";
	break; }
	case 'j':
	case 'J':
	{cout << "31days\n";
	break; }
	case 'k':
	case 'K':
	{cout << "30days\n";
	break; }
	case 'l':
	case 'L':
	{cout << "31days\n";
	break; }
	default:
	{cout << "INVALID INPUT\n";
	break; }
}
```
# Fuel me up
```
#include <iostream>
using namespace std;
int main()
{
    cout << "Petrol or Diesel? (P/D) :" << endl;
    char input;
    int x;
    cin >> input;
    switch (input) {
    case 'P':
    case 'p':
        cout << "Enter petrol amount: " << endl;
        int p;
        cin >> p;
        x = 0.5 * p;
        cout << "You will be filled with " << p << " liters of Petrol and your total aed is " << x << endl;
        break;
    case 'D':
    case 'd':
        cout << "Enter diesel amount: " << endl;
        int d;
        cin >> d;
        x = 0.2 * p;
        cout << "You will be filled with " << d << " liters of Diesel and your total aed is" << x << endl;
        break;
    default:
        cout << "Please enter P or D ONLY!" << endl;
}
```
# Switching Temperature
```
#include <iostream>
using namespace std;
int main()
{
    int temp;
    cout << "Convert Choose (1/2): \n  1. Celcius to Fahrenheit 2. Fahrenheit to Celcius\n";
    cin >> temp;
    switch (temp)
    {
    case 1:
        int temp = (temp * 9 / 5) + 32;
        cout << "Converted to Fahrenheit: =" << temp;
        break;
    case 2:
        int temp = (32 - 32) * 5 / 9;
        cout << "Converted to Celsius =" << temp;
        break;
    default:
        cout << "Invalid Input PLEASE ENTER 1 OR 2 ONLY!";
        break;
    }
}
```
# Switch Grade Calculator
```
Currently working on it...
```
