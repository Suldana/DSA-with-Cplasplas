question one :::: find the maximum and the minimum number

#include <iostream>

using namespace std;

int max(int first, int second) {
    if(first > second) {
        return first;
    }else return second;
}

int main()
{
    int numbers = max(100, 200);
    std::cout << numbers << std::endl;

    return 0;
}

question two :::: Define a program to find out whether a given number is even or odd.

#include <iostream>

using namespace std;

void check(int num) {
    if(num % 2 == 0) {
        cout << num <<"is even Number";
    }else
    cout << num <<"is odd number";
}

int main()
{
check(6);
    return 0;
}


question three :::: A person is eligible to vote if his/her age is greater than or equal to 18. Define a method to find out if he/she is eligible to vote.

#include <iostream>

using namespace std;

void eligible(int age) {
    if(age >= 18) {
        std::cout << age <<"is eligible to vote" << std::endl;
    }else
    cout << age <<"isn't eligible to vote";
}
int main()
{
    eligible(10);
    return 0;
}


question four :::: Write a program to print the sum of two numbers entered by user by defining your own method.

#include <iostream>

using namespace std;

void numbers(int num1, int num2) {
    int sum = num2 + num1;
    std::cout << sum << std::endl;
}
int main()
{
    numbers(56, 85);
    return 0;
}


question five ::::  Define a method that returns the product of two numbers entered by user.

#include <iostream>

using namespace std;

void numbers(int num1, int num2) {
    cout << "enter the first number: " << endl;
    std::cin >> num1;
    cout << "enter the second number: " << endl;
    cin >> num2;
    int sum = num2 * num1;
    std::cout << sum << std::endl;
}
int main()
{
    numbers(23, 56);
    return 0;
}