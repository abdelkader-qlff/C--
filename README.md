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


#30-TRYING IN THE LOOP LESSON:
#include <iostream>
using namespace std;
int main() {
	int number, counter;
	int factorial = 1;
	cout << "enter your number: ";
	cin >> number;
	if (number >= 0) {
		counter = number + 1;
		counter = counter - 1;
		factorial = factorial * counter;
		if (counter == 1) {
			cout << factorial;
		}
	}
}


31-POWER OF 2,3,4:
#include <iostream>
using namespace std;
int main() {
	int number;
	cout << "enter your number: ";
	cin >> number;
	int number2 = number * number;
	int number3 = number * number * number;
	int number4 = number * number * number * number;
	cout << number2 << endl << number3 << endl << number4 << endl;
}


#39-PAY REMAINDER:
#include <iostream>
using namespace std;
int main() {
	int totalbill, cashpaid, paidback;
	cout << "enter the totalbill: ";
	cin >> totalbill;
	cout << "enter the cashpaid: ";
	cin >> cashpaid;
	paidback = cashpaid - totalbill;
	cout << "paid back is: " << paidback;
}


#40-SERVICE FEE AND SALES TAX:
#include <iostream>
	using namespace std;
int main() {
	float billvalue, services_fee, sales_tax, total_price;
	cout << "enter the bill value: ";
	cin >> billvalue;
	services_fee = (10 * billvalue) / 100;
	sales_tax = (16 * billvalue) / 100;
	total_price = billvalue + services_fee + sales_tax;
	cout << "the total price is: " << total_price;
} 


#42-THE DURATION IN SECONDS:
#include <iostream>
	using namespace std;
int main() {
	int seconds, minutes, hours, days;
	cout << "how much of days: ";
	cin >> days;
	int daytosecond = days * 24 * 60 * 60;
	cout << "how much of hours: ";
	cin >> hours;
	int hourtosecond = hours * 60 * 60;
	cout << "how much of minutes: ";
	cin >> minutes;
	int minutetosecond = minutes * 60;
	cout << "how much of seconds: ";
	cin >> seconds;
	int total_seconds = seconds + daytosecond + hourtosecond + minutetosecond;
	cout << "the total srconds is: " << total_seconds;
} 


#43-SECONDS TO DAYS,HOURS,MINUTES:
#include <iostream>
	using namespace std;
	int main() {
		int seconds = 0;
		int totalseconds = 193535;
		int secondtoday = totalseconds / (24 * 60 * 60);
		totalseconds %= (24 * 60 * 60);
		int secondtohour = totalseconds / (60 * 60);
		totalseconds %= (60 * 60);
		int secondtominute = totalseconds / 60;
		totalseconds %= 60;
		seconds = totalseconds;
		cout << secondtoday << " days" << endl << secondtohour << " hours" << endl << secondtominute << " minutes" << endl << seconds << " seconds";
	}


 #47-LOAN INSTALMENT MONTHS:
 #include <iostream>
using namespace std;
int main() {
	int loanamoun, monthlypayment, months;
	cout << "enter the the total price: ";
	cin >> loanamoun;
	cout << "enter your monthly payment: ";
	cin >> monthlypayment;
	months = loanamoun / monthlypayment;
	cout << "you need " << months << " mmonths to settle the loan";
}


#48-:

