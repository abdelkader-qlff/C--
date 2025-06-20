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


#48-MONTHLY LOAN INSTALMENT:
#include <iostream>
using namespace std;
int main() {
	int loanamoun, monthlypayment, months;
	cout << "enter the the total price: ";
	cin >> loanamoun;
	cout << "enter your monthly payment: ";
	cin >> months;
	monthlypayment = loanamoun / months;
	cout << "the monthly instalment amount is: " << monthlypayment;
}


#Increment Decrement Operators: ++, --:

#include <iostream>
using namespace std;
int main() {
	int A = 10, B = 20;
	A++; // ++A.;
	B--; // --B;
	cout << "A = " << A << endl;
	cout << "B = " << B << endl;
}


#Postfix vs Prefix : ++A vs A++ , --A vs A--:
#include <iostream> 
using namespace std; 
int main() {
	int A = 10;
	int B = A++; // B will take the old value of A, then A will increase by 1 
	cout << "B = " << B << endl;
	cout << "A = " << A << endl;

	B = ++A; // A will increase by 1, then 8 will take the new value 
	cout << "B = " << B << endl;
	cout << "A = " << A << endl;

	return 0;
}


#RELATION OPERATORS:
#include <iostream> 
using namespace std; 
int main() {
	int A, B;
	cout << "enter the first number: ";
	cin >> A;
	cout << "enter the second number: ";
	cin >> B;
	cout << A << " = " << B << " is " << (A == B) << endl;
	cout << A << " != " << B << " is " << (A != B) << endl;
	cout << A << " < " << B << " is " << (A < B) << endl;
	cout << A << " > " << B << " is " << (A > B) << endl;
	cout << A << " <= " << B << " is " << (A <= B) << endl;
	cout << A << " >= " << B << " is " << (A >= B) << endl;
	return 0;
}


#TRAINING ON FUNCTIONS(not !;and &&;or ||):
#include <iostream>
using namespace std;
int main() {
	cout << (12 >= 12) << endl;
	cout << !(12 >= 12) << endl;
	cout << (1 && 1) << endl;
	cout << ((7 == 7) && (7 > 5)) << endl;
	cout << (12 > 7) << endl;
	cout << !(12 < 7) << endl;
	cout << (1 && 0) << endl;
	cout << ((7 == 7) && (7 < 5)) << endl;
	cout << (0 || 1) << endl;
	cout << (0 || 0) << endl;
	cout << !(0) << endl;
	cout << !(1 || 0) << endl;
	cout << ((7 < 7) || (7 > 5)) << endl;
	cout << ((7 == 7) && !(7 < 5));
}


#16-Rectangle area Through Diagonal and Side Area:
#include <iostream>
#include <cmath>
using namespace std;
int main() {
	int a, d;
	cout << "enter a: ";
	cin >> a;
	cout << "enter d: ";
	cin >> d;
	float area = a * sqrt(pow(d, 2) - pow(a, 2));
	cout << "The Rectangle area Through Diagonal and Side Area: " << area;
}


#18-CIRCLE AREA:
#include <iostream>
#include <cmath>
using namespace std;
int main() {
	int r;
	const float PI = 3.14;
	cout << "enter r: ";
	cin >> r;
	float area = PI * pow(r, 2);
	cout << "The Circle Area: " << ceil(area);
}


#19-CIRCLE AREA THROUGH DIAMETER:
#include <iostream>
#include <cmath>
using namespace std;
int main() {
	int D;
	const float PI = 3.14;
	cout << "enter D: ";
	cin >> D;
	float area = ceil((PI * pow(D, 2)) / 4);
	cout << "The CIRCLE AREA THROUGH DIAMETER: " << area;
}


#20-Circle Area Inscribed in a Square:
#include <iostream>
#include <cmath>
using namespace std;
int main() {
	int A;
	const float PI = 3.14;
	cout << "enter A: ";
	cin >> A;
	float area = ceil((PI * pow(A, 2)) / 4);
	cout << "The Circle Area Inscribed in a Square: " << area;
}


#21- Circle Area Along the Circumference:
#include <iostream>
#include <cmath>
using namespace std;
int main() {
	int l;
	const float PI = 3.14;
	cout << "enter l: ";
	cin >> l;
	float area = pow(l, 2) / (4 * PI);
	cout << "The Circle Area Along the Circumference: " << floor(area);
}


#22-Circle Area Inscribed in an Isosceles Triangle:
#include <iostream>
#include <cmath>
using namespace std;
int main() {
	float a, b;
	const float PI = 3.14;
	cout << "enter a: ";
	cin >> a;
	cout << "enter b: ";
	cin >> b;
	float area = PI * (pow(b, 2) / 4) * ((2 * a - b) / (2 * a + b));
	cout << "The Circle Area Inscribed in an Isosceles Triangle: " << floor(area);
}


#23-Circle Area circle Described Around an Arbitrary Triangle:
#include <iostream>
#include <cmath>
using namespace std;
int main() {
	float a, b, c;
	const float PI = 3.14;
	cout << "enter a: ";
	cin >> a;
	cout << "enter b: ";
	cin >> b;
	cout << "enter c: ";
	cin >> c;
	int p = (a + b + c) / 2;
	float area = PI * pow(((a * b * c) / (4 * sqrt(p * (p - a) * (p - b) * (p - c)))), 2);
	cout << "The Circle Area circle Described Around an Arbitrary Triangle: " << round(area);
}


#31-Pwer of 2,3,4:
#include <iostream>
using namespace std;
int main() {
	int number;
	cout << "enter your number: ";
	cin >> number;
	cout << pow(number, 2) << endl << pow(number, 3) << endl << pow(number, 4) << endl;
}


#32-Power of M:
#include <iostream>
using namespace std;
int main() {
	int number, M;
	cout << "enter your number: ";
	cin >> number;
	cout << "enter M: ";
	cin >> M;
	cout << pow(number, M) << endl;
}


#Structures:
#include <iostream>
using namespace std;
struct friends {
	int age;
	string name;
	char firstletter;
};

int main() {
	friends myfriend1, myfriend2;

	myfriend1.age = 17;
	myfriend1.name = "abdelkader";
	myfriend1.firstletter = 'A';

	cout << " \" " << myfriend1.name << " \" " << myfriend1.age << " \" " << myfriend1.firstletter << " \" " << endl;

	cout << "what is his name: ";
	cin >> myfriend2.name;
	cout << "what is your friend's age: ";
	cin >> myfriend2.age;
	cout << "what is the first word in his name: ";
	cin >> myfriend2.firstletter;

	cout << "informations data of your friend " << myfriend2.name << " is: " << endl;
	cout << "name: " << myfriend2.name << endl;
	cout << "age: " << myfriend2.age << endl;
	cout<< "first word in his name: " << myfriend2.firstletter << endl;
}


#Enums:
#include <iostream>
using namespace std;
enum gender { male = 'M', female = 'F' };
enum married { NO , YES };
enum color { red = 1, blue , black };

int main() {
	gender mygender = gender::male;
	married mymarried = married::NO;
	color mycolor = color::black;
	cout << "Gender: " << (char)mygender << endl;
	cout << "Married: " << mymarried << endl;
	cout << "favourite color: " << mycolor << endl;
}


#Nested Structures and Enums - Full Practical Example:
#include <iostream>
using namespace std;

enum engender { male = 'M', female = 'F' };
enum enmarried { NO , YES };
enum encolor { red = 1, blue , black };

struct stAddress {
	string streetname;
	string pobox;
	string zipcode;
};

struct stcontact {
	string phone;
	string email;
	stAddress address;
};

struct stinfoperson{
	string fullname;
	short int age;

	stcontact contact;

	enmarried married;
	engender gender;
	encolor color;

};

int main() {
	stinfoperson person1;
	person1.fullname = "anane abdelkader";
	person1.age = 17;

	person1.contact.address.streetname = "kazirna";
	person1.contact.address.pobox = "0600";
	person1.contact.address.zipcode = "0001";
	person1.contact.email = "abdelkader20085@gmail.com";
	person1.contact.phone = "+213776459813";

	person1.gender = engender::male;
	person1.married = enmarried::NO;
	person1.color = encolor::black;

	cout << "Name: " << person1.fullname << endl;
	cout << "Age: " << person1.age << endl;
	cout << "Street Name: " << person1.contact.address.streetname << endl;
	cout << "PoBox: " << person1.contact.address.pobox << endl;
	cout << "Zip Code: " << person1.contact.address.zipcode << endl;
	cout << "E-mail: " << person1.contact.email << endl;
	cout << "Phone Number: " << person1.contact.phone << endl;
	
	cout << "Gender: " << (char)person1.gender << endl;
	cout << "Married: " << person1.married << endl;
	cout << "Favourite Color: " << person1.color << endl;
}


#Data Type Conversion
#include <iostream>
#include <string>
using namespace std;
int main() {
	//float to intiger
	double float_num = 18.99;
	int int_num = (int)float_num;
	cout << "float to intiger: " << int_num << endl;

	//string and float(stof) to intiger
	string name = "123";
	string f_num = "15.25";
	int str_to_int = stoi(name);
	int str_to_float = stof(f_num);//stod() if it is a double
	cout << "string to intiger: " << str_to_int << endl;
	cout << "float to intiger: " << str_to_float << endl;

	//intiger and float to string
	int num1 = 123;
	double num2 = 18.99;
	string ST1, ST2;
	ST1 = to_string(num1);
	ST2 = to_string(num2);
	cout << "intiger to string: " << ST1 << endl;
	cout << "float to string: " << ST2 << endl;
}


#
#include<iostream>
#include <string>
using namespace std;
int main() {
	string string1, string2, string3;
	cout << "enter string1: " << endl;
	getline(cin, string1);
	cout << "the length of string1 is: " << string1.length() << endl;
	cout << "characters at 0,2,4,7 are: " << string1[0] << " " << string1[2] << " " << string1[4] << " " << string1[7] << endl;
	cout << "please enter string2: ";
	cin >> string2;
	cout << "please enter string3: ";
	cin >> string3;
	string connection = string2 + string3;
	cout << "concatenating string2 and string3: " << connection << endl;
	int beating = stoi(string2) * stoi(string3);
	cout << string2 << " * " << string3 << " = " << beating;
}


#functions://void
#include <iostream>
using namespace std;
void desplay_mycart_info() {
	string Name = "Abdelkader";
	int Age = 17;
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
void print_square_stars() {
	cout << "*********************" << endl;
}
void space() {
	cout << "\n";
}
void word_H() {
	cout << "*    *" << endl;
	cout << "*    *" << endl;
	cout << "******" << endl;
	cout << "*    *" << endl;
	cout << "*    *" << endl;
}


int main() {
	desplay_mycart_info();
	space();
	print_square_stars();
	print_square_stars();
	print_square_stars();
	print_square_stars();
	space();
	word_H();
}


#getline:
#include <iostream>
#include <string>
using namespace std;
int main() {
	int age;
	string name;
	cout << "enter your age:";
	cin >> age;
	cout << "enter your name: ";
	cin.ignore(1, '\n');
	getline(cin, name);
	cout << "age: " << age << endl << "your name is: " << name << endl;
	return 0;
}


