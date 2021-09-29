# Killing-Time
Lecture 7 Exercise 5
#include<iostream>
using namespace std;
int main()
{
	int time;
	int money;
	cout << "hey how much time will you take to reach Dubai Mall? " << endl; //the user will enter the time
	cin >> time; //user input will be stored in variable time
	if(time>=15)  //if time greater than or equal to 15 then it will move to the inner if else statement
{
		cout << "How much money do you have? " << endl; 
		cin >> money;
		cout << money << " AED " << endl;
		if (money > 5)  //if money is greater than 5 then the if statement will be executed, if not then else will be executed
		{
			cout << "Buy a coffee from a nearby cafe." << endl;
		}
		else
		{
			cout << "Go for a stroll. " << endl;
		}

}
	else if (time < 15)  //if time is less than 15 minutes then the following message will be displayed
	{
		cout << "Wait for your friend in the Food Court." << endl;
	}
	return 0;
}
