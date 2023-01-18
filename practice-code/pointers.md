#include <iostream>

using namespace std;

int main()
{
    // int number[] = {10, 20, 30};
    // int* ptr = number;
    // // ptr++;
    // // ptr--;
    // cout<<*(ptr + 0);
    
    
    // int x = 30;
    // int y = 40;
    // int* ptrx = &x;
    // int* ptry = &y;
    // if(ptrx > ptry) {
    //     cout <<*ptry;
    // }else{
    //     cout <<*ptrx;
        
    // } 
    
    
    // int numbers[] = {10, 20, 30};
    // int* ptr = &numbers[2];
    // cout <<*(ptr + 2);
    // int i = 0;
    // while(i < size_t(numbers)) {
    //     // cout << ptr[i];
    //     i--;
    // }
    
    int numbers[] = {10, 20, 30};
    int* ptr = &numbers[size(numbers)-1];
    while(ptr >= numbers) {
        cout << *ptr;
        ptr--;
    }
    

    return 0;
}