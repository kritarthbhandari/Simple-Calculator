# Simple-Calculator
#include<iostream>
using namespace std;
int main(){
    float x,y;
    cout<<"Enter first number : ";
    cin>>x;
    cout<<"Enter second number : ";
    cin>>y;
    int n;
    cout<<"Press 1 for addition "<<endl<<"Press 2 for subtraction "<<endl<<"Press 3 for multiplication "<<endl<<"Press 4 for divide "<<endl<<"Press 5 for exit "<<endl<<"Enter choice : ";
    cin>>n;
    while(n!=5){
        switch(n){
            case(1):
            cout<<float(x+y);
            break;
            case(2):
            cout<<float(x-y);
            break;
            case(3):
            cout<<float(x*y);
            break;
            case(4):
            cout<<float(x/y);
            break;
            default:
            cout<<"Invalid choice";
        }break;
    }
}
