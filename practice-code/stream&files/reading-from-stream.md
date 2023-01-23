#include <iostream>

using namespace std;

int main()
{
    cout<<"Enter First: ";
    int First;
    cin >> First;
    if(cin.fail()) {
        cout << "Enter a valid number!" <<endl;
        cin.clear();
        cin.ignore(numeric_limits<streamsize>::max(), '\n');
    }
    else break;
    
    cout<<"Enter second: ";
    int second;
    cin >> second;
    
    cout <<"you entered " <<First <<" and " <<second;

    return 0;
}