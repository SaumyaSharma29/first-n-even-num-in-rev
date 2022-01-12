# first-n-even-num-in-rev
#include <bits/stdc++.h>
using namespace std;
void PrintReverseOrder(int N)
{
 
    for (int i = N; i > 0; i--)
        cout << i << " ";
 
}
int main()
{
    int N = 5;
 
    PrintReverseOrder(N);
 
    return 0;
}
