#include <iostream>
#include<conio.h>
using namespace std;

bool isPrima(int a) {
    if (a==2){
            return true;
    }
    for (int i=2;i<a;i++){
        if (a%i==0) return false;
    }
}
int main()
{
    for (int i=2;i<=100;i++){
        if (isPrima (i)) cout << i << " ";
    }
    getch();
    return 0;
}
