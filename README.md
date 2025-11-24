# function5
#include <iostream>
using namespace std;

void printBigger(int a, int b){
    if(a>b)
     cout<<"boyuk eded:"<<a<<endl;
    else if(b>a)
     cout<<"boyuk eded:"<<b<<endl;
    else
     cout<<"ededler beraberdir"<<endl;
}
int main(){
    int a,b;
    cout<<"iki eded daxil edin"<<endl;
    cin>>a>>b;
     printBigger(a,b);
    return 0;
}
