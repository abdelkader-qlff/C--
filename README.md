# C--
#MY FIRST PROJECT IN C++:

#include <iostream>
int main() {
		std::cout << "NAME:abdelkader anane\n"<<"AGE:17 ans\n" << "CITY:akbou\n" << "COUNTRIE:algeria";
}


 #my first variable:
 
#include <iostream>
using namespace std;
int main() {
	int result;
	result = 4 / 2;
	cout << "the result of 4/2 is" << ":" << "\t" << result << "\ni find it!";
	result = 20;
	cout << "\n\t" << endl << result;
}


#just a simple code:

#include <iostream>
using namespace std;
int main() {
	string Name = "Abdelkader";
	int Age = 17 ;
	string City = "Bejaia";
	string Country = "Algeria";
	int Monthly_Salary = 0000;
	int YEARLY_SALARY = 1000;
	char Gender = 'M';
	bool Married = false;
	//print:
	cout << "Name: " << Name << endl;
	cout << "Age: " << Age << " Years old" << endl;
	cout << "City: " << City << endl;
	cout << "Country: " << Country << endl;
	cout << "Monthly_Salary: " << Monthly_Salary << endl;
	cout << "Yearly salary: " << YEARLY_SALARY << endl;
	cout << "Gender: " << Gender << endl;
	cout << "Married: " << Married << endl;
}


#the big code that i am do at c++ even now:

#include <iostream>
using namespace std;
int main() {
	string Name;
	cout << "what is your name: ";
	cin >> Name;
	int Age;
	cout << "enter your age: ";
	cin >> Age;
	string City;
	cout << "where are you living: ";
	cin >> City;
	string Country;
	cout << "where are you from: ";
	cin >> Country;
	int Monthly_Salary;
	cout << "enter your Monthly_Salary: ";
	cin >> Monthly_Salary;
	char Gender;
	cout << "what is your Gender: ";
	cin >> Gender;
	bool Married;
	cout << "are you married?answer with true or false: ";
	cin >> Married;
	//print:
	cout << "Name: " << Name << endl;
	cout << "Age: " << Age << " Years old" << endl;
	cout << "City: " << City << endl;
	cout << "Country: " << Country << endl;
	cout << "Monthly_Salary: " << Monthly_Salary << endl;
	cout << "Yearly salary: " << Monthly_Salary * 12 << endl;
	cout << "Gender: " << Gender << endl;
	cout << "Married: " << Married << endl;
}

