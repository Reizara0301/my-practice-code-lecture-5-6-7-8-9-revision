# my-practice-code-lecture-5-6-7-8-9-revision
#Lecture 5
#Biography 
#include <iostream>
#include <string>
using namespace std;

int main()
{
    string age, address, name;
   
    cout << "Enter your name: \n"; 
    cin >> name;
    cout << "\nEnter your age: \n";
    cin >> age;
    cout << "\n Enter your address:\n" << address;
    cin >> address;
    cout << "\nYour name is: \n" << name;
cout << "\nYour age is: \n" << age;
cout << "\n Your address is: \n" << address;
}
#Temperature
#include <iostream>
#include <string>
using namespace std;

int main()
{
 double x;
    double y;
    cout << "Enter the temperature in Fahrenheit to be converted into celcius\n";
    cin >> x;
    y = (x - 32) * 0.5556;
    cout << "The temperature in Celcius is: " << y << endl;
}
#Temperature 2
#include <iostream>
#include <string>
using namespace std;

int main()
{
 double x,y;
cout << "Enter the temperature in celcius to be converted into Fahrenheit \n";
    cin >> x;
    y = (x *1.8) +32;
    cout << "The temperature in Fahrenheit is: " << y << endl;
}
#Cicle
#include <iostream>
#include <string>
using namespace std;

int main()
{
  double r,a,c;
    cout << "Enter the radius to calculate the area and circumference of the circle \n";
    cin >> r;
    a = 3.14 * r * r;
    c = 2 * 3.14 * r;
    cout << "The area of the circle is: \n " << a << endl;
  cout << "The circumference  of the circle is: \n " << c << endl;
}
# Rectangle Triangle Square
#include <iostream>
#include <string>
using namespace std;

int main()
{
   double length, width, rect, tri, sq;
    cout << "\n Calculating the area of Rectangle, Triangle and Square shapes\n";
    cout << "Enter the length:\n";
       cin >> length;
    cout << "\nEnter the width : \n";
    cin >> width;
   
    rect = length * width;
    tri = (length * width) * 0.5;
    sq= length*length;

    cout << "\nThe area of rectangle : \n" << rect;
    cout << "\nThe area of triangle: \n" << tri;
    cout << "\nThe area of  square: \n"<< sq;
}




Lecture #6
#Name that shape
#include<iostream>
using namespace std;
int main()
{
	double side;
	cout << "Enter the sides number to see the shape name (minimum 3 sides, maximum 10) \n";
	cin >> side;
	
	if (side <= 2)
	{
		cout << "You enter 2 as side, which is incorrect input";
	}
	else if (side==3) 
	{
		cout << "Triangle  has " << side << " sides" << endl;
	}
	else if (side == 4)
	{
		cout << "Square | Rectangle has " << side << " sides" << endl;
	}
	else if (side == 5)
	{
		cout << "Pentagon has " << side << " sides" << endl;
	}
	else if (side == 6)
	{
		cout << "Hexagon have " << side << " sides" << endl;

	}
	else if (side == 7)
	{
		cout << "Hepaton have " << side << " sides" << endl;

	}
	else if (side == 8)
	{
		cout << "Octagon have " << side << " sides" << endl;

	}

	else if (side == 9)
	{
		cout << "Nonagon have " << side << " sides" << endl;

	}
	else if (side == 10)
	{
		cout << "Decagon have " << side << " sides" << endl;

	}
	else 
	{
		cout << "Incorrect";

	}

	return 0;
}

#Profit of loss 
#include<iostream>
using namespace std;
int main()
{
	double Purchase, sale, x;
	cout << "Enter the purchase price: \n";
	cin >> Purchase;
	cout << "\nEnter the sale price: ";
	cin >> sale;
	x = sale - Purchase; 
	if (x > 0) 
	{
		cout << "You have a Profit of " << x << endl;
	}
	else if (x < 0) // For loss
	{
		cout << "You had a Loss of " << x << endl;
	}
	else if(x==0)
	{
		cout << "No loss no profit." << endl;
	}
	else
	{
		cout << "Incorrect input";
	}
	return 0;
}

#Number of checker Positve or not
#include <iostream>
using namespace std;

int main()
{
    cout << "Enter the number to see whether its positive, negative or zero\n";
    double number;
    cin >> number;
    if (number == 0)
    {
        cout << "The number you entered is zero";
    }

    else  if (number > 0)
    {
        cout << "The number you entered is positive";
    }
    else  if (number < 0)
    {
        cout << "The number you entered is negative";
    }
    else
    {
        cout << "Incorrect input";
    }
}
#even odd
#include <iostream>
using namespace std;
int main()
{
    cout << "Enter the number to see whether its even or odd\n";
    int number;
    cin >> number;
    if (number % 2 == 0)
    {
        cout << "\nThe entered number is Even\n";
    }
    else if (number % 2 != 0)
    {
        cout << "The number entered is odd";
    }
    else
    {
        cout << "Incorrect";
    }
}
#Vote
#include <iostream>
using namespace std;

int main()
{
    cout << "Kindly enter your age to see whether you can vote or not!\n";
    int age;
    cin >> age;
    if(age>=18)
    {
        cout << "You can vote";

    }
    else
    {
        cout << "Sorry not today";
    }
#Goodmorning
  // am.pm.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include<iostream>
using namespace std;
int main()
{
	cout << "Enter the time in 24 hour pattern to see whether it Morning, Afternoon, Evening or Night\n";
	double time;
	cin >> time;
	if (time < 12)
	{
		cout << "Good Morning";
	}
	else if (time >= 12 && time < 18)
	{
		cout << "Good Afternoon";
		}
	else if (time >=18 && time < 21)
	{
		cout << "Good Evening";
	}
	else if (time >=21 && time <24)
	{
		cout << "Good Night";
	}
	else
	{
		cout << "Incorrect input";
	}
}
}

#Lecture 7
#Earthquake
#include<iostream>
using namespace std;
int main()
{
	double mag;
	cout << "please enter the mangitude of the earthquake in numbers 0 input is not accepted : ";
	cin >> mag;

	

		if (mag < 2.0 && mag >0) {
			cout << " earthquake is considered to be a micro earthquake.";
		}
		else if (mag >= 2.0 && mag < 3)
		{
			cout << mag << " earthquake is considered to be a very minor earthquake.";
		}
		else if (mag >= 3.0 && mag < 4)
		{
			cout << mag << " earthquake is considered to be a minor earthquake.";
		}
		else if (mag >= 4.0 && mag < 5.0)
		{
			cout << mag << " earthquake is considered to be a light earthquake.";
		}
		else if (mag >= 5.0 && mag < 6.0)
		{
			cout << mag << " earthquake is considered to be a moderate earthquake." << endl;
		}
		else if (mag >= 6.0 && mag < 7)
		{
			cout << mag << " earthquake is considered to be a strong earthquake." << endl;
		}
		else if (mag >= 7.0 && mag < 8)
		{
			cout << mag << " earthquake is considered to be a major earthquake." << endl;
		}
		else if (mag >= 8.0 && mag <= 10)
		{
			cout << mag << " earthquake is considered to be a great earthquake." << endl;
		}
		else if (mag > 10.0)
		{
			cout << mag << " earthquake is considered to be a meteoric earthquake." << endl;
		}
	
		else {
			cout << "You entered an invalid value" << endl;
		}
		return 0;
		}
#Earthquake advance
#include<iostream>
using namespace std;
int main()
{

	int mag;
	std::cout << "Enter the enter the mangitude of the earthquake in numbers: ";
	std::cin >> mag;
	//Using the cin.fail function (when user enters alphabet instead of numbers)
	if (std::cin.fail())
	{
		std::cin.clear();
		std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
		std::cout << "Incorrect command\n: ";
	}
	
	else if (mag < 2.0 && mag >0) {
		cout << " earthquake is considered to be a micro earthquake.";
	}
	else if (mag >= 2.0 && mag < 3)
	{
		cout << mag << " earthquake is considered to be a very minor earthquake.";
	}
	else if (mag >= 3.0 && mag < 4)
	{
		cout << mag << " earthquake is considered to be a minor earthquake.";
	}
	else if (mag >= 4.0 && mag < 5.0)
	{
		cout << mag << " earthquake is considered to be a light earthquake.";
	}
	else if (mag >= 5.0 && mag < 6.0)
	{
		cout << mag << " earthquake is considered to be a moderate earthquake." << endl;
	}
	else if (mag >= 6.0 && mag < 7)
	{
		cout << mag << " earthquake is considered to be a strong earthquake." << endl;
	}
	else if (mag >= 7.0 && mag < 8)
	{
		cout << mag << " earthquake is considered to be a major earthquake." << endl;
	}
	else if (mag >= 8.0 && mag <= 10)
	{
		cout << mag << " earthquake is considered to be a great earthquake." << endl;
	}
	else if (mag > 10.0)
	{
		cout << mag << " earthquake is considered to be a meteoric earthquake." << endl;
	}

	else {
		cout << "You entered an invalid value" << endl;
	}
	return 0;

}
#Timekilling
#include<iostream>
using namespace std;
int main()
{
	int t, m;
	cout << "Until what time your friend will come? (Enter the time in minutes)\n";
	cin >> t;
	if (t >= 15)
	{
		cout << "Your friend will take more or equal to 15 minutes to come,\n enter the money amount to see if you can drink something";
		cin >> m;
		if (m > 5)
		{
			cout << "You have more than 5 AED, now you will buy a drink and wait for him" << endl;
		}
		else
		{
			cout << "You don't have enough money,\n Let's just walk around";
		}
	}
	else
	{
		cout << "Your friend will be here within 15 minutes, \n so you're just going to wait for him." << endl;
	}
	return 0;
}
#Starting a band
#include<iostream>
#include<string>
using namespace std;
int main()
{
	bool musician;
	string reply;
	string instrument;
	cout << "Do you play any musical instrument? \n type 'y' for yes \n and 'n' for no \n ";
	cin >> reply;
	if (reply == "y" || reply == "Y")
	{
		musician = true;
		if (musician == true)
		{
			cout << "What kind of insturment you can play \n type d if you're a drummer \n type g if you're a guitarist\n type o for other\n" << endl;
			cin >> instrument;
			if (instrument == "g" || instrument == "G")
			{
				cout << "That's great! I really needed a guitarist." << endl;
			}
			else if (instrument == "d" || instrument == "D")
			{
				cout << "That's great! I really needed a drummer." << endl;
			}
			else if(instrument =="o" || instrument == "O")
			{
				cout << "Ah I see, actually I'm looking for guitarist or a drummer.\n Let me know if you someone who plays them\n Thank you :)" << endl;
			}
			else
			{
				cout << "Incorrect input" << endl;
			}

		}
	}
		else if (reply == "N" || reply == "n")
		{
			musician = false;
			cout << "Oh! so you don't know how to play any instrument\n it's alright, let me know if you know someone who does \n Thanks" << endl;
		}
		else
		{

			cout << "Incorrect input" << endl;
		}

	
		return 0;
	}
#Mark my  words grade
#include <iostream>
using namespace std;

int main()
{
   cout << "Enter the marks from 1-100 to see the grade, 0 input is not accepted\n";
   double m;
   cin >> m;
   if (m>70)
   {
  cout << "You have a A Grade";
   }
   else if (m >= 60 && m < 70)
   {
  cout << "You have a B Grade";
   }
   else if (m >= 50 && m < 60)
   {
  cout << "You have a C Grade";
   }
   else if (m>40 && m<50)
   {
  cout << "You have a D Grade";
   }
   else if (m == 40 )
   {
  cout << "You have a JUST PASSED Grade";
   }
   else if(m<40 && m!=0)
   {
  cout << "You have a Fail Grade";
   }
   else 
   {
  cout << "Wrong input";
   }
}a
#Mark my words Grade. adv.
#include <iostream>
#include <exception>

using namespace std;
int main()
{

    int x;
    std::cout << "Enter the marks in number to see the grade: ";
    std::cin >> x;
    //Using the cin.fail function (when user enters alphabet instead of numbers)
    if (std::cin.fail())
    {
        std::cin.clear();
        std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
        std::cout << "Incorrect command\n: ";
    }

    else if (x > 70)
    {
        cout << "You have a A Grade";
    }
    else if (x >= 60 && x < 70)
    {
        cout << "You have a B Grade";
    }
    else if (x >= 50 && x < 60)
    {
        cout << "You have a C Grade";
    }
    else if (x > 40 && x < 50)
    {
        cout << "You have a D Grade";
    }
    else if (x == 40)
    {
        cout << "You have a JUST PASSED Grade";
    }
    else if (x < 40)
    {
        cout << "You have a Fail Grade";
    }
    else
    {
        cout << "Wrong input";
    }
}
#Letter checker Vowels Consonant
#include <iostream>
using namespace std;

int main()
{
	cout << "Enter a letter to see whether its a vowel or consonant\n";
	char c;
	cin >> c;
	//isalpha is a built in function to check for alphabet values in c++
	if (!isalpha(c))
	{
		cout << "you entered an incorrect value";
	}
	else if (c == 'a' || c == 'e' || c == 'i' || c == 'o' || c == 'u' || c == 'A' || c == 'E' || c == 'I' || c == 'O' || c == 'U')
	{
		cout << "you entered a vowel";

	}


	else
	{
		cout << "you entered a consonant";
	}
}
#Letter checker vowel, consonant and special characters advance
#include <iostream>
using namespace std;

int main()
{
	
	char l;
	int count1, count2; // variable for isalpha
	
	cout << "Enter a letter to check whether its a vowel or a consonant: ";
	cin >> l;
	if (l == 'a' || l == 'e' || l == 'i' || l == 'o' || l == 'u'|| l == 'A' || l == 'E' || l == 'I' || l == 'O' || l == 'U') // Checking if the entered character is a vowel
	{
		cout << "The input is a vowel." << endl;
	}
	count1 = isalpha(char(l)); // Using isalpha built-in function for alphabets
	count2 = isdigit(char(l)); // Using isdigit built-in function for digits
	if (count1 == 0 && count2 != 4) // Checking if the entered character is a special character, converting the special character into their ASCII code
	{
		cout << "The input is a special character." << endl;
	}
	else if (count1 != 2 && count2 == 4) // Checking if the entered character is a digit
	{
		cout << "The input is a digit." << endl;
	}
	else if (count1 != 0 && count2 != 4 && l != 'a' && l != 'e' && l != 'i' && l != 'o' && l != 'u' && l != 'A' && l != 'E' && l != 'I' && l != 'O' && l != 'U') // Checking if the entered character is a consonant
	{
		cout << "The input is a consonant." << endl;
	}
	else
	{
		cout << "The input is incorrect.";
			}
	return 0;
}
#France
#include <iostream>
using namespace std;
int main()
{
    cout << "What is the capital of France?\n";
    string capital;
    cin >> capital;
   
    if (capital == "Paris" || capital == "paris" || capital == "PARIS")
    {
        cout << "You enter the correct answer";
    }
    else 
    {
        cout << "Sorry wrong answer";
    }
    
    return 0;
}
#Theme park
#include <iostream>
using namespace std;
int main()
{
    cout << "Please enter your height in meters to check whether you can ride or not\n";
    double h, age;
    cin >> h;
    cout << "Please enter your age to check whether you can ride or not\n";
    cin >> age;
    if (age >= 5 && h >= 0.6)
    {
        cout << "You can ride";
    }
    else if (age < 5 && h < 0.5)
    {
        cout << "Sorry you cannot ride";
    }
    else
    {
        cout << "Incorrect input";
    }
    return 0;
}
#Lecture 8
# switch month
#include <iostream>
using namespace std;
int main()
{

	cout << "Kindly select the option number for the month you want to see the days of:\n";

	cout << " 1. January\n 2. February\n 3. March\n 4. April\n 5. May \n 6. June \n 7. July \n 8. August\n 9. September\n 10. October\n 11. November\n 12. December\n";
	int a;
	cin >> a;


	switch (a)
	{
	case 1:
	{
		cout << "The month of January have  days 31";
		break;
	}
	case 2:
	{
		cout << "The month of February have  days 28 if there is a leap year than 29";
		break;
	}
	case 3:
	{
		cout << "The month of March have  days 31";
		break;
	}
	case 4:
	{
		cout << "The month of April have  days 30";
		break;
	}
	case 5:
	{
		cout << "The month of May have  days 31";
		break;
	}
	case 6:
	{
		cout << "The month of June have  days 30";
		break;
	}
	case 7:
	{
		cout << "The month of July have  days 31";
		break;
	}
	case 8:
	{
		cout << "The month of August have  days 31";
		break;
	}
	case 9:
	{
		cout << "The month of September have  days 30 ";
		break;
	}
	case 10:
	{
		cout << "The month of October have  days 31";
		break;
	}
	case 11:
	{
		cout << "The month of November have  days 30";
		break;
	}
	case 12:
	{
		cout << "The month of December have  days 31";
		break;
	}

	default:
	{
		cout << "Invalid Input" << endl;
		break;
	}
	}

}
#exe gameplay
#include <iostream>

using namespace std;
int main()
{

		cout << "Would you like to continue? (Y/N): "; 
		char answer; 
		cin >> answer; 

			switch (answer)
			{ 
			
			case 'Y':
			case 'y':
			{
				cout << "You selected yes";
				break;
			}
					
			case 'N':
			case 'n':
			{
				cout << "You selected no";
				break;
			}
					
			default: 
			{
				cout << "incorrect command";
			}

			}
		cin.get(); //keeps console window open in Visual Studio
		return 0;
	}
#fuel 
#include <iostream>
using namespace std;
int main()
{
    cout << "Kindly enter how many litres you want to fill up your car\n";
    int lit;
    cin >> lit;
    if (lit != 0)
    {
        cout << "You have selected " << lit << " litres\n";
        cout << "Kindly select the fuel type you want for your car\n";
        cout << "Enter 'p' for Petrol\n 'd' for Diesel\n";
        char fuel;
        cin >> fuel;
        switch (fuel)
        {
        case 'P':
        case 'p':
        {

            cout << "You have selected Petrol for filling up your car\n "; 
            int c;
            c = lit * 0.8;
            cout << "\nThe price per litres is 0.8 now the total is " << c;
            break;
        }
        case 'd':
        case 'D':
        {
            cout << "You have selected Diesel for filling up your car ";
            int c;
            c = lit * 0.5;
            cout << "\nThe price per litres is 0.5 now the total is " << c;
            break;

            break;
        }

        default:
        {
            cout << "Incorrect command"; break;
        }
        }
    }
    else
    {
        cout << "Incorrect command\n ";
    }
    

}
#Fuel adv.
#include <iostream>
using namespace std;
int main()
{
    cout << "Kindly enter how many litres you want to fill up your car\n";
    double lit, c;


    std::cin >> lit;
    //Using the cin.fail function (when user enters alphabet instead of numbers)
    if (std::cin.fail())
    {
        std::cin.clear();
        std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
        std::cout << "Incorrect command\n: ";
    }

    else {
        cout << "You have selected " << lit << " litres\n";
        cout << "Kindly select the fuel type you want for your car\n";
        cout << "Enter 'p' for Petrol\n 'd' for Diesel\n";
        char fuel;
        cin >> fuel;
        switch (fuel)
        {
        case 'P':
        case 'p':
        {

            cout << "You have selected Petrol for filling up your car\n ";
           
            c = lit * 0.8;
            cout << "\nThe price per litres is 0.8 now the total is " << c << " AED" << endl;
            break;
        }
        case 'd':
        case 'D':
        {
            cout << "You have selected Diesel for filling up your car ";
           
            c = lit * 0.5;
            cout << "\nThe price per litres is 0.5 now the total is " << c << " AED" << endl;
            break;

            break;
        }

        default:
        {
            cout << "Incorrect command";
            break;
        }

        }
    }
}
#switch name that shape
#include<iostream>
using namespace std;
int main()
{
	int side;
	cout << "Enter the sides number to see the shape name (minimum 3 sides, maximum 10) \n";
	cin >> side;
	switch (side)
	{
	
	case 1:
	case 2:
	{ cout << "The minimum side required is 3, you have entered less than the requirement" << endl; break; }
	case 3:
	{ cout << "Triangle  has " << side << " sides" << endl;
		break;
	}
	case 4:
	{ cout << "Square | Rectangle has " << side << " sides" << endl;
		break;
	}
	case 5:
	{cout << "Pentagon has " << side << " sides" << endl;
		break;
	}
	case 6:
	{ cout << "Hexagon has " << side << " sides" << endl;
		break;
	}
	case 7:
	{ cout << "Heptagon has " << side << " sides" << endl;
		break;
	}
	case 8: 
	{ cout << "Octagon has " << side << " sides" << endl;
		break;
	}
	case 9:
	{ cout << "Nonagon has " << side << " sides" << endl;
		break;
	}
	case 10:
	{ cout << "Decagon has " << side << " sides" << endl;
		break;
	}
	default:
	{
		cout << "Incorrect command" << endl;
		break;
	}

	}

	
}
#switch capital of france
#include <iostream>
using namespace std;
int main()
{
    cout << "What is the capital of France? Select the option from below\n";
    cout << "\n Enter 'P' for Paris";
    cout << "\n Enter 'D' for Dubai";
    cout << "\n Enter 'N' if you don't know\n";
    char capital;
    cin >> capital;
    switch (capital)
    {
    case 'P':
    case 'p':
    {
        cout << "You're right, the capital of France is Paris" << endl;
        break;
    }
    case 'd':
    case 'D':
    {
        cout << "You're wrong, the capital of France is Paris not Dubai " << endl;
        break;
      }
    case 'n':
    case 'N':
    {
        cout << "The capital of France is Paris" << endl;
        break; 
    }
    default:
    {
        cout << "Incorrect command";

    }
    }

    return 0;
}
#switch grade
#include <iostream>
#include <exception>
#include <string>

using namespace std;
int main()
{


    

    cout << "Enter your full name" << endl;
    string name;
  // cin cannot read spaces, that is why we can use the getline code to read the input untill the next line
    getline(cin, name);
    

    cout << "\nEnter The Marks Between 0 To 100 to check your grade:";

    cout << "\nEnter The Mark: ";
    int marks;

    std::cin >> marks;
    //Using the cin.fail function (when user enters alphabet instead of numbers)
    if (std::cin.fail())
    {
        std::cin.clear();
        std::cin.ignore(std::numeric_limits<std::streamsize>::max(), '\n');
        std::cout << "Incorrect command\n: ";
    }

    else if (marks > 100)

    {

        /* Marks greater than 100 */

        cout << "\nKindly input your Marks Between Limit\n";
    }

    else

    {

        switch (marks / 10)

        {

        case 10:

        case 9:
        case 8:

        {
            /* Marks between 80-100 */


            cout << name <<" Your Grade Is: A Excellent";


            break;
        }
        case 7:

        {    /* Marks between 70-79 */


            cout << name << " Your Grade Is: B Very Good";


            break;
        }
        case 6:
        {
            /* Marks between 60-69 */


            cout << name << " Your Grade Is: C Fair";

            break;
        }
        case 5:
        {
            /* Marks between 50-59 */

            cout << name << " Your Grade Is: D Need more practice";


            break;
        }
        case 4:
        {
            /* Marks between 40-49 */



            cout << name << " Your Grade Is: E Need more practice";



            break;
        }
        default:
        {
            /* Marks less than 40 */


            cout << name << " You Grade Is: F or Fail\n";


        }
        }
    }
}
#Code if user enters more than one value input for char
#reading char size 
#include <iostream>
#include <string>
using namespace std;
int main()
{
	cout << "Enter The 'A' alphabet" << endl;
	char letter;

	// declaring a string to check the size
	string input = "";

	// get what ever user inputs, whole line until new line to check the size length
	getline(cin, input);

	//if the size is not equals to one, basically more than one letter, it will show this error message
	if (input.size() != 1)
	{
		cout << "You have entered more than one letter" << endl;
	}
	else
	{
		//converting the string into char because switch cannot accept any input except for int and char
		letter = input.at(0);

		switch (letter)
		{
		case 'a':
		case 'A':
			cout << "you have entered a letter\n";
			break;
		default:
			cout << "you did not entered 'A' letter";
		}

	}
}

#Lecture 9
#Remain positive
#include <iostream>
using namespace std;

int main()
{
	
	double myNum=20;
	
	while (myNum>0) {
		myNum = myNum - 0.5;
		cout << myNum << endl;
	}
#reverse 9
#include <iostream>  
using namespace std;

int main() 
{

    int num=108;
    
    while (num>=9 )  //while conditional check
    {
        //code to output then decrease number
        cout << num << endl;
        num = num - 9;
              
    }

    cin.get(); //keeps console window open in Visual  Studio
    return 0;
}
#Brute force!!
#include <iostream>
using namespace std;
int main()
{
	string password = "246";
	string userInput;
	int x = 5;
	cout << "You will only have 5 attempts" << endl;


	while (x > 0)
	{
		cout << "Enter the pass code for the safe" << endl;
		cin >> userInput;
		if (userInput == password)
		{
			cout << "You have finally unlocked the safe" << endl;

			break;
		}
		else
			x--;
	}
	//to print the ran out of message only if the password was not found within 5 attempts
	if (x == 0)
	{
		cout << "You ran out of attempts" << endl;
	}
}
#pointless box 
//To exit the loop if user enter anything other than one or two

#include <iostream>
using namespace std;
int main()
{
    cout << "Enter a number either 1 or 2\n";
    int x; 
    cin >> x;
    while (x != 0 && x <= 2 && !cin.fail())
    {
        if (x == 1)
        {
            cout << "you have entered the number 1\n";
        }
        else
        {
            cout << "you have entered the number 2\n";
        }

        cout << "Enter a number either 1 or 2\n";
        cin >> x;
     
    }
cout << "You did not enter the number 1 or 2";

}
#pointless box endless loop

//if you don't want to end the loop no matter what

#include <iostream>
using namespace std;
int main()
{
    cout << "Enter a number either 1 or 2\n";
    string x;
    cin >> x;
    while (true)
    {
        if (x == "1")
        {
            cout << "you have entered the number 1\n";
            cout << "Enter a number either 1 or 2\n";
            cin >> x;
        }
        else if (x == "2" )
        {
            cout << "you have entered the number 2\n";
            cout << "Enter a number either 1 or 2\n";
            cin >> x;
        }
        
        else
        {
            cout << "you did not enter the number 1 and 2\n";
            cout << "Enter a number either 1 or 2\n";
            cin >> x;
        }
        

    }


}

	
}
#input improvement while loop
#include <iostream> 
using namespace std; 
int main() {

char input;  
do {
	cout << "Would you like to Quit (Y/N)?" << endl;
	cin >> input;
	
} 
while ((input != 'Y') && (input != 'y') );

return 0;
}
#input improvement do while 
#include <iostream>
using namespace std;
int main() {

char input; 
do
{
	cout << "Would you like to Quit (Y/N)?" <<
		endl;
	cin >> input;
} 
while ((input != 'Y') && (input != 'y'));

return 0;
}
# brute force !
#include <iostream>
using namespace std;
int main()
{
	string password = "246"; 
	string userInput;
	


	while (userInput != password)
	{
		cout << "Enter the pass code for the safe" << endl;
		cin >> userInput;

	}
	//to print the ran out of message only if the password was not found within 5 attempts
	cout << "You found the code";
}
#Loopy 
#include <iostream>  
using namespace std; 
int main() {

	int myInt = 0, counter;
	cout << "Enter a number\n";
	cin >> counter;
	do
	{
		cout << myInt << endl;
		myInt++;

	} while (myInt<=counter);

}

#Revision

#Revision average
#include <iostream>
#include <string>
using namespace std;
int main()
{
	cout << "Hello User!! This is the program that takes 5 subject marks input and display the sum and average" << endl;
	cout << "Enter Marks for 5 Subjects" << endl;
	double s1, s2, s3, s4, s5;
	int average;
	cin >> s1;
	cin >> s2;
	cin >> s3;
	cin >> s4;
	cin >> s5;
	//first if statement
	if (!cin.fail() && s1 >= 0 && s1 <= 100 && s2 >= 0 && s2 <= 100 && s3 >= 0 && s3 <= 100 && s4 >= 0 && s4 <= 100 && s5 >= 0 && s5 <= 100)
	{
		
						cout << "1st Subject marks is " << s1 << endl;
						cout << "2nd Subject marks is " << s2 << endl;
						cout << "3rd Subject marks is " << s3 << endl;
						cout << "4th Subject marks is " << s4 << endl;
						cout << "5th Subject marks is " << s5 << endl;
						cout << "Sum is " << s1 + s2 + s3 + s4 + s5 << endl;
						cout << "Average is " << (s1 + s2 + s3 + s4 + s5) / 5 << endl;

	}
	//first else
	else
	{
		cout << "Incorrect command" << endl;
	}

}

#Revision age
#include <iostream>
#include <string>
using namespace std;

int main()
{
	cout << "*****************************************************************************\n" << endl;

	cout << "This program is to check your age and give you message according to your age" << endl;

	cout << "*****************************************************************************\n" << endl;

	cout << "\nEnter your age in numbers\n";
	int age;
	cin >> age;
	if (cin.fail())
	{
		cin.clear();
		cin.ignore();
		cout << "Kindly input correct value" << endl;
	}
	else if (age < 10)
	{
		cout << "Sorry you cannot participate" << endl;
	}
	else
	{
		if (age >= 10 && age <= 12)
		{
			cout << "Pre-teen" << endl;
		}
		if (age >= 13 && age <= 19)
		{
			cout << "Teen-age" << endl;
		}
		if (age >= 20 && age <= 29)
		{
			cout << "Twenties" << endl;
		}
		if (age >= 30 && age <= 39)
		{
			cout << "Thirties" << endl;
		}
		if (age >= 40 && age <= 49)
		{
			cout << "Fourties" << endl;
		}
		if (age >= 50 && age <= 59)
		{
			cout << "Fifties" << endl;
		}
		else if(age>=60)
		{
			cout << "Sixty or above" << endl;
		}
	}
}

#Revision 1 input
#include <iostream>
#include <string>
using namespace std;
int main()
{
	cout << "Enter just one input" << endl;
	
	// declaring a string to check the size
	string input = "";

	// get what ever user inputs, whole line until new line to check the size length
	getline(cin, input);

	//if the size is not equals to one, basically more than one letter, it will show this error message
	if (input.size() != 1)
	{
		cout << "You have entered more than one input" << endl;
	}
	else
	{
		cout << "You have entered just than one input" << endl;

	}
}

	#Lecture 10

#Countdown for loop
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int x = 10; x >=0; x--)
	{
		if (x != 0)
			cout << "X is " << x << "\n";
		else
			cout << "We have lift off" << endl;
	}

}




*****************************************************************************
SECOND METHOD

*****************************************************************************

#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int x = 10; x !=0; x--)
	{
		
			cout << "X is " << x << "\n";
		
			
	}
	cout << "We have lift off" << endl;
}

#Odd and Even for loop
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int x = 20; x <= 24; x++)
	{
		if (x %2==0)
			cout << x << " - even" << "\n";
		else
			cout << x << " - odd" << "\n";
	}

}

#For loop seven star row and column 
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 0; i < 7; i++)
	{ //execute the outer loop 5 times 
		for (int j = 0; j < 7; j++)
		{//execute the inner loop 5 x 5 times
			cout << "*"; //print 5 stars
		}
		cout << endl; //print to a new console line 
	}


}

#some counting 
#include <iostream>
#include <string>
using namespace std;
int main()
{
cout << " **********A program that counts up from 0 to 50 in increments of 1**********\n";
for (int x=0; x<51; x++)
{
	cout << x << endl;
}
cout << endl;
cout << " **********A program that counts down from 50 to 0 in decrements of 1**********\n";
for (int x = 50; x >= 0; x--)
{
	cout << x << endl;
}
cout << endl;
cout << " **********A program that counts up from 30 to 50 in increments of 1**********\n";
for (int x = 30; x < 51; x++)
{
	cout << x << endl;
}

cout << " **********A program that counts down from 50 to 10 in decrements of 2**********\n";
for (int x = 50; x > 11; x=x-2)
{
	cout << x << endl;
}

cout << " **********A program that counts up from 100 to 200 in increments of 5**********\n";
for (int x = 100; x < 201; x = x + 5)
{
	cout << x << endl;
}
}

#iterate through a word
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int x = 0; x < 4; x++)
	{
		string myWord = "ARSH";
		cout << myWord.at(x) << endl;
	}

}

#Lecture 10 exercises

#Decending star 7
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)
	{ //execute the outer loop 5 times 
		for (int j = 1; j <=i; j++)
		{//execute the inner loop 5 x 5 times
			cout << "*"; //print 5 stars
		}
		cout << endl; //print to a new console line 
	}


}

#Cube
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int r;
	cout << "Enter a number to find the cube" << endl;
	cin >> r;
	for (int x = 1; x <= r; x++)
	{
		cout << "\nNumber is " << x << " the cube is ";
		int y = x;
		y=y* y* y;
		cout << y;
	}

}

#9s
#include <iostream>
#include <string>
using namespace std;
int main()
{
	int sum = 0;
	
	for (int x = 100; x <= 200; x++)
	{
		if (x % 9 == 0)
		{
			cout << "\nNumber is " << x << endl;
					
			sum = sum + x;
		
					}
		
		
	}
	cout << "The sum is " << sum << endl;
}

#rising start 5
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)
	{ //execute the outer loop 5 times 
		for (int j = 1; j <=i; j++)
		{//execute the inner loop 5 x 5 times
			cout << "*"; //print 5 stars
		}
		cout << endl; //print to a new console line 
	}


}

#rise and fall
#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int i = 1; i <= 5; i++)
	{ //execute the outer loop 5 times 
		for (int j = 1; j <= i; j++)
		{//execute the inner loop 5 x 5 times
			cout << "*"; //print 5 stars
		}
		cout << endl; //print to a new console line 
	}


	for (int i = 1; i <= 5; i++) {
		for (int j = i; j <= 5; j++) { //execute the inner loop 5 times
			cout << "*"; //print reducing lines of stars
		}
		cout << endl; //print to a new console line 
	}


}
