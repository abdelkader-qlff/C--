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


 #حلول سلسلة الخوارزميات بلغة C++:
 
#7-HALF NUMBER:
#include <iostream>
using namespace std;
int main() {
	int number;
	cout << "enter the number that you need to get his half: ";
	cin >> number;
	cout << "Half of the " << number << " is: " << number / 2;
}

#10-AVERAGE OF THREE MARKS:
#include <iostream>
using namespace std;
int main() {
	int mark1, mark2, mark3 , average;
	cout << "enter the first mark: ";
	cin >> mark1;
	cout << "enter the second mark: ";

 #14-SWAP NUMBER:
 #include <iostream>
using namespace std;
int main() {
	int number1, number2;
	cout << "enter your first number: ";
	cin >> number1;
	cout << "enter your second number: ";
	cin >> number2;
	cout << number1 << endl << number2 << endl << endl << number2 << endl << number1;
}
	cin >> mark2;
	cout << "enter the thrid mark: ";
	cin >> mark3;
	average = (mark1 + mark2 + mark3) / 3;
	cout << "average of entered marks is: " << average;
}

#15-RECTANGLE AREA:
#include <iostream>
using namespace std;
int main() {
	int a, b, area;
	cout << "enter the length of rectangle: ";
	cin >> a;
	cout << "enter the width of rectangle: ";
	cin >> b;
	area = a * b;
	cout << "the area of rectangle is: " << area;
}

#17-TRIANGLE AREA:
#include <iostream>
using namespace std;
int main() {
	int a, h, area;
	cout << "enter a: ";
	cin >> a;
	cout << "enter h: ";
	cin >> h;
	area = (a / 2 ) * h;
	cout << "the triangle area is: " << area;
}


#20-THE CIRCLE AREA:
#include <iostream>
using namespace std;
int main() {
	int A;
	float const PI = 3.14;
	cout << "enter A: ";
	cin >> A;
	float area = PI * ((A/2)*(A/2));
	cout << "the Circle Area Through Diameter is: " << area;
}


#21-THE CIRCLE AREA ALONG THE CRCUFERENCE:
#include <iostream>
using namespace std;
int main() {
	int l;
	float const PI = 3.14;
	cout << "enter l: ";
	cin >> l;
	float area = (l * l) / (4 * PI);
	cout << "the Circle Area Along the Circumference is: " << area;
}


#22-THE CIRCLE AREA INSCRIBED IN AN ISOSCELES TRIANGLE:
#include <iostream>
using namespace std;
int main() {
	float a, b;
	const float PI = 3.14;
	cout << "enter a: ";
	cin >> a;
	cout << "enter b: ";
	cin >> b;
	float area = (PI)*((b*b)/4)*((2*a-b)/(2*a+b));
	cout << "the Circle Area Inscribed in an Isosceles Triangle is: " << area;
}
