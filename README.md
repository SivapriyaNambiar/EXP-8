# EXP-8
```
// NAME - SHLOKA PATEL 
// PRN - 23070123120 
// EXPERIMENT - 8(A)      

#include<iostream> 
using namespace std; 

int main() 
{
    int a[4][4], i, j, k, l;
    for (i=0; i<4; i++) {
        for (j=0; j<4; j++) {
            cout<<"Enter elements: ("<<i<<j<<"):";
            cin>>a[i][j];
        }
    }
    for (k=0; k<4; k++) {
        for (l=0; l<4; l++) {
            cout<<a[k][l];
            cout<<" ";
        }
        cout<<"\n";
    }
}
```
