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


#the latest code with another way:

#include <iostream>
using namespace std;
int main() {
	//input:
	string name;
	cout << "enter your name: ";
	cin >> name;
	int age;
	cout << "what is your age: ";
	cin >> age;
	string city;
	cout << "where are you living: ";
	cin >> city;
	string country;
	cout << "where are you from: ";
	cin >> country;
	int monthlysalary;
	cout << "how much your monthly salary: ";
	cin >> monthlysalary;
	char gender;
	cout << "enter your gender(M or F): ";
	cin >> gender;
	bool married;
	cout << "are you married(answer with true or false): ";
	cin >> married;
	//print:
	cout << "\nyour information card:\nname: " << name << endl << "age: " << age << endl << "city: " << city << endl << "country: " << country << endl << "monthly salary: " << monthlysalary << endl << "yearly salary: " << monthlysalary * 12 << endl << "gender: " << gender << endl << "married: " << married << endl;

}



#simple calculator:

#include <iostream>
using namespace std;
int main() {
	int value1, value2, value3;
	cout << "enter the first number: ";
	cin >> value1;
	cout << "enter the SECOND number: ";
	cin >> value2;
	cout << "enter the THIRD number: ";
	cin >> value3;
	int total_values = value1 + value2 + value3;
	cout << value1 << " +" << endl << value2 << " +" << endl << value3 << endl << "-------------------" << endl << "= " << total_values;
}


#simple code:

#include <iostream>
using namespace std;
int main() {
	int originalage;
	cout << "what is your age: ";
	cin >> originalage;
	int after5years = originalage + 5;
	cout << "after 5 years you will be " << after5years << " years old.";
}
